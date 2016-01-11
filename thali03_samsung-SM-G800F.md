#### Test 5563415007e42e9_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 3750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3750):  
I/SELinux ( 3750):  
I/SELinux ( 3750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3750): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3750): >>>>> Normal User
E/dalvikvm( 3750): >>>>> com.android.vending [ userId:0 | appId:10031 ]
E/SELinux ( 3750): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2419): onPackageAdded : com.example.hello
D/TimaKeyStoreProvider( 3750): in addTimaSignatureService
D/TimaKeyStoreProvider( 3750): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3750): Added TimaKesytore provider
D/dalvikvm( 3750): GC_CONCURRENT freed 2996K, 32% free 9568K/13912K, paused 2ms+2ms, total 21ms
D/dalvikvm( 3750): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 3659): GC_CONCURRENT freed 2376K, 27% free 10420K/14152K, paused 2ms+2ms, total 35ms
I/dalvikvm( 3750): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3750): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x000e
--------- beginning of /dev/log/system
I/PowerManagerService( 2419): [PWL] On : 0 (35002 ms ago)
I/PowerManagerService( 2419): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService( 2419): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2578, ws=null) (elapsedTime=15113)
W/dalvikvm( 3158): VFY: unable to find class referenced in signature (Landroid/util/Size;)
D/SensorService( 2419):   0.2 0.0 9.9
W/ResourceType( 3659): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
W/PackageManager( 3659): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 3659): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 3659): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 3659): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 3659): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 3659): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 3659): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 3659): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 3659): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 3659): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 3659): 	at java.lang.Thread.run(Thread.java:841)
D/Finsky  ( 3750): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3158): Module APK com.google.android.play.games already loaded
I/dalvikvm( 3750): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 3750): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 3750): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 3750): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 3750): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3750): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3750): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 3750): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3750): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 3750): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3750): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 3750): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3750): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3750): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3750): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x0385
I/dalvikvm( 3750): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3750): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x0019
D/Ads     ( 3750): Skipping gmscore version check
D/Finsky  ( 3750): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3750): [1] Libraries$2.run: Finished loading 1 libraries.
I/GCoreNlp( 2735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/Finsky  ( 3750): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.location.PROVIDERS_CHANGED}]
I/dalvikvm( 3750): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3750): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3750): VFY: replacing opcode 0x6e at 0x0013
D/Finsky  ( 3750): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/GCoreUlr( 2735): DispatchingService.onCreate()
,I/SELinux ( 3794): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3794):  
D/dalvikvm( 3659): GC_CONCURRENT freed 2025K, 27% free 10388K/14152K, paused 2ms+2ms, total 39ms
I/SELinux ( 3794): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3794):  
I/SELinux ( 3794):  
I/SELinux ( 3794): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3794): >>>>> Normal User
E/dalvikvm( 3794): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
E/SELinux ( 3794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3158): GC_CONCURRENT freed 1411K, 22% free 11593K/14728K, paused 9ms+5ms, total 75ms
D/TimaKeyStoreProvider( 3794): in addTimaSignatureService
D/TimaKeyStoreProvider( 3794): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3794): Added TimaKesytore provider
I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.location.PROVIDERS_CHANGED
D/dalvikvm( 3794): GC_CONCURRENT freed 3000K, 32% free 9567K/13920K, paused 3ms+2ms, total 21ms
D/dalvikvm( 3794): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/Documents( 3794): Loading roots for com.android.externalstorage.documents
I/SELinux ( 3810): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3810):  
D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9502K/10892K, paused 2ms+3ms, total 29ms
I/SELinux ( 3810): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3810):  
I/SELinux ( 3810):  
I/SELinux ( 3810): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3810): >>>>> Normal User
E/dalvikvm( 3810): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
E/SELinux ( 3810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/Icing   ( 3158): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10892K, paused 2ms+3ms, total 25ms
D/TimaKeyStoreProvider( 3810): in addTimaSignatureService
D/TimaKeyStoreProvider( 3810): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3810): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10892K, paused 3ms+3ms, total 27ms
I/Icing   ( 3158): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/[SBeam] ( 2828): SBeamEnabler.isPowerOff : shutdown - 0, reason - 0, retVal - false
D/[SBeam] ( 2828): SBeamEnabler.saveSbeamOn : on[false] save[false] fromNfc[true]
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/GCoreUlr( 2735): WorldUpdater:android.location.PROVIDERS_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/[SBeam] ( 2828): SBeamEnabler.saveStatus : on[false] last[true] 
D/[SBeam] ( 2828): SBeamEnabler.updateState
D/[SBeam] ( 2828): SBeamEnabler.isSBeamOn > 0
D/[SBeam] ( 2828): SBeamEnabler.isSBeamLastStatusOn > true(0)
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:2
W/ContextImpl( 2828): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.nfc.SBeamEnabler.updateState:667 com.android.settings.nfc.SBeamEnabler.saveSbeamOn:658 
I/GCoreUlr( 2735): Unbound from all location providers
I/GCoreUlr( 2735): Place inference reporting - stopped
E/CscReceiver( 2751): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 2751): Recieve Sim State Changed : NOT_READY
I/SELinux ( 3828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3828):  
D/AndroidRuntime( 3798): 
D/AndroidRuntime( 3798): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3798): CheckJNI is OFF
D/AndroidRuntime( 3798): setted country_code = Poland
D/AndroidRuntime( 3798): setted countryiso_code = PL
D/AndroidRuntime( 3798): setted sales_code = PLS
D/AndroidRuntime( 3798): readGMSProperty: start
D/AndroidRuntime( 3798): readGMSProperty: already setted!!
D/AndroidRuntime( 3798): readGMSProperty: end
D/AndroidRuntime( 3798): addProductProperty: start
D/dalvikvm( 3810): GC_CONCURRENT freed 2997K, 32% free 9572K/13916K, paused 19ms+2ms, total 68ms
D/dalvikvm( 3810): WAIT_FOR_CONCURRENT_GC blocked 47ms
D/dalvikvm( 3798): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3798): Added shared lib libjavacore.so 0x0
I/SELinux ( 3828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3828):  
I/SELinux ( 3828):  
I/SELinux ( 3828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3828): >>>>> Normal User
E/dalvikvm( 3828): >>>>> com.fmm.dm [ userId:0 | appId:1000 ]
E/SELinux ( 3828): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3798): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3798): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3798): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/GCoreUlr( 2735): DispatchingService.onDestroy()
I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
D/TimaKeyStoreProvider( 3828): in addTimaSignatureService
D/ExternalStorage( 3810): After updating volumes, found 1 active roots
I/GCoreUlr( 2735): Unbound from all location providers
I/GCoreUlr( 2735): Place inference reporting - stopped
D/TimaKeyStoreProvider( 3828): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3828): Added TimaKesytore provider
D/Documents( 3794): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3794): Loading roots for com.android.providers.downloads.documents
D/Documents( 3794): Loading roots for com.android.providers.media.documents
D/Documents( 3794): Loading roots for com.google.android.apps.docs.storage
D/dalvikvm( 3828): GC_CONCURRENT freed 2995K, 32% free 9565K/13912K, paused 3ms+1ms, total 25ms
D/dalvikvm( 3828): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/SELinux ( 3847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3847):  
I/SELinux ( 3847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3847):  
I/SELinux ( 3847):  
I/SELinux ( 3847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3847): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3847): >>>>> Normal User
E/dalvikvm( 3847): >>>>> com.google.android.apps.docs [ userId:0 | appId:10094 ]
E/SELinux ( 3847): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/memtrack( 3798): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3798): failed to load memtrack module: -2
D/TimaKeyStoreProvider( 3847): in addTimaSignatureService
D/TimaKeyStoreProvider( 3847): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3847): Added TimaKesytore provider
D/dalvikvm( 3798): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 3859): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3859):  
I/SELinux ( 3859): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3859):  
I/SELinux ( 3859):  
I/SELinux ( 3859): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3859): >>>>> Normal User
E/dalvikvm( 3859): >>>>> com.sec.android.omc [ userId:0 | appId:1000 ]
E/SELinux ( 3859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3847): GC_CONCURRENT freed 2987K, 32% free 9579K/13916K, paused 5ms+2ms, total 31ms
D/dalvikvm( 3847): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/AndroidRuntime( 3798): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 3859): in addTimaSignatureService
D/TimaKeyStoreProvider( 3859): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3859): Added TimaKesytore provider
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=10 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=11 createSurf (16x16),-1 flag=20004, EimLayer
D/Launcher.HomeView( 2782): onPause
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2419,o:f
I/SurfaceFlinger( 1921): id=12 createSurf (1x1),1 flag=404, iello
D/dalvikvm( 3859): GC_CONCURRENT freed 3004K, 32% free 9565K/13920K, paused 4ms+1ms, total 44ms
D/dalvikvm( 3859): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/AndroidRuntime( 3798): Shutting down VM
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2782,o:f
D/dalvikvm( 3798): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 3873): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3873):  
D/p2.ApplicationLoader( 3659): Process time: 3567
D/p2.ApplicationLoader( 3659): ##############################  apps after loading: 
I/Omc:OmcReceiver( 3859): onReceive : android.intent.action.SIM_STATE_CHANGED
I/SELinux ( 3873): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3873):  
I/SELinux ( 3873):  
I/SELinux ( 3873): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
E/SELinux ( 3873): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
E/dalvikvm( 3873): >>>>> Normal User
E/dalvikvm( 3873): >>>>> com.example.hello [ userId:0 | appId:10612 ]
E/SELinux ( 3873): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/Omc:OmcModel( 3859): OmcModel : OmcParser failed java.io.FileNotFoundException: /system/csc/omc.xml: open failed: ENOENT (No such file or directory)
I/Omc:OmcReceiver( 3859): /system/csc/omc.xml load failed - exit
D/TimaKeyStoreProvider( 3873): in addTimaSignatureService
D/TimaKeyStoreProvider( 3873): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 3885): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3885):  
D/ActivityThread( 3873): Added TimaKesytore provider
V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/SELinux ( 3885): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3885):  
I/SELinux ( 3885):  
I/SELinux ( 3885): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/Launcher.HomeView( 2782): onStop
E/SELinux ( 3885): [DEBUG] seapp_context_lookup: seinfoCategory = release
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
E/dalvikvm( 3885): >>>>> Normal User
E/dalvikvm( 3885): >>>>> com.android.mms [ userId:0 | appId:10049 ]
E/SELinux ( 3885): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 3885): in addTimaSignatureService
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(18)
,D/TimaKeyStoreProvider( 3885): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3885): Added TimaKesytore provider
,D/dalvikvm( 3873): GC_CONCURRENT freed 3002K, 32% free 9565K/13916K, paused 4ms+1ms, total 32ms
,D/dalvikvm( 3873): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/Launcher( 2782): onTrimMemory. Level: 20
,V/WebViewChromium( 3873): Binding Chromium to the background looper Looper (main, tid 1) {422a1268}
,I/chromium( 3873): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 3873): Initializing chromium process, renderers=0
,W/chromium( 3873): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 3873): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 3873): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 3873): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 3873): Mali API Version : 401
,I/Mali    ( 3873): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/dalvikvm( 3847): Could not find class 'com.google.trix.ritz.shared.messages.b', referenced from method bnz.<init>
W/dalvikvm( 3847): VFY: unable to resolve new-instance 7208 (Lcom/google/trix/ritz/shared/messages/b;) in Lbnz;
,D/dalvikvm( 3847): VFY: replacing opcode 0x22 at 0x03bc
E/dalvikvm( 3847): Could not find class 'com.google.trix.ritz.shared.render.g', referenced from method bnz.<init>
W/dalvikvm( 3847): VFY: unable to resolve new-instance 7339 (Lcom/google/trix/ritz/shared/render/g;) in Lbnz;
,D/dalvikvm( 3847): VFY: replacing opcode 0x22 at 0x03cb
,E/dalvikvm( 3847): Could not find class 'com.google.trix.ritz.shared.behavior.validation.a', referenced from method bnz.<init>
W/dalvikvm( 3847): VFY: unable to resolve new-instance 7168 (Lcom/google/trix/ritz/shared/behavior/validation/a;) in Lbnz;
,D/dalvikvm( 3847): VFY: replacing opcode 0x22 at 0x05d8
,D/dalvikvm( 3885): GC_CONCURRENT freed 2988K, 32% free 9581K/13920K, paused 10ms+1ms, total 69ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 53ms
E/dalvikvm( 3847): Could not find class 'com.google.trix.ritz.shared.mutation.O', referenced from method bnz.<init>
W/dalvikvm( 3847): VFY: unable to resolve new-instance 7301 (Lcom/google/trix/ritz/shared/mutation/O;) in Lbnz;
,D/dalvikvm( 3847): VFY: replacing opcode 0x22 at 0x07a9
,D/dalvikvm( 3847): DexOpt: unable to opt direct call 0xb146 at 0x3be in Lbnz;.<init>
W/dalvikvm( 3885): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/dalvikvm( 3847): DexOpt: unable to opt direct call 0xb292 at 0x3cd in Lbnz;.<init>
D/dalvikvm( 3847): DexOpt: unable to opt direct call 0xb108 at 0x5da in Lbnz;.<init>
,D/dalvikvm( 3847): DexOpt: unable to opt direct call 0xb23b at 0x7ab in Lbnz;.<init>
I/dalvikvm( 3873): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3873): VFY: unable to resolve virtual method 145: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3873): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3873): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3873): VFY: unable to resolve virtual method 140: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3873): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:3873,o:f
,W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3873): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3873): VFY: unable to resolve virtual method 198: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3873): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3873): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3873): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3873): VFY: unable to resolve virtual method 156: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3873): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3873): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3873): VFY: unable to resolve virtual method 161: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3873): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3873): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (7/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
,W/dalvikvm( 3847): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.a incorrectly overrides package-private method with same name in Lakm;
,W/dalvikvm( 3847): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.b incorrectly overrides package-private method with same name in Lakm;
,D/dalvikvm( 3659): GC_CONCURRENT freed 2216K, 29% free 10095K/14152K, paused 3ms+4ms, total 67ms
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:3873,o:f
,I/SurfaceFlinger( 1921): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 3873): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 3873): Enabling debug mode 0
,W/AwContents( 3873): nativeOnDraw failed; clearing to background color.
,D/Mms/MmsApp( 3885): [start]    onCreate()
,D/Mms/TelephonyPermission( 3885): start operation mode monitor
,W/ActivityManager( 2419): mDVFSHelper.release()
W/AwContents( 3873): nativeOnDraw failed; clearing to background color.
I/SamsungIME( 3041): getCurrentCandidateView
,D/Mms/TelephonyPermission( 3885): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 3885): isDefault true
,D/Mms/MmsApp( 3885): onCreate() com.android.mms
W/dalvikvm( 3847): VFY: unable to resolve instance field 20115
,D/dalvikvm( 3847): VFY: replacing opcode 0x54 at 0x001e
,I/dalvikvm( 3847): DexOpt: unable to optimize instance field ref 0x4e93 at 0x28 in LbvF;.getInstance
,D/Mms/MmsConfig( 3885): before partial update
,D/SamsungIME( 3041): Dismiss ExpandCandiate
,D/Mms/MmsConfig( 3885): Load Resize quality : 80
,D/Mms/MmsConfig( 3885):  enable multiwindow = false
,E/Mms/MessageUtils( 3885): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 3885): updateCountryIso : update country iso info 
,D/CountryDetector( 2419): The first listener is added
,I/SamsungIME( 3041): getDebugLevel  : 0x4f4c
,I/SurfaceFlinger( 1921): id=12 Removed iello (9/10)
,I/SurfaceFlinger( 1921): id=12 Removed iello (-2/10)
,D/TP/MmsSmsProvider( 2751): match 13:Elapsed time : 2.518 ms
,I/SamsungIME( 3041): getDebugLevel  : 0x4f4c
,D/Mms/Conversation( 3885): init()
,D/TP/MmsSmsProvider( 2751): match 12:Elapsed time : 2.344 ms
,I/SamsungIME( 3041): KeybaordView init() : load resources
,D/TP/MmsSmsDatabaseHelper( 2751): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off', secret_mode INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 2751): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 2751): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 2751): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,seen INTEGER DEFAULT 0,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 2751): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
,D/TP/MmsSmsProvider( 2751): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 2751): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/skia    ( 3041): ---- fAsset->read(4091) returned 0
,D/TP/MmsSmsProvider( 2751): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 2751): need read changed broadcast:false
,I/chromium( 3873): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 3041): getCurrentKeyboard
,I/SamsungIME( 3041): getTextKeyboard
,E/AndroidProtocolHandler( 3873): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/SamsungIME( 3041): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActiveOrDefaultContextProvider( 3847): Missing scope.enter somewhere. Returning default context
,D/JsMessageQueue( 3873): Set native->JS mode to OnlineEventsBridgeMode
,W/ActiveOrDefaultContextProvider( 3847): Missing scope.enter somewhere. Returning default context
,D/dalvikvm( 3041): GC_CONCURRENT freed 1033K, 17% free 11999K/14384K, paused 9ms+3ms, total 69ms
,I/Mms/ReservationManager( 3885): ReservationManager()
,I/Mms/ReservationManager( 3885): resetAfterConnected()
,D/TP/MmsSmsProvider( 2751): match 7:Elapsed time : 7.454 ms
,I/Mms/ReservationManager( 3885): getReservedSendMessageCount(): retMessageCount=0
,I/chromium( 3873): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/Mms/MmsApp( 3885): [end]    onCreate()
,D/Mms/SmsReceiver( 3885): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
,I/chromium( 3873): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/libGLESv2( 3873): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 3873): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 3847): GC_CONCURRENT freed 2128K, 25% free 10536K/13976K, paused 3ms+2ms, total 82ms
,I/WifiApBroadcastReceiver( 2828): onReceive: action android.intent.action.SIM_STATE_CHANGED
,D/Mms/DownloadManager( 3885): Service state changed: Bundle[mParcelledData.dataSize=740]
D/Mms/DownloadManager( 3885): roaming ------> false
,D/Mms/DownloadManager( 3885): mAutoDownload ------> true
,I/BootupListener( 2751): mPendingNetworkManualSelection : false
,W/GAV2    ( 3847): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 3947): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3947):  
,D/Mms/TelephonyPermission( 3885): isDefault true
,D/Mms/SmsReceiverService( 3885): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
E/libGLESv2( 3873): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 3873): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/Mms/SmsReceiverService( 3885): handleSIMStatus()
,D/Mms/SmsReceiverService( 3885): handleSIMStatus(): SIM_STATUS = NOT_READY
,I/SELinux ( 3947): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3947):  
I/SELinux ( 3947):  
,I/SELinux ( 3947): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/Documents( 3794): Update found 7 roots in 2113ms
,E/SELinux ( 3947): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3947): >>>>> Normal User
,E/dalvikvm( 3947): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3947): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3947): in addTimaSignatureService
,D/Documents( 3794): Loading roots for com.android.externalstorage.documents
,D/TimaKeyStoreProvider( 3947): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3947): Added TimaKesytore provider
,D/dalvikvm( 3947): GC_CONCURRENT freed 2991K, 32% free 9577K/13916K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 3947): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/StatusChecker( 3947): onReceive : android.intent.action.SIM_STATE_CHANGED
,D/StatusChecker( 3947): onReceive : preference initializing
,I/SELinux ( 3964): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3964):  
,I/SELinux ( 3964): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3964):  
I/SELinux ( 3964):  
,I/SELinux ( 3964): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3964): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3964): >>>>> Normal User
,E/dalvikvm( 3964): >>>>> com.sec.android.app.sbrowser [ userId:0 | appId:10139 ]
,E/SELinux ( 3964): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 2419): GC_EXPLICIT freed 2896K, 20% free 22587K/28132K, paused 7ms+14ms, total 178ms
,D/TimaKeyStoreProvider( 3964): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3964): Cannot add TimaSignature Service, License check Failed
D/Documents( 3794): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3794): Used cached roots for com.android.providers.media.documents
D/Documents( 3794): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3794): Update found 7 roots in 225ms
,D/ActivityThread( 3964): Added TimaKesytore provider
,D/dalvikvm( 3964): GC_CONCURRENT freed 2999K, 32% free 9570K/13920K, paused 2ms+3ms, total 20ms
,D/dalvikvm( 3964): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/sbChromeBrowserProvider( 3964): onCreate called.
,E/OperatorBookmarksSIMReceiver( 3964): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,I/SELinux ( 3978): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3978):  
,I/SELinux ( 3978): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3978):  
I/SELinux ( 3978):  
I/SELinux ( 3978): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3978): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3978): >>>>> Normal User
E/dalvikvm( 3978): >>>>> com.sec.android.app.SecSetupWizard [ userId:0 | appId:1000 ]
E/SELinux ( 3978): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/SamsungIME( 3041): [SwiftkeyWrapper] currentLangauge : 1701729619
D/TimaKeyStoreProvider( 3978): in addTimaSignatureService
D/TimaKeyStoreProvider( 3978): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3978): Added TimaKesytore provider
D/dalvikvm( 3978): GC_CONCURRENT freed 2999K, 32% free 9566K/13916K, paused 4ms+2ms, total 23ms
D/dalvikvm( 3978): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/SELinux ( 3991): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3991):  
D/SensorService( 2419):   0.3 0.0 9.9
I/SELinux ( 3991): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 3991):  
I/SELinux ( 3991):  
I/SELinux ( 3991): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3991): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3991): >>>>> Normal User
E/dalvikvm( 3991): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
E/SELinux ( 3991): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3991): in addTimaSignatureService
D/TimaKeyStoreProvider( 3991): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3991): Added TimaKesytore provider
D/dalvikvm( 3991): GC_CONCURRENT freed 3003K, 32% free 9565K/13920K, paused 3ms+2ms, total 25ms
D/dalvikvm( 3991): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/SELinux ( 4003): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4003):  
I/SELinux ( 4003): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4003):  
I/SELinux ( 4003):  
I/SELinux ( 4003): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4003): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4003): >>>>> Normal User
E/dalvikvm( 4003): >>>>> com.sec.tcpdumpservice [ userId:0 | appId:1000 ]
E/SELinux ( 4003): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4003): in addTimaSignatureService
D/TimaKeyStoreProvider( 4003): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4003): Added TimaKesytore provider
D/dalvikvm( 4003): GC_CONCURRENT freed 3001K, 32% free 9572K/13920K, paused 3ms+2ms, total 21ms
D/dalvikvm( 4003): WAIT_FOR_CONCURRENT_GC blocked 9ms
I/SELinux ( 4015): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4015):  
I/ActivityManager( 2419): Killing 2696:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10896K, paused 2ms+3ms, total 33ms
I/SELinux ( 4015): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4015):  
I/SELinux ( 4015):  
I/SELinux ( 4015): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4015): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 4015): >>>>> Normal User
E/dalvikvm( 4015): >>>>> com.android.contacts [ userId:0 | appId:10020 ]
E/SELinux ( 4015): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 4015): in addTimaSignatureService
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 26ms
D/TimaKeyStoreProvider( 4015): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4015): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 25ms
E/SMD     ( 1939): InvokeOemRequestHookRaw usbstatus true is success
E/SMD     ( 1939): [*] dr_smd_dsr_event_hdlr event received  is received 
E/SMD     ( 1939): data pin is DSR 
E/SMD     ( 1939): DSR pinstatus is ON 
D/dalvikvm( 4015): GC_CONCURRENT freed 3006K, 32% free 9563K/13920K, paused 2ms+1ms, total 19ms
D/dalvikvm( 4015): WAIT_FOR_CONCURRENT_GC blocked 11ms
V/VibratorService( 2419): hasVibrator - useVibetonz: false
D/Mms/UIEventReceiver( 3885): ui event
I/SELinux ( 4030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4030):  
I/SELinux ( 4030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4030):  
I/SELinux ( 4030):  
I/SELinux ( 4030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4030): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4030): >>>>> Normal User
E/dalvikvm( 4030): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10154 ]
E/SELinux ( 4030): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4030): in addTimaSignatureService
D/TimaKeyStoreProvider( 4030): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4030): Added TimaKesytore provider
D/dalvikvm( 4030): GC_FOR_ALLOC freed 3032K, 32% free 9542K/13920K, paused 17ms, total 17ms
V/TaskCloserActivity( 4030): TaskCloserActivity enter()
D/dalvikvm( 4030): GC_CONCURRENT freed 193K, 16% free 9568K/11376K, paused 2ms+1ms, total 18ms
I/BootupListener( 2751): mPendingNetworkManualSelection : false
D/StatusChecker( 3947): onReceive : android.intent.action.SERVICE_STATE
D/StatusChecker( 3947): Service state changed : 3
V/SipBroadcastReceiver( 2751): SipBroadcastReceiver onReceive
I/WifiService( 2419): android.intent.action.BOOT_COMPLETED
I/WifiService( 2419): setWifiEnabled: true pid=2419, uid=1000
I/WifiService( 2419): WifiService starting up with Wi-Fi enabled
E/WifiHW  ( 2419): ##################### set firmware type 0 #####################
I/WifiHW  ( 1914): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1914): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1914): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1914): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1914): Softap fwReload - Ok,
D/CommandListener( 1914): Setting iface cfg
,D/CommandListener( 1914): Trying to bring down wlan0
,D/WifiHW  ( 2419): Skip the update_ctrl_interface,
,D/WifiHW  ( 2419): Skip the update_ctrl_interface
,E/WifiHW  ( 2419): supplicant_name : p2p_supplicant
,I/wpa_supplicant( 4046): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
I/wpa_supplicant( 4046): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4046): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4046): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4046): getIMSI cannot open file
,E/wpa_supplicant( 4046): Interworking config: - SIM READ ERROR
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BOOT_COMPLETED
,V/OtaStartupReceiver( 2751): onReceive: intent action=android.intent.action.BOOT_COMPLETED  mOtaspMode=-1
,D/OtaStartupReceiver( 2751): OTASP not supported, nothing to do.
,D/PopupuiReceiver( 3141): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/PopupuiReceiver( 3141): Batterycover is on
,D/PopupuiReceiver( 3141): ril. condition
,D/WifiMonitor( 2419): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/PopupuiReceiver( 3141): FINISH condition
W/ContextImpl( 3141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:288 android.app.ActivityThread.handleReceiver:2698 
W/ContextImpl( 3141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:288 
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.popupuireceiver
,I/wpa_supplicant( 4046): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4046): getIMSI cannot open file
E/wpa_supplicant( 4046): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4046): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4046): rfkill: Cannot open RFKILL control device
,W/ActivityManager( 2419): mDVFSHelper.acquire()
D/PermissionCache( 1921): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (262 us)
,I/dalvikvm-heap( 2419): Grow heap (frag case) to 24.096MB for 380496-byte allocation
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager( 2419): mDVFSHelper.release()
,I/SELinux ( 4053): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4053):  
W/ActivityManager( 2419): mDVFSHelper.acquire()
,D/PopupuiReceiver( 3141): on BatteryCover Delete to FirstValue
I/SELinux ( 4053): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4053):  
I/SELinux ( 4053):  
,I/SELinux ( 4053): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4053): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4053): >>>>> Normal User
,E/dalvikvm( 4053): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
,E/SELinux ( 4053): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PopupuiReceiver( 3141): on BatteryCover  : firstvalue
,D/StatusBarManagerService( 2419): semi p:3141,o:f
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/TimaKeyStoreProvider( 4053): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4053): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4053): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=14 createSurf (1x1),2 flag=404, CatteryCove
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/PopupuiReceiver( 3141): showPopupBatteryCover()+
D/PopupuiReceiver( 3141): mini popup layout in 
,D/dalvikvm( 4053): GC_CONCURRENT freed 2994K, 32% free 9565K/13912K, paused 5ms+1ms, total 24ms
,D/dalvikvm( 4053): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/BatteryService( 2419): bootCompleted
,D/BatteryService( 2419): Dormant OnOff Settings = false
,D/BatteryService( 2419): Dormant Disable LED Settings = false
,D/BatteryService( 2419): Dormant Always Settings = true
,D/BatteryService( 2419): Dormant time Settings = 21:0 ~ 6:0
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/IInputConnectionWrapper( 3873): showStatusIcon on inactive InputConnection
,I/LteTpBooster( 2419): No model
,I/SurfaceFlinger( 1921): id=15 createSurf (1x1),1 flag=4, CatteryCove
,I/Mms/MmsApp( 3885):  start initViewCache mms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 a.G.H:-1 a.B.a:-1 a.B.a:-1 com.android.server.ssrm.L.e:-1 
,D/WindowManager( 2419): ACTION_BOOT_COMPLETED isKidsLauncherEnabled = false
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=android
V/AlarmManager( 2419): mGmsLocationBundling: false
,D/BluetoothManagerService( 2419): foregroundUser: 0
D/RCPManagerService( 2419): ACTION_BOOT_COMPLETED
,E/RCPManagerService( 2419):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,E/BluetoothManagerService( 2419): Package is exist.
,D/RCPManagerService( 2419): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/PersonaManagerService( 2419): returning null in  getPersonasForUser
,I/SELinux ( 4069): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4069):  
,D/MountService( 2419): received ACTION_BOOT_COMPLETED
,I/SELinux ( 4069): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4069):  
I/SELinux ( 4069):  
,I/SELinux ( 4069): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4069): >>>>> Normal User
,E/dalvikvm( 4069): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
,E/SELinux ( 4069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4069): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4069): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4069): Added TimaKesytore provider
,D/EnterpriseDeviceManagerService( 2419): android.intent.action.BOOT_COMPLETED
,V/ApplicationPolicy( 2419): boot completed - refreshWidgetStatus
,D/EnterpriseDeviceManagerService( 2419): runAdminUpdate
D/readPropertyValue( 2419): File Not Found : /data/system/selfUpdateAdmin.conf
,D/EnterpriseDeviceManagerService( 2419): nothing to selfUpdate
,V/ApplicationPolicy( 2419): refresh widget status for user 0
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname pl.k2.droidoaudioteka
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname pl.k2.droidoaudioteka
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.GeoLookout
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widget.samsungapps
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.kidsplat.installer
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.n7mobile.muzodajnia
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.n7mobile.muzodajnia
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.naviexpert.NaviExpert_Plus
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname flipboard.app
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.android.vending
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.samsung.helphub
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,I/SQLiteSecureOpenHelper( 2419): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2419): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2419): Open ssrm_secure.db in secure mode
,W/PhoneRestrictionPolicy( 2419): Message received - msg { when=-3ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,W/PhoneRestrictionPolicy( 2419):  >>>> deliveryBlockedMsgs
,D/KnoxMUMContainerPolicy( 2419): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,W/PhoneRestrictionPolicy( 2419): cvList size 0
,W/PhoneRestrictionPolicy( 2419):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 2419): cvList size 0
,I/KnoxMUMContainerPolicy( 2419): MSG_REMOVE_ORPHANED_CONTAINERS received
D/dalvikvm( 4069): GC_CONCURRENT freed 2998K, 32% free 9569K/13920K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 4069): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/Tethering( 2419): Boot complete.
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2578 (0x0)
,E/BluetoothHeadset( 2419): BTStateChangeCB is registed
,D/BtSettings.ProfileConfig( 4069): Adding GattService
D/BtSettings.ProfileConfig( 4069): Adding HeadsetService
D/BtSettings.ProfileConfig( 4069): Adding A2dpService
,D/BtSettings.ProfileConfig( 4069): Adding HidService
D/BtSettings.ProfileConfig( 4069): Adding HealthService
D/BtSettings.ProfileConfig( 4069): Adding PanService
D/BtSettings.ProfileConfig( 4069): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 4069): Adding SapService
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 android.media.AudioService.getBluetoothHeadset:3361 
E/BluetoothHeadset( 2419): BluetoothHeadset service is binded
V/MediaPlayer( 2419): decode(368, 0, 6586)
,V/MediaPlayerService( 1925): decode(26, 0, 6586)
,W/ActivityManager( 2419): mDVFSHelper.release()
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 6586)
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 android.media.AudioService$AudioServiceBroadcastReceiver.onReceive:6141 
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/BluetoothAdapterService( 4069): REFCOUNT: CREATED. INSTANCE_COUNT1
,I/AudioHardwareTinyALSA( 1925): setParameters(ril_connected=1)
I/AudioHardwareTinyALSA( 1925): ### CLK state - PcmClk : 0 / ModemPath : 0
,I/AudioHardwareTinyALSA( 1925): connect RILD ok
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/WiredAccessoryManager( 2419): init()
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
D/UsbHostNotification( 2419): boot completed
,D/UsbStorageNotification( 2419): boot completed
I/SQLiteSecureOpenHelper( 2419): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 2419): ...getDatabaseLocked(b,b,pwd)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
D/UsbDeviceManager( 2419): boot completed
D/UsbDeviceManager( 2419): handleMessage -> MSG_BOOT_COMPLETED
D/UsbDeviceManager( 2419): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 2419): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9328, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x1e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 2419): decode(374, 0, 5018)
,V/MediaPlayerService( 1925): decode(26, 0, 5018)
,D/MotionRecognitionService( 2419):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 5018)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/BluetoothAdapterState( 4069): make
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/SmartFaceService( 2419): onReceive: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.as.cO:-1 com.android.server.ssrm.as.<init>:-1 com.android.server.ssrm.L.onBootCompleted:-1 com.android.server.ssrm.L.e:-1 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/bluedroid( 4069): init
D/SmartFaceIndicator( 2419): no icon
E/SmartFaceService( 2419): mActiveServiceType: 0
E/SmartFaceService( 2419): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 2419): updateClientsDone. def. do nothing.
E/SmartFaceService( 2419): Service Type to Worker: 0
E/SmartFaceService( 2419): Last Active clients:0 Current Active clients: 0
,E/SmartFaceService( 2419): Last Smart Pause clients: 0 Current Smart Pause clients: 0
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/SSRMv2:SIOP( 2419): notifyLimitBrightness() : brightness : -1isBootCompleted = true
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 com.android.server.ssrm.L.a:-1 com.android.server.ssrm.L.onBootCompleted:-1 com.android.server.ssrm.L.e:-1 com.android.server.ssrm.av.handleMessage:-1 
,I/BluetoothAdapterState( 4069): Entering OffState
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
,V/SSRMv2:SsrmUEventObserver( 2419): Startng SsrmUEventObserver
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/bte_conf( 4069): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/FactoryTest( 2419): Not factory mode
D/FactoryTest( 2419): Not factory mode. isFactoryMode() returend false
I/AudioPlayer( 1925): First fillBuffer call!!
I/bluedroid( 4069): get_profile_interface socket
D/BluetoothAdapterService( 4069):  checkAddrForIOP: Loading from conf
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1350, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/GKI_LINUX( 4069): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x1f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
E/BluetoothServiceJni( 4069): populateRssiValuesNative
I/bluedroid( 4069): getModelRssiValues
E/BluetoothServiceJni( 4069): model_rssi_values_callback: low = -75, mid = -65, high = 127
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 2419): decode(376, 0, 9847)
V/MediaPlayerService( 1925): decode(26, 0, 9847)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
D/PowerManagerService( 2419): [api] BootCompletedReceiver: onReceive
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 9847)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/PersonaManagerService( 2419): ACTION_BOOT_COMPLETED
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
D/PowerManagerService( 2419): [api] Check if boot animation finished...
I/PowerManagerService( 2419): Boot animation finished.
D/PowerManagerService( 2419): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2419): [input device light] updateInputDeviceLightStateLocked: BootCompleted!
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/PersonaManagerServiceHandler( 2419):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
E/PersonaManagerService( 2419): returning null in  getPersonasForUser
D/StorageNotification( 2578): boot completed
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b1a48, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x20, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 2419): decode(377, 0, 7868)
,V/MediaPlayerService( 1925): decode(26, 0, 7868)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 7868)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
D/SSRMv2:SIOP( 2419): SIOP:: AP = 360, Delta = 360
D/SSRMv2:SIOP:Limiter( 2419): limitCPUFreq:: freq = -1
D/SSRMv2:SIOP:Limiter( 2419): broadcastSiopLevelIntent:: currentSiopLevel = 0
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/SSRMv2:SIOP:Limiter( 2419): limitRecording:: recordingStop = false
D/SSRMv2:SIOP:Limiter( 2419): limitSmartBonding:: limit = false
D/SSRMv2:SIOP:Limiter( 2419): limitFlashLed:: bLimit = false
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/ContentApp( 2721):  LEVEL : 0
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
D/StatusBar-DoNotDistrub( 2578): Received intent with android.intent.action.BOOT_COMPLETED action
D/StatusBar-DoNotDistrub( 2578): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
,I/AudioService( 2419): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2578): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2578): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=com.android.systemui
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
D/STATUSBAR-NotificationService( 2419): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x21, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/EmergencyMode( 2746): [EmergencyModeReceiver] onReceive : android.intent.action.BOOT_COMPLETED
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 2419): decode(382, 0, 6585)
,V/MediaPlayerService( 1925): decode(26, 0, 6585)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 6585)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/EmergencyMode( 2746): [EmergencyModeReceiver] No Recovery State, kill my self.
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
,D/PhoneApp( 2751): ACTION_BOOT_COMPLETED
D/UsbDeviceManager( 2419): isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
,D/UsbManager( 2419):  :::: isUsb30Enabled :: return = false from pid = 2419
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/Process ( 2746): Sending signal. PID: 2746 SIG: 9
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/bluedroid( 4069): config_hci_snoop_log
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
I/SELinux ( 4121): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4121):  
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
D/BluetoothManagerService( 2419): Broadcasting onBluetoothServiceUp() to 6 receivers.
,V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf568, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
I/ServiceManager( 1909): service 'emergency_service' died
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf568, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x22, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 2419): decode(388, 0, 4713)
,V/MediaPlayerService( 1925): decode(26, 0, 4713)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 0, 4713)
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
I/SELinux ( 4121): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4121):  
I/SELinux ( 4121):  
,I/SELinux ( 4121): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
,E/SELinux ( 4121): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
E/dalvikvm( 4121): >>>>> Normal User
E/dalvikvm( 4121): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
,I/ActivityManager( 2419): Process com.sec.android.emergencymode.service (pid 2746) (adj 0) has died.
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
E/SELinux ( 4121): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x23, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
D/BluetoothAdapterState( 4069): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterSta,te( 4069): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 4069): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4069): updateAdapterState state is 11
D/BluetoothAdapterService( 4069): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 4069): Autoconnection is available 
D/BluetoothAdapterService( 4069): updateAdapterState prevState = 10newState = 11
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
D/BluetoothSecureManager( 4069): getInstant: null
D/BluetoothSecureManager( 4069): calling getMethod for getService
D/BluetoothSecureManager( 4069): calling getService
D/BluetoothSecureManager( 4069): getService return binder: android.os.BinderProxy@422d0078
D/BluetoothSecureManagerService( 2419): isSecureModeEnabled
D/BluetoothSecureManagerService( 2419): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/TimaKeyStoreProvider( 4121): in addTimaSignatureService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/TimaKeyStoreProvider( 4121): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4121): Added TimaKesytore provider
W/InputMethodManagerService( 2419): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2419): [BT Setting State] State =11
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/SamsungIME( 3041): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 4069): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
D/BluetoothBondStateMachine( 4069): make
I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(7)
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 4069): StableState(): Entering Off State
,I/BtGatt.JNI( 4069): classInitNative(L703): classInitNative: Success!
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.hfp.HeadsetService
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/SELinux ( 4140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4140):  
D/BtGatt.GattService( 4069): BluetoothAdapter state is = 11
D/BtGatt.DebugUtils( 4069): handleDebugAction() action=null
D/BtGatt.GattService( 4069): Received start request. Starting profile...
D/BtGatt.GattService( 4069): start()
E/Tethering( 2419): No numeric data
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/bluedroid( 4069): get_profile_interface gatt
D/Tethering( 2419): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime( 2419): forceRefresh() from cache miss
,I/wpa_supplicant( 4046): wlan0: Setting scan request: 0 sec 100000 usec
,D/NtpTrustedTime( 2419): forceRefresh Fail.
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.hid.HidService
I/SELinux ( 4140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4140):  
I/SELinux ( 4140):  
,I/SELinux ( 4140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4140): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 4140): >>>>> Normal User
,E/dalvikvm( 4140): >>>>> com.sec.android.widgetapp.digitalclock [ userId:0 | appId:10090 ]
,E/SELinux ( 4140): [DEBUG] seapp_context_lookup: seinfoCategory = shared
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.hdp.HealthService
V/NetworkStats( 2419): performPollLocked() took 21ms
,W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.pan.PanService
I/wpa_supplicant( 4046): >>>>> Not GET KEY, IV <<<<<
,D/NtpTrustedTime( 2419): forceRefresh() from cache miss
,I/wpa_supplicant( 4046): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4046): rfkill: Cannot open RFKILL control device
,D/NtpTrustedTime( 2419): forceRefresh Fail.
D/Tethering( 2419): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2419): interfaceStatusChanged p2p0, true
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4069): Not skipping com.android.bluetooth.map.BluetoothMapService
D/Tethering( 2419): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2419): interfaceStatusChanged p2p0, true
,D/TimaKeyStoreProvider( 4140): in addTimaSignatureService
W/BluetoothAdapterService( 4069): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 4069): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 4069): Not skipping com.broadcom.bt.service.sap.SapService
,D/TimaKeyStoreProvider( 4140): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4140): Added TimaKesytore provider
,I/BluetoothAdapterState( 4069): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/Mms/ComposeMessageFragment( 3885): fillCache, easy = false
,I/wpa_supplicant( 4046): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4046): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2419): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s272ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s273ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s273ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s273ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s273ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-1s274ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative( 2419): callSECApiString - ID [21]
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/wpa_supplicant( 4046): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4046): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/WifiNative( 2419): callSECApiInt - ID [65]
,D/dalvikvm( 4121): GC_CONCURRENT freed 2996K, 32% free 9568K/13916K, paused 13ms+2ms, total 64ms
,D/dalvikvm( 4121): WAIT_FOR_CONCURRENT_GC blocked 54ms
,D/HeadsetService( 4069): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 4069): classInitNative: succeeds
,D/HeadsetStateMachine( 4069): Version 1.5
,D/HeadsetStateMachine( 4069): make
,E/HeadsetStateMachine( 4069): # of Max HF connection is 2
,D/dalvikvm( 4140): GC_CONCURRENT freed 3000K, 32% free 9573K/13920K, paused 7ms+9ms, total 54ms
,D/dalvikvm( 4140): WAIT_FOR_CONCURRENT_GC blocked 47ms
,E/WifiConfigStore( 2419): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/bluedroid( 4069): get_profile_interface handsfree
,D/BluetoothAtMessage( 4069): createCMTIContentObservers
,D/HeadsetStateMachine( 4069): Enter Disconnected: -2
,E/HeadsetStateMachine( 4069): set to mRemoteBrsf = 0
,D/WifiNative( 2419): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4046): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4046): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4046): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4046): First Scan Start
,I/wpa_supplicant( 4046): Scan requested (ret=0) - scan timeout 30 seconds
,D/HeadsetStateMachine( 4069): map size, before remove : 0
,D/BluetoothA2dp( 2419): Proxy object connected
D/A2dpService( 4069): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 4069): classInitNative: succeeds
,D/A2dpStateMachine( 4069): make
,D/HeadsetStateMachine( 4069): map size, after remove: 0
D/HeadsetStateMachine( 4069): mNextConnectingDevice : null
,E/WifiStateMachine( 2419): Set the Nv default ccode
,I/bluedroid( 4069): get_profile_interface a2dp
,I/GKI_LINUX( 4069): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 4069): classInitNative: succeeds
,I/bluedroid( 4069): get_profile_interface avrcp
,D/A2dpStateMachine( 4069): Enter Disconnected: -2
,D/MediaFocusControl( 2419): >>> registerRemoteControlDisplay
,D/WifiStateMachine( 2419): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2419): Blacklist file delete
D/WifiP2pService( 2419): P2pDisabledState{ what=131203 }
,I/BluetoothHidServiceJni( 4069): classInitNative: succeeds
,D/HidService( 4069): Received start request. Starting profile...
,I/bluedroid( 4069): get_profile_interface hidhost
,D/HidService( 4069): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 4069): classInitNative: succeeds
D/CommandListener( 1914): Setting iface cfg
,D/CommandListener( 1914): Trying to bring up p2p0
,D/HealthService( 4069): Received start request. Starting profile...
,D/WifiMonitor( 2419): startMonitoring(p2p0) with mConnected = true
,I/bluedroid( 4069): get_profile_interface health
,I/BluetoothPanServiceJni( 4069): classInitNative(L105): succeeds
D/WifiP2pService( 2419): P2pEnablingState
I/ActivityManager( 2419): Killing 2813:com.sec.android.provider.emergencymode/u0a100 (adj 15): empty #43
,D/WifiP2pService( 2419): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 2419): P2p socket connection successful
,D/WifiP2pService( 2419): P2pEnabledState
,I/RecoverySystem( 2419): !@RecoverySystem handleAftermath
,I/RecoverySystem( 2419): No recovery log file
D/PanService( 4069): Received start request. Starting profile...
D/BluetoothPanServiceJni( 4069): initializeNative(L110): pan
,I/bluedroid( 4069): get_profile_interface pan
,I/DrmEventReceiver( 2419): DrmEventReceiver : onReceive
,I/DrmEventReceiver( 2419): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,D/WifiP2pService( 2419): sending p2p connection changed broadcast: IDLE
I/DrmEventReceiver( 2419): DrmEventReceiver : beginStartingService
I/System.out( 2419): start Service
,D/BluetoothTethering( 2419): got CMD_CHANNEL_HALF_CONNECTED
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
E/WifiStateMachine( 2419): HS20_DISABLED_COMPLETEnormal
,D/BluetoothMapService( 4069): Received start request. Starting profile...
D/WifiDisplayController( 2419): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2419): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2419): disconnect
D/WifiDisplayController( 2419): updateConnection
D/WifiDisplayController( 2419): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2419): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 2419): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayController( 2419): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/BluetoothMapMasInstance( 4069): mAccount : null
D/BluetoothPan( 2419): BluetoothPAN Proxy object connected
E/WifiStateMachine( 2419): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
I/BluetoothSAPServiceJni( 4069): classInitNative(L204): succeeds
,I/wpa_supplicant( 4046): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/SapService( 4069): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 4069): initializeNative(L209): sap
,I/bluedroid( 4069): get_profile_interface sap
D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 3024
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 3024
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0xbd0
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0xbd0
,D/HeadsetStateMachine( 4069): Try to query the phonestate on bind
,I/wpa_supplicant( 4046): reset timer : RESET_TIMER 1
I/wpa_supplicant( 4046): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 4046): Skip scan - already scanning
,D/HeadsetStateMachine( 4069): Proxy object connected
D/BluetoothPhoneService( 2751): handleMessage: 4
,V/BluetoothPhoneService( 2751): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetPhoneState( 4069): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 4069): Disconnected process message: 11
D/HeadsetPhoneState( 4069): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 4069): Signal level : previous=0 curr=0
W/BluetoothHeadset( 2751): Proxy not attached to service
D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
V/HeadsetService( 4069): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/HeadsetStateMachine( 4069): Disconnected process message: 20
D/BluetoothAdapterService( 4069): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/HeadsetStateMachine( 4069): Disconnected process message: 10
,D/HeadsetPhoneState( 4069): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 4069): Disconnected process message: 11
,D/WifiP2pService( 2419): DeviceAddress: 02:e0:6d
D/BluetoothAdapterState( 4069): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 4069): enable
,I/bt_hci_bdroid( 4069): init
,D/WifiDisplayController( 2419): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2419):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2419):  primary type: 10-0050F204-5
D/WifiDisplayController( 2419):  secondary type: null
D/WifiDisplayController( 2419):  wps: 0
D/WifiDisplayController( 2419):  grpcapab: 0
D/WifiDisplayController( 2419):  devcapab: 0
D/WifiDisplayController( 2419):  status: 3
D/WifiDisplayController( 2419):  wfdInfo: null
D/WifiDisplayController( 2419):  groupownerAddress: null
D/WifiDisplayController( 2419):  GOdeviceName: null
D/WifiDisplayController( 2419):  interfaceAddress: 
D/WifiDisplayController( 2419):  SConnectInfo : null
I/bt_vendor( 4069): init
I/bt_vnd_conf( 4069): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 4069): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt_hci_bdroid( 4069): bt_hc_worker_thread started
,I/DrmEventService( 2419): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 2419): TimaServiceEventReceiver : onReceive
W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiP2pService( 2419): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 2419): InactiveState
I/ANDROID_DRM_FRWORKS_DrmManager( 1924): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/BootCompletedReceiver( 2419): onReceive
D/Reset_Reason( 2419): resetString = NPON
,E/CscReceiver( 2751): onReceive android.intent.action.BOOT_COMPLETED
D/SSRMv2:TSP:AirViewOnOff( 2419): SettingsAirViewInfo:: 000000000
,D/CscUpdateService( 2751): onStart
E/CscUpdateService( 2751): costomer file is exists : it has been preconfiged.
,I/CscUpdateService( 2751): set_CSC_version
,E/CscParser( 2751): update(): xml file exist
,I/BootReceiver( 2419): Copying /proc/last_kmsg to DropBox (SYSTEM_LAST_KMSG)
,I/SELinux ( 4178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4178):  
,D/dalvikvm( 3071): GC_CONCURRENT freed 2158K, 26% free 10418K/13924K, paused 4ms+2ms, total 60ms
,I/GKI_LINUX( 4069): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt_userial_vendor( 4069): userial vendor open: opening /dev/ttySAC0
,I/bt_userial_vendor( 4069): userial_vendor_open():UART is setup
I/bt_userial_vendor( 4069): device fd = 76 open
,E/bt_hwcfg( 4069): Start CFG HW, HCI reset
,I/SELinux ( 4178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4178):  
I/SELinux ( 4178):  
,I/SELinux ( 4178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4178): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4178): >>>>> Normal User
,E/dalvikvm( 4178): >>>>> com.google.android.configupdater [ userId:0 | appId:10003 ]
,E/bt_hwcfg( 4069): Read Local Name after HCI reset
,E/SELinux ( 4178): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4178): in addTimaSignatureService
,D/bt_hwcfg( 4069): Chipset BCM4334B0
D/bt_hwcfg( 4069): Target name = [BCM4334B0]
,I/bt_hwcfg( 4069): module conf file not found; use default file extension .hcd
D/bt_hwcfg( 4069): Target name = [BCM4334]
I/bt_hwcfg( 4069): module conf file not found; use default file extension .hcd
I/bt_hwcfg( 4069): Found patchfile: BT_FW_VER_BCM4334B0_002.001.013.1792.1803_K_Mini.hcd
,I/bt_hwcfg( 4069): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 4069): bt vendor lib: set UART baud 3000000
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 2830K, 18% free 23879K/29088K, paused 157ms, total 157ms
,I/wpa_supplicant( 4046): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/TimaKeyStoreProvider( 4178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4178): Added TimaKesytore provider
,I/CscUtil ( 2751): isWifiOnly = false
,I/System.out( 2751): HandDataNode = null
,I/CscUpdateService( 2751): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 2751): This is normal boot : CSC not updated
,E/CscParser( 2751): update(): xml file exist
,I/SELinux ( 4198): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4198):  
,I/BootReceiver( 2419): Copying audit failures to DropBox
,I/CscUpdateService( 2751): same CSC Version
,D/CscUtil ( 2751): Set Build Fingerprint to samsung/kminiltexx/kminilte:4.4.2/KOT49H/G800FXXU1ANG7:user/release-keys
,D/CscGPS  ( 2751): CSCGPS.updateParameters
,D/CscGPS  ( 2751): supl host : null
D/CscGPS  ( 2751): SUPL Host is null or invalid
D/CscGPS  ( 2751): supl_ver : null
,D/CscGPS  ( 2751): SUPL Ver is null or invalid
D/CscGPS  ( 2751): supl port : null
D/CscGPS  ( 2751): SUPL PORT is null or invalid
,D/CscGPS  ( 2751): CSC don't have any AGPS value.
,D/AbsListView( 3885): Get MotionRecognitionManager
,I/wpa_supplicant( 4046): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 4046): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4046): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
I/SELinux ( 4198): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4198):  
I/SELinux ( 4198):  
,I/SELinux ( 4198): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4198): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4198): >>>>> Normal User
,E/dalvikvm( 4198): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
D/PackageManager( 2419): [MSG] MCS_UNBIND
I/PackageManager( 2419): calling disconnectService()
D/PackageManager( 2419): Trying to unbind to DefaultContainerService
,E/SELinux ( 4198): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/ActivityManager( 2419): Killing 2900:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,D/MotionRecognitionService( 2419):  ssp status : false
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 4198): in addTimaSignatureService
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 4046): Associated with C0.AA.48
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 4198): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4198): Added TimaKesytore provider
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4046): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4046): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4046): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/dalvikvm( 2419): GC_CONCURRENT freed 240K, 18% free 23912K/29088K, paused 7ms+23ms, total 232ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 165ms
,I/dalvikvm-heap( 2419): Grow heap (frag case) to 24.774MB for 35634-byte allocation
,I/wpa_supplicant( 4046): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/dalvikvm( 4178): GC_CONCURRENT freed 3003K, 32% free 9566K/13920K, paused 14ms+2ms, total 44ms
,D/dalvikvm( 4178): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/dalvikvm( 3885): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 3885): VFY: unable to resolve static method 1401: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
,D/dalvikvm( 3885): VFY: replacing opcode 0x71 at 0x03bb
,I/dalvikvm( 3885): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 3885): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 3885): VFY: replacing opcode 0x74 at 0x0759
I/dalvikvm( 3885): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 3885): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 3885): VFY: replacing opcode 0x74 at 0x07e8
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/dalvikvm( 2419): GC_FOR_ALLOC freed 116K, 19% free 23834K/29124K, paused 144ms, total 145ms
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,I/BootReceiver( 2419): Copied 0 worth of audits to DropBox
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/bt_hwcfg( 4069): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 4069): Settlement delay -- 100 ms
,V/WebViewChromium( 3885): Binding Chromium to the main looper Looper (main, tid 1) {422a22b8}
,E/UpdateRequestReceiver( 4178): ignoring update request
,D/dalvikvm( 4198): GC_CONCURRENT freed 2996K, 32% free 9569K/13916K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 4198): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/chromium( 3885): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BootReceiver( 2419): Checking for fsck errors
E/UpdateRequestReceiver( 4178): ignoring update request
,E/UpdateRequestReceiver( 4178): ignoring update request
,I/BrowserProcessMain( 3885): Initializing chromium process, renderers=0
,E/UpdateRequestReceiver( 4178): ignoring update request
,E/UpdateRequestReceiver( 4178): ignoring update request
,D/@ WidgetProvider( 4198): onReceive = android.appwidget.action.APPWIDGET_ENABLED
,E/UpdateRequestReceiver( 4178): ignoring update request
,D/@ WidgetProvider( 4198): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider( 4198): onUpdate called for widgetId : 0
,W/GAV2    ( 3847): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/@ WidgetProvider( 4198): Widget random data : 7
,D/@ WidgetProvider( 4198): onUpdate called for widgetId : 5
,D/@ WidgetProvider( 4198): Widget random data : 5
,I/SELinux ( 4238): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4238):  
,I/ActivityManager( 2419): Killing 2800:com.android.printspooler/u0a146 (adj 15): empty #43
,I/bt_hwcfg( 4069): bt vendor lib: set UART baud 3000000
,I/ActivityManager( 2419): Killing 3186:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/libEGL  ( 3885): loaded /system/lib/egl/libEGL_mali.so
I/ActivityManager( 2419): Killing 3230:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,D/libEGL  ( 3885): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/AmoledAdjustTimer( 2419): TEMP_TABLE[0] = -20
D/AmoledAdjustTimer( 2419): TEMP_TABLE[1] = -19
D/AmoledAdjustTimer( 2419): TEMP_TABLE[2] = 0
D/AmoledAdjustTimer( 2419): TEMP_TABLE[3] = 1
D/AmoledAdjustTimer( 2419): prevTemp = 200, currTemp = 282, prevStep = 4, currStep = 4
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/libEGL  ( 3885): loaded /system/lib/egl/libGLESv2_mali.so
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
W/chromium( 3885): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
E/dalvikvm( 4198): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm( 4198): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm( 4198): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm( 4198): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm( 4198): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm( 4198): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm( 4198): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm( 4198): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm( 4198): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm( 4198): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm( 4198): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm( 4198): VFY: replacing opcode 0x22 at 0x0038
I/bt_hwcfg( 4069): vendor lib fwcfg completed
D/GKI_LINUX( 4069): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
D/dalvikvm( 4198): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm( 4198): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm( 4198): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
I/        ( 4069): BTE_InitTraceLevels -- TRC_HCI
I/        ( 4069): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 4069): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 4069): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 4069): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 4069): BTE_InitTraceLevels -- TRC_A2D
I/        ( 4069): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 4069): BTE_InitTraceLevels -- TRC_BTM
I/        ( 4069): BTE_InitTraceLevels -- TRC_GAP
I/        ( 4069): BTE_InitTraceLevels -- TRC_PAN
I/        ( 4069): BTE_InitTraceLevels -- TRC_SAP
I/        ( 4069): BTE_InitTraceLevels -- TRC_SDP
D/dalvikvm( 4198): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
I/        ( 4069): BTE_InitTraceLevels -- TRC_GATT
I/        ( 4069): BTE_InitTraceLevels -- TRC_SMP
I/        ( 4069): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 4069): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 4069): BTE_InitTraceLevels -- TRC_PROTOCOL
I/SELinux ( 4238): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4238):  
I/SELinux ( 4238):  
I/SELinux ( 4238): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4238): >>>>> Normal User
E/dalvikvm( 4238): >>>>> com.samsung.android.providers.context [ userId:0 | appId:10005 ]
I/Mali    ( 3885): Mali API Version : 401
I/Mali    ( 3885): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
E/SELinux ( 4238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4238): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4238): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4238): Added TimaKesytore provider
,D/SensorService( 2419):   0.2 -0.0 9.8
,D/dalvikvm( 3885): GC_CONCURRENT freed 899K, 17% free 11753K/14000K, paused 2ms+3ms, total 37ms
E/bt-btm  ( 4069): BTM_SecRegister:p_cb_info->p_le_callback == 0x77ce9af9 
,E/bt-btm  ( 4069): BTM_SecRegister: btm_cb.api.p_le_callback = 0x77ce9af9 
,E/bt-btif ( 4069): Calling BTA_HhEnable
,E/bt-btif ( 4069): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 4069): populateRssiValuesNative
I/bluedroid( 4069): getModelRssiValues
,E/BluetoothServiceJni( 4069): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/dalvikvm( 4238): GC_CONCURRENT freed 2927K, 31% free 9641K/13920K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 4238): WAIT_FOR_CONCURRENT_GC blocked 17ms
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/System.out( 4198): Thread-231(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
I/System.out( 4198): Thread-231(ApacheHTTPLog):isShipBuild true
,I/System.out( 4198): Thread-231(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,I/System.out( 4198): AsyncNetworking-1-thread-1 calls detatch()
,W/System.err( 4198): java.net.UnknownHostException: Unable to resolve host "wap.muzodajnia1.plus.pl": No address associated with hostname
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
W/System.err( 4198): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:424)
W/System.err( 4198): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:236)
W/System.err( 4198): 	at java.net.InetAddress.getAllByName(InetAddress.java:214)
W/System.err( 4198): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
W/System.err( 4198): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
W/System.err( 4198): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
,W/System.err( 4198): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1227)
W/System.err( 4198): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:677)
W/System.err( 4198): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:570)
,W/System.err( 4198): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:491)
W/System.err( 4198): 	at com.n7mobile.common.Networking.requestCore(Networking.java:693)
W/System.err( 4198): 	at com.n7mobile.common.Networking.makeGetRequest(Networking.java:655)
,W/System.err( 4198): 	at com.n7mobile.common.Networking.downloadAndParseXml(Networking.java:1155)
W/System.err( 4198): 	at com.n7mobile.common.AsyncNetworking$15.call(AsyncNetworking.java:628)
W/System.err( 4198): 	at com.n7mobile.common.AsyncNetworking$AsyncTask$AsyncRunnable.run(AsyncNetworking.java:254)
,W/System.err( 4198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 4198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 4198): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4198): Caused by: libcore.io.GaiException: getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 4198): 	at libcore.io.Posix.getaddrinfo(Native Method)
E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,W/System.err( 4198): 	at libcore.io.ForwardingOs.getaddrinfo(ForwardingOs.java:61)
W/System.err( 4198): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:405)
,W/System.err( 4198): 	... 17 more
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,D/@ WidgetProvider( 4198): Building error widget : 0
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 4069): isSecureModeOn:false
I/System.out( 4198): AsyncNetworking-1-thread-1 calls detatch()
E/BluetoothRemoteDevices( 4069): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 4069): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
I/bt_hwcfg( 4069): hw_sco_disable_i2s_setting {0, 0, 0, 0}
I/bt_hwcfg( 4069): SCO PCM configure {0, 4, 0, 0, 0}
E/bt-btif ( 4069): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 4069): btif_sock_init: !radio_req && !rfc_init
W/System.err( 4198): java.net.UnknownHostException: Unable to resolve host "wap.muzodajnia1.plus.pl": No address associated with hostname
,E/bt-btif ( 4069): btif_sock_init: !vhci_init
W/System.err( 4198): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:394)
,W/System.err( 4198): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:236)
W/System.err( 4198): 	at java.net.InetAddress.getAllByName(InetAddress.java:214)
,W/System.err( 4198): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
W/System.err( 4198): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
W/System.err( 4198): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
,W/System.err( 4198): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1227)
W/System.err( 4198): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:677)
,W/System.err( 4198): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:570)
W/System.err( 4198): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:491)
W/System.err( 4198): 	at com.n7mobile.common.Networking.requestCore(Networking.java:693)
,W/System.err( 4198): 	at com.n7mobile.common.Networking.makeGetRequest(Networking.java:655)
W/System.err( 4198): 	at com.n7mobile.common.Networking.downloadAndParseXml(Networking.java:1155)
W/System.err( 4198): 	at com.n7mobile.common.AsyncNetworking$15.call(AsyncNetworking.java:628)
W/System.err( 4198): 	at com.n7mobile.common.AsyncNetworking$AsyncTask$AsyncRunnable.run(AsyncNetworking.java:254)
,D/IOP_DB_BT( 4069): db_open: file /etc/bluetooth/iop_bt.db
W/System.err( 4198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 4198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 4198): 	at java.lang.Thread.run(Thread.java:841)
,D/@ WidgetProvider( 4198): Building error widget : 5
D/IOP_DB_BT( 4069): db_open: db_open : handle 2010915884l, read 9734 bytes onto local cache
D/IOP_DB_BT( 4069): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 4069): db_query: result 1
,I/        ( 4069): iop_db_open: iop_db_open status 0
,I/bte_conf( 4069): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 4069): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 4069): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 4069): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 4069): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4069): ScanMode =  20
,D/BluetoothAdapterProperties( 4069): State =  11
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
D/BtConfig.SecureMode( 4069): isSecureModeOn:false
,I/BluetoothAdapterState( 4069): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 4069): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 4069): updateAdapterState state is 12
,E/bt_h4   ( 4069): vendor lib postload completed
,D/BluetoothAdapterService( 4069): Broadcasting updateAdapterState() to 1 receivers.
,E/bt_h4   ( 4069): vendor lib postload completed
,D/BluetoothAdapterService(1110046840)( 4069): Register RemoteMessageListener
,D/HeadsetService( 4069): registerMessageListener
,D/BluetoothAdapterService( 4069): Autoconnection is available 
,D/BluetoothA2dp( 2419): onBluetoothStateChange: up=true
,D/HeadsetStateMachine( 4069): Disconnected process message: 70
D/HeadsetStateMachine( 4069): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@422d3e58
,D/BluetoothAdapterService( 4069): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 4069): starting service from this receiver
,W/ContextImpl( 4069): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothAdapterService( 4069): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
D/BluetoothPanServiceJni( 4069): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/bluedroid( 4069): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothAdapterState( 4069): Entering On State from state = 11
,I/BluetoothPbapService( 4069): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 2419): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2419): [BT Setting State] State =12
I/InputMethodManagerService( 2419): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapterService(1110046840)( 4069): Get Bonded Devices being called
D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/SamsungIME( 3041): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 2751): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@424dc178, true
,D/BluetoothHeadset( 2751): registerMessageListener
,D/HeadsetService( 4069): registerMessageListener
,D/HeadsetService( 4069): registerMessageListener
,D/HeadsetStateMachine( 4069): Disconnected process message: 70
D/HeadsetStateMachine( 4069): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42374288
,D/PhoneApp( 2751): registerMessageListener
,I/dhcpcd  ( 4257): if(wlan0) info get Success. (MAC : C0.AA.48)
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
,I/dhcpcd  ( 4257): bssid match
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/BluetoothPbapService( 4069): Handler(): got msg=1
,D/dalvikvm( 4238): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4231ebd0, skipping init
I/SecureStorage( 4238): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 4238): [INFO]: SPID(0x00000000)This device supports Secure Storage
,V/BluetoothPbapService( 4069): PBAP Service initSocket try: 0
I/SecureStorage( 1965): [INFO]: SPID(0x00000002)Credentials: uid 10005, gid 10005, pid 4238
I/SecureStorage( 1965): [INFO]: SPID(0x00000002)Received function mask & code: 0000010C
,I/SecureStorage( 4238): [INFO]: SPID(0x00000000)SS Daemon is running
,D/BluetoothMapMasInstance( 4069): set MAP SDP message type : 1
,D/BluetoothManagerService( 2419): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:2
,I/SELinux ( 4271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4271):  
,I/SecureStorage( 4238): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000002)Credentials: uid 10005, gid 10005, pid 4238
,I/SecureStorage( 1965): [INFO]: SPID(0x00000002)Received function mask & code: 00000106
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,W/BluetoothAdapter( 4069): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 4069): SOCK FLAG = 3 ***********************
,W/BluetoothAdapter( 4069): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 4069): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 4069): PBAP Socket is BluetoothServerSocket
,D/checkbox( 3885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 3885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 3885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 3885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
I/SELinux ( 4271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4271):  
I/SELinux ( 4271):  
,I/SELinux ( 4271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4271): >>>>> Normal User
,E/dalvikvm( 4271): >>>>> com.sec.dsm.system [ userId:0 | appId:1000 ]
,E/SELinux ( 4271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4271): in addTimaSignatureService
,D/Mms/BubbleViewCache( 3885): fillCache bubble = 8
,D/TimaKeyStoreProvider( 4271): Cannot add TimaSignature Service, License check Failed
,D/Mms/Synchronizer( 3885): [start]    dbSync()
,D/ActivityThread( 4271): Added TimaKesytore provider
,D/TP/MmsSmsProvider( 2751): update uri: content://mms-sms/db_synchronization
,V/TP/MmsSmsProvider( 2751): syncDBData start
,D/TP/MmsSmsProvider( 2751): match 0:Elapsed time : 1.860 ms
,V/TP/MmsSmsProvider( 2751): syncDBData sms end
,V/TP/MmsSmsProvider( 2751): syncDBData mms end
,V/TP/MmsSmsProvider( 2751): syncDBData end
,D/Mms/Synchronizer( 3885): [end]    dbSync()
,I/SELinux ( 4284): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4284):  
,I/SELinux ( 4284): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4284):  
I/SELinux ( 4284):  
,I/SELinux ( 4284): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4284): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4284): >>>>> Normal User
E/dalvikvm( 4284): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 4284): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 4271): GC_CONCURRENT freed 3003K, 32% free 9567K/13916K, paused 9ms+2ms, total 32ms
,D/dalvikvm( 4271): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/TimaKeyStoreProvider( 4284): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4284): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4284): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 3249:com.android.musicfx/u0a24 (adj 15): empty #43
,D/DSM     ( 4271): [Lines:106] Normal booted
,D/DSM     ( 4271): [Lines:113] Boot completed
,D/dalvikvm( 4284): GC_CONCURRENT freed 3002K, 32% free 9565K/13916K, paused 6ms+2ms, total 30ms
,D/dalvikvm( 4284): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/BadgeProvider( 4284): onCreate
,D/BadgeProvider( 4284): DatabaseHelper
,I/SELinux ( 4297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4297):  
,I/ActivityManager( 2419): Killing 3262:com.sec.pcw.device/1000 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 45K, 13% free 9502K/10896K, paused 2ms+3ms, total 34ms
,I/SELinux ( 4297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4297):  
I/SELinux ( 4297):  
,I/SELinux ( 4297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4297): >>>>> Normal User
,E/dalvikvm( 4297): >>>>> com.sec.android.app.factorykeystring [ userId:0 | appId:1000 ]
,E/SELinux ( 4297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 28ms
,D/TimaKeyStoreProvider( 4297): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4297): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4297): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 26ms
,D/Mms/MessagingNotification( 3885): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/MmsSmsProvider( 2751): match 6:Elapsed time : 1.336 ms
,D/dalvikvm( 4297): GC_CONCURRENT freed 2995K, 32% free 9570K/13916K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 4297): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ActivityThread( 4297): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-g800f.dat
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=kminilte.dat
,I/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-g800f.dat
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IRLED_CONCEPT
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_EPEN
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_COMPLEX_LOOPBACK_TEST
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_IF_CORROSION
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{4330c6a8 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_COMPLEX_LOOPBACK_PATH
I/GAV2    ( 3847): Thread[GAThread,5,main]: No campaign data found.
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=GESTURE_CROSSTALK_RAW
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
I/GAv4-SVC( 3158): Google Analytics 8.4.89 is starting up.
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 4297): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 4297): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,I/SELinux ( 4314): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4314):  
,I/SELinux ( 4314): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4314):  
I/SELinux ( 4314):  
,I/SELinux ( 4314): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4314): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 4314): >>>>> Normal User
,E/dalvikvm( 4314): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 4314): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2419): Killing 3275:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4314): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4314): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4314): Added TimaKesytore provider
,D/dalvikvm( 4314): GC_CONCURRENT freed 3003K, 32% free 9569K/13920K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 4314): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/FactoryTestApp( 4314): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.BOOT_COMPLETED
,D/FactoryTestApp( 4314): [XMLDataStorage$parseXML] is Live Demo : false
,W/ActivityThread( 4314): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 4314): [XMLDataStorage$parseXML] modelXML=sm-g800f.dat
D/FactoryTestApp( 4314): [XMLDataStorage$parseXML] deviceXML=kminilte.dat
D/FactoryTestApp( 4314): [XMLDataStorage$parseXML] nameXML=kminiltexx.dat
,I/FactoryTestApp( 4314): [XMLDataStorage$parseAsset] Convert dat file: sm-g800f.dat
,D/FactoryTestApp( 4314): [XMLDataStorage$parseAsset] Decode base file: factory.dat
,I/SecureStorage( 1965): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000002)PID: 4238, TID: 4268
,D/dalvikvm( 4314): GC_CONCURRENT freed 2508K, 28% free 10048K/13920K, paused 1ms+3ms, total 18ms
,I/SecureStorage( 4238): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SQLiteSecureOpenHelper( 4238): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4238): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4238): Open SecureContextLog.db in secure mode
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FAILHIST_VERSION
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MIC_COUNT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOST_MEDIASCAN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=CAL_AP_TEMP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FONT_SIZE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
I/SQLiteSecureOpenHelper( 4238): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4238): ...getDatabaseLocked(b,b,pwd)
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
I/SQLiteSecureOpenHelper( 4238): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4238): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4238): Open SecureSurveyLog.db in secure mode
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
I/SQLiteSecureOpenHelper( 4238): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4238): ...getDatabaseLocked(b,b,pwd)
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=AT_SPKSTEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2419): VerifyingLinkState enter
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SQLiteSecureOpenHelper( 4238): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4238): getDatabaseLocked(b,b,pwd)...
W/ActivityManager( 2419): mDVFSHelper.acquire()
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:3873,o:f
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,V/RouteController( 1914): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
I/ActivityManager( 2419): Killing 3412:com.osp.app.signin/u0a44 (adj 15): empty #43
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,V/RouteController( 1914): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
,V/RouteController( 1914): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
,V/RouteController( 1914): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
,E/BluetoothHeadset( 4238): BTStateChangeCB is registed
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,E/BluetoothHeadset( 4238): BluetoothHeadset service is binded
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): forceRefresh() from cache miss
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
V/NetworkStats( 2419): performPollLocked() took 16ms
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
,I/SQLiteSecureOpenHelper( 4238): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4238): getDatabaseLocked(b,b,pwd)...
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
I/SQLiteSecureOpenHelper( 4238): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4238): getDatabaseLocked(b,b,pwd)...
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/BluetoothA2dp( 4238): Proxy object connected
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by BW check
,D/NtpTrustedTime( 2419): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1452527841395 mCachedNtpElapsedRealtime : 43740 mCachedNtpCertainty : 10
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,I/SurfaceFlinger( 1921): id=15 Removed CatteryCove (10/11)
,I/SurfaceFlinger( 1921): id=15 Removed CatteryCove (-2/11)
,I/SurfaceFlinger( 1921): id=14 Removed CatteryCove (9/10)
,I/SurfaceFlinger( 1921): id=14 Removed CatteryCove (-2/10)
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/dalvikvm( 4314): GC_CONCURRENT freed 3729K, 33% free 10351K/15424K, paused 1ms+2ms, total 37ms
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_CMD
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=LED_RED
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=LED_GREEN
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=LED_BLUE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=USB3_TYPE_CHECK
,D/FactoryTestApp( 4314): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/FactoryTestApp( 4314): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/FactoryTestApp( 4314): [Support$Values.getString] id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
D/FactoryTestApp( 4314): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
D/FactoryTestApp( 4314): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
D/FactoryTestApp( 4314): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=S.LSI
,I/FactoryTestApp( 4314): [ModuleCommon$ModuleCommon] Create ModuleCommon
,D/FactoryTestApp( 4314): [Support$Values.getString] id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
D/FactoryTestApp( 4314): [Support$Kernel.read] path=/efs/FactoryApp/factorymode, value=ON
,I/FactoryTestApp( 4314): [ModuleCommon$readFactoryMode] mode: ON
,D/FactoryTestApp( 4314): [Support$Values.getString] id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 4314): [FactoryTestBroadcastReceiver$onReceive] KEYSTRING_BLOCK is already existed...
,D/FactoryTestApp( 4314): [Support$Values.getString] id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
D/FactoryTestApp( 4314): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 4314): [Support$Properties.get] property=ro.factory.factory_binary
D/FactoryTestApp( 4314): [FactoryTestBroadcastReceiver$onReceive] Boot completed, IS_FACTORY_BINARY = Unknown
,I/FactoryTestApp( 4314): [ModuleCommon$15 Test Ready flag] blocking
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/        ( 2419): Setting time of day to sec=1452527841
,D/        ( 2419): Trying to open a file
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
D/        ( 2419): File Open Success
D/        ( 2419): File Close Success
,I/        ( 2419): DRM_TIME_PATH CHMOD 660 for resetState done 
V/AlarmManager( 2419): waitForAlarm result :65536
,I/FactoryTestApp( 4314): [ModuleCommon$getFtClientEnableState] result : false
,I/FactoryTestApp( 4314): [ModuleCommon$connectedJIG] ...
D/FactoryTestApp( 4314): [Support$Values.getString] id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
,I/FactoryTestApp( 4314): [ModuleCommon$connectedJIG] cable_type = ANYWAY_JIG
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
V/AlarmManager( 2419): waitForAlarm result :8
D/StatusBar-DoNotDistrub( 2578): Received intent with android.intent.action.TIME_SET action
D/NotificationMgr( 2751): updateNotificationsAtStartup()...
,D/NotificationMgr( 2751): - start call log query...
,D/StatusBar-DoNotDistrub( 2578): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Settings( 2419): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AudioService( 2419): getStreamVolume 5 index 110
,E/Parcel  ( 2419): nm 23
D/StatusBar-DoNotDistrub( 2578): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2578): The STREAM NOTIFICATION volume is 0
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=com.android.systemui
I/PrGenericPlugin( 1924): [A] ENTER onAcquireDrmInfo : 0xbd0
I/PrGenericPlugin( 1924): [A] LEAVE onAcquireDrmInfo : 0xbd0
,I/DrmEventService( 2419):  no response from SecureClock 
D/STATUSBAR-NotificationService( 2419): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2419): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/NotificationMgr( 2751): call log query complete.
D/NotificationMgr( 2751): call log cursor count : 0
D/NotificationMgr( 2751): call log cursor count2 : null
D/FactoryTestApp( 4314): [Support$Values.getString] id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 4314): [Support$Values.getString] id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 4314): [Support$Kernel.read] path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 4314): [ModuleCommon$connectedJIG] value = 1f, JIG_ON = 1C
D/FactoryTestApp( 4314): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 4314): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTest( 4314): User mode
,I/FactoryTestApp( 4314): [ModuleCommon$disableFtClient] ...
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4374):  
I/ActivityManager( 2419): Killing 3370:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/SELinux ( 4374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4374):  
I/SELinux ( 4374):  
,I/SELinux ( 4374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4374): >>>>> Normal User
,E/dalvikvm( 4374): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 4374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4374): Added TimaKesytore provider
,I/SELinux ( 4389): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4389):  
,I/SELinux ( 4389): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4389):  
I/SELinux ( 4389):  
I/SELinux ( 4389): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,E/SELinux ( 4389): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 4389): >>>>> Normal User
,E/dalvikvm( 4389): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 4389): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 4389): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4389): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4389): Added TimaKesytore provider
D/dalvikvm( 4374): GC_CONCURRENT freed 3000K, 32% free 9568K/13920K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 4374): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/DBG_DIAGMONDM( 4374): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/dalvikvm( 4389): GC_CONCURRENT freed 2998K, 32% free 9566K/13916K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 4389): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/DBG_DIAGMONDM( 4374): [1.140541.0531][Line:48][onCreate] myUserId : 0
,I/DBG_DIAGMONDM( 4374): [1.140541.0531][Line:376][xdbDMffs_Init] 
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DIAGMONDM( 4374): [1.140541.0531][Line:70][onCreate] nStatus : 0
,I/SELinux ( 4405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4405):  
,I/SELinux ( 4405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4405):  
I/SELinux ( 4405):  
,I/SELinux ( 4405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4405): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4405): >>>>> Normal User
,E/dalvikvm( 4405): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 4405): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4405): Added TimaKesytore provider
,D/dalvikvm( 4405): GC_CONCURRENT freed 3002K, 32% free 9565K/13916K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 4405): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2419): Killing 3207:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/SensorService( 2419):   0.2 -0.0 9.9
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 4425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4425):  
,I/SELinux ( 4425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4425):  
I/SELinux ( 4425):  
,I/SELinux ( 4425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4425): >>>>> Normal User
,E/dalvikvm( 4425): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 4425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4425): Added TimaKesytore provider
,I/RlzPingService( 3469): Setting next ping for 1453132642725
,D/dalvikvm( 4425): GC_CONCURRENT freed 2999K, 32% free 9565K/13916K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 4425): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/KLMS-2.3.201 : ( 4425): KLMSValidator() : checkQATesting()
,D/dalvikvm( 2419): GC_EXPLICIT freed 2488K, 20% free 23976K/29936K, paused 7ms+15ms, total 182ms
,I/ActivityManager( 2419): Killing 3463:com.samsung.android.intelligenceservice/u0a5 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 4425): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.BOOT_COMPLETED , timestamp: 1452527842874
,I/SELinux ( 4439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4439):  
,I/ActivityManager( 2419): Killing 3497:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 4439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4439):  
I/SELinux ( 4439):  
,I/SELinux ( 4439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4439): >>>>> Normal User
,E/dalvikvm( 4439): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 4439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4439): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4439): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4439): Added TimaKesytore provider
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
D/dalvikvm( 4439): GC_CONCURRENT freed 3003K, 32% free 9567K/13916K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 4439): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SELinux ( 4453): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4453):  
I/ActivityManager( 2419): Killing 3513:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 4453): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4453):  
I/SELinux ( 4453):  
,I/SELinux ( 4453): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4453): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4453): >>>>> Normal User
,E/dalvikvm( 4453): >>>>> com.sec.android.app.msa [ userId:0 | appId:10023 ]
,E/SELinux ( 4453): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4453): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4453): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4453): Added TimaKesytore provider
,D/dalvikvm( 4453): GC_CONCURRENT freed 3014K, 32% free 9558K/13920K, paused 1ms+1ms, total 19ms
,D/dalvikvm( 4453): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 4467): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4467):  
,I/ActivityManager( 2419): Killing 3533:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 4467): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4467):  
I/SELinux ( 4467):  
,I/SELinux ( 4467): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4467): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4467): >>>>> Normal User
,E/dalvikvm( 4467): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 4467): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4467): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4467): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4467): Added TimaKesytore provider
,D/dalvikvm( 4467): GC_CONCURRENT freed 2999K, 32% free 9566K/13912K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 4467): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/GKI_LINUX( 4069): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,E/MTPRx   ( 4467): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,I/SELinux ( 4480): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4480):  
,I/ActivityManager( 2419): Killing 3547:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,I/SELinux ( 4480): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4480):  
I/SELinux ( 4480):  
,I/SELinux ( 4480): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4480): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4480): >>>>> Normal User
,E/dalvikvm( 4480): >>>>> com.android.onetimeinitializer [ userId:0 | appId:10028 ]
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,E/SELinux ( 4480): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4069): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4069): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
D/TimaKeyStoreProvider( 4480): in addTimaSignatureService
D/TimaKeyStoreProvider( 4480): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4480): Added TimaKesytore provider
,D/dalvikvm( 4480): GC_CONCURRENT freed 3014K, 32% free 9559K/13920K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 4480): WAIT_FOR_CONCURRENT_GC blocked 15ms
,V/OneTimeInitializerRece( 4480): OneTimeInitializerReceiver.onReceive
,I/SELinux ( 4495): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4495):  
,I/ActivityManager( 2419): Killing 3561:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/SELinux ( 4495): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4495):  
I/SELinux ( 4495):  
,I/SELinux ( 4495): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4495): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4495): >>>>> Normal User
,E/dalvikvm( 4495): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 4495): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 4495): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 4495): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4495): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4495): Added TimaKesytore provider
,D/dalvikvm( 4495): GC_CONCURRENT freed 3006K, 32% free 9560K/13916K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 4495): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/PCWCLIENTTRACE_PushUtil( 4495): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4495): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4495): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 4495): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4495): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_SYSTEMReceiver( 4495): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 4495): ACTION_BOOTUP - Version: 4.72
,D/PCWCLIENTTRACE_SYSTEMReceiver( 4495): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/PCWCLIENTTRACE_AccountUtil( 4495): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 4495): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4495): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 4495): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 4495): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4495): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4495): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4495): [ensureRegistration] - No Samsung account
,I/SELinux ( 4508): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4508):  
I/ActivityManager( 2419): Killing 3577:com.samsung.helphub/1000 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9502K/10896K, paused 2ms+3ms, total 28ms
,I/SELinux ( 4508): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4508):  
I/SELinux ( 4508):  
,I/SELinux ( 4508): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4508): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4508): >>>>> Normal User
,E/dalvikvm( 4508): >>>>> com.sec.android.pagebuddynotisvc [ userId:0 | appId:10029 ]
,E/SELinux ( 4508): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 4508): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4508): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4508): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 4508): GC_CONCURRENT freed 2998K, 32% free 9572K/13920K, paused 5ms+1ms, total 21ms
,D/dalvikvm( 4508): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/PageBuddyNotiSvcBRcvr( 4508): Intent received
,W/ContextImpl( 4508): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:39 
,I/PageBuddyNotiSvc( 4508): onCreate mCpBitFlag=0
,I/SELinux ( 4521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4521):  
,I/SELinux ( 4521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4521):  
I/SELinux ( 4521):  
,I/SELinux ( 4521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4521): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4521): >>>>> Normal User
,E/dalvikvm( 4521): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 4521): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4521): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4521): Added TimaKesytore provider
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/dalvikvm( 4521): GC_CONCURRENT freed 3007K, 32% free 9566K/13920K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 4521): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/ActivityThread( 3158): Failed to find provider info for com.android.contacts.metadata
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/DelayedSyncController( 4389): Delaying sync.
D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/dalvikvm( 3158): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 3158): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3158): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 2850): GC_EXPLICIT freed 1116K, 25% free 10417K/13888K, paused 5ms+5ms, total 71ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,D/NtpTrustedTime( 2419): getCachedNtpTime() cache hit
W/ActivityManager( 2419): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/SyncManager( 2419): failed sync operation 
,D/SyncManager( 2419): not retrying sync operation because the error is a hard error: 
,I/ActivityManager( 2419): Killing 3589:com.android.keychain/1000 (adj 15): empty #43
,I/System.out( 4521): Inside WakeupProvider
,I/System.out( 4521): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4521): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 4521): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4521): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,E/BOOT    ( 4521): Received!com.vlingo.client.vlingoconfigprovider TIME: 1452527844415
,D/DialogFlow( 4521): initQueue()
,I/ActivityManager( 2419): Killing 3627:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,I/Process ( 3289): Sending signal. PID: 3289 SIG: 9
,I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 3289) (adj 0) has died.
,I/SELinux ( 4545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4545):  
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SELinux ( 4545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4545):  
I/SELinux ( 4545):  
,I/SELinux ( 4545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4545): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4545): >>>>> Normal User
,E/dalvikvm( 4545): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 4545): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4545): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4545): Added TimaKesytore provider
,D/dalvikvm( 4545): GC_CONCURRENT freed 2994K, 32% free 9568K/13912K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 4545): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/DriveInitializer( 3158): Awaiting to be initialized
,W/DriveInitializer( 3158): Background init thread started
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3158): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ContextImpl( 4545): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 4572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4572):  
,E/Device Type Shared Preferences( 4545): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 4545): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 4545): ContentProvider is not null
,W/ResourceType( 4545): No package identifier when getting value for resource number 0x00000000
,I/System.out( 4545): resource Id::2131361807
,I/SELinux ( 4572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4572):  
I/SELinux ( 4572):  
,I/SELinux ( 4572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4572): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4572): >>>>> Normal User
,E/dalvikvm( 4572): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 4572): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/DriveInitializer( 3158): Background init thread ended
,D/TimaKeyStoreProvider( 4572): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4572): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4572): Added TimaKesytore provider
,D/dalvikvm( 4572): GC_CONCURRENT freed 3009K, 32% free 9557K/13916K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 4572): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.sec.android.app.shealth.SHealthApplication( 4545): Success during batch insertion in App registry:0
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,V/MediaPlayer( 4545): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1925): decode(26, 30565892, 48105)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444f6ec8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6ec8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x24, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4545): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1925): decode(26, 30501792, 10421)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x442bbae0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 6, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442bbae0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x25, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4545): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1925): decode(26, 34044116, 34198)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x43f402d0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
,I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x43f402d0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x43f402d0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x26, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4545): decode(60, 30449260, 7405)
V/MediaPlayerService( 1925): decode(27, 30449260, 7405)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
,V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 30449260, 7405)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 200, 973, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 1, 0, 0)
V/AudioCache( 1925): prepared
,V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 6, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444f6e30, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e30, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4545): decode(61, 34134748, 5555)
V/MediaPlayerService( 1925): decode(26, 34134748, 5555)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34134748, 5555)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
D/btif_config_util( 4069): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
,V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): addBatteryData
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4545): decode(62, 26954540, 5085)
V/MediaPlayerService( 1925): decode(26, 26954540, 5085)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4545): decode(63, 26959684, 21552)
,V/MediaPlayerService( 1925): decode(27, 26959684, 21552)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 26959684, 21552)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 1925): notify(0x444f77f0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 5, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
,V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f77f0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4545): decode(64, 34130460, 4230)
,V/MediaPlayerService( 1925): decode(26, 34130460, 4230)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink,
V/StagefrightPlayer( 1925): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear,
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
,I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 5, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
,V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6eb0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4545): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1925): decode(27, 26923896, 9400)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 26923896, 9400)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fb950, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,I/Process ( 4545): Sending signal. PID: 4545 SIG: 9
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
,I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444fb950, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444fb950, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fb950, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
E/IMemory ( 1925): binder=0x444fb8d0 transaction failed fd=-2147483647, size=0, err=-2147483646 (Unknown error 2147483646)
,E/IMemory ( 1925): cannot dup fd=-2147483647, size=0, err=-2147483646 (Bad file number)
,E/IMemory ( 1925): cannot map BpMemoryHeap (binder=0x444fb8d0), size=0, fd=-1 (Bad file number)
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fb950, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 4545) (adj 0) has died.
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,E/Watchdog( 2419): !@Sync 1
,I/SELinux ( 4637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4637):  
,I/SELinux ( 4637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4637):  
I/SELinux ( 4637):  
,I/SELinux ( 4637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4637): >>>>> Normal User
,E/dalvikvm( 4637): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4637): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4637): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4637): Added TimaKesytore provider
,D/dalvikvm( 4637): GC_CONCURRENT freed 3002K, 32% free 9568K/13920K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4637): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/SensorService( 2419):   0.2 -0.0 9.9
,W/ContextImpl( 4637): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,E/Device Type Shared Preferences( 4637): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 4637): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 4637): ContentProvider is not null
,W/ResourceType( 4637): No package identifier when getting value for resource number 0x00000000
,I/System.out( 4637): resource Id::2131361807
,D/com.sec.android.app.shealth.SHealthApplication( 4637): Success during batch insertion in App registry:0
,V/MediaPlayer( 4637): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1925): decode(26, 30565892, 48105)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
,V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 1, 0, 0)
,V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 6, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbc48, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1925): decode(26, 30501792, 10421)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
,V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 8, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 1925): notify(0x442c0cb8, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 5, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
,V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x442c0cb8, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442c0cb8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1925): decode(25, 34044116, 34198)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(25, 34044116, 34198)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444fbb80, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444fbb80, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444fbb80, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(60, 30449260, 7405)
V/MediaPlayerService( 1925): decode(26, 30449260, 7405)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30449260, 7405)
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
,V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(61, 34134748, 5555)
,V/MediaPlayerService( 1925): decode(25, 34134748, 5555)
V/MediaPlayerService( 1925): player type = 3
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
,V/StagefrightPlayer( 1925): setDataSource(25, 34134748, 5555)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 5, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
,V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 6, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444f9180, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9180, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(62, 26954540, 5085)
,V/MediaPlayerService( 1925): decode(26, 26954540, 5085)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
,V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream,
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
,V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
,V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0),
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 4637): decode(63, 26959684, 21552)
V/MediaPlayerService( 1925): decode(26, 26959684, 21552)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
,V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 5, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 6, 0, 0),
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
,I/AudioPlayer( 1925): First fillBuffer call!!
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b4eb0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4637): decode(64, 34130460, 4230)
V/MediaPlayerService( 1925): decode(26, 34130460, 4230)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
,V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
,V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444f6e70, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
,V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f6e70, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 4637): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1925): decode(27, 26923896, 9400)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 26923896, 9400)
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f71b8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,I/Process ( 4637): Sending signal. PID: 4637 SIG: 9
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f71b8, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f71b8, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f71b8, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
,E/IMemory ( 1925): binder=0x442be7b0 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory ( 1925): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory ( 1925): cannot map BpMemoryHeap (binder=0x442be7b0), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f71b8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 4637) (adj 0) has died.
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,I/SELinux ( 4697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4697):  
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4697):  
I/SELinux ( 4697):  
,I/SELinux ( 4697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4697): >>>>> Normal User
,E/dalvikvm( 4697): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10037 ]
,E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4697): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4697): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4697): Added TimaKesytore provider
,D/dalvikvm( 4697): GC_CONCURRENT freed 2975K, 32% free 9596K/13920K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 4697): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/Process ( 4697): Sending signal. PID: 4697 SIG: 9
,I/ActivityManager( 2419): Process com.sec.android.app.sns3 (pid 4697) (adj 0) has died.
,I/SELinux ( 4720): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4720):  
,I/SELinux ( 4720): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4720):  
I/SELinux ( 4720):  
,I/SELinux ( 4720): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4720): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4720): >>>>> Normal User
,E/dalvikvm( 4720): >>>>> com.policydm [ userId:0 | appId:1000 ]
,E/SELinux ( 4720): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4720): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4720): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4720): Added TimaKesytore provider
,D/Finsky  ( 3750): [190] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3750): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 4720): GC_CONCURRENT freed 2998K, 32% free 9569K/13916K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 4720): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = -10
,I/SELinux ( 4736): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4736):  
,I/ActivityManager( 2419): Killing 3603:com.google.android.apps.plus/u0a133 (adj 15): empty #43
,I/SELinux ( 4736): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4736):  
I/SELinux ( 4736):  
,I/SELinux ( 4736): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4736): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4736): >>>>> Normal User
,E/dalvikvm( 4736): >>>>> com.osp.app.signin [ userId:0 | appId:10044 ]
,E/SELinux ( 4736): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4736): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4736): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4736): Added TimaKesytore provider
,D/dalvikvm( 4720): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4229ce10, skipping init
,I/SecureStorage( 4720): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 1000, gid 1000, pid 4720
,I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
,D/dalvikvm( 2419): GC_EXPLICIT freed 1804K, 20% free 24031K/29916K, paused 6ms+13ms, total 164ms
,D/dalvikvm( 4736): GC_CONCURRENT freed 2997K, 32% free 9575K/13920K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SA      ( 4736): [SSP] onCreated
,I/SA      ( 4736): [TPM] There is no property file
,I/SA      ( 4736): [SCU] isHaveSA() - false
I/SA      ( 4736): [TPM] getModelProperty : null
,I/SA      ( 4736): [TPM] getCSCProperty : null
I/SA      ( 4736): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
,I/SA      ( 4736): [DM] init START
,I/SA      ( 4736): [DM] This device is not a Vodafone
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SA      ( 4736): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4736): support phone number id : false
I/SA      ( 4736): [DM] init END
I/SA      ( 4736): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 4736): [BDLM] already registered in spp
,I/SA      ( 4736): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
,I/SA      ( 4736): [OR] onReceive END
,I/SA      ( 4736): [BDC] create
,I/SELinux ( 4754): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4754):  
,I/SA      ( 4736): [DBMV2] getEmailID
I/SA      ( 4736): [DBMV2] getDataV02ForItems
,I/SA      ( 4736): [SSP] query invoked
,I/SA      ( 4736): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4736): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4736): [BDC] destroy
I/ActivityManager( 2419): Killing 3643:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,I/SELinux ( 4754): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4754):  
I/SELinux ( 4754):  
,I/SELinux ( 4754): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4754): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4754): >>>>> Normal User
,E/dalvikvm( 4754): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 4754): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4754): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4754): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4754): Added TimaKesytore provider
,D/dalvikvm( 4754): GC_CONCURRENT freed 2994K, 32% free 9568K/13912K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 4754): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/MediaScannerReceiver( 2721): action: android.intent.action.BOOT_COMPLETED
,D/MediaScannerService( 2721): !@start scanning volume internal: [/system/media]
,D/TP/MmsProvider( 2751): Update uri=content://mms, match=0
,D/TP/MmsProvider( 2751): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 2751): need read changed broadcast:false
,I/Mms:transaction( 3885): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,D/Mms/MessagingNotification( 3885): [start]    nonBlockingUpdateMessageIndicator()
,I/Mms/ReservationManager( 3885): resetAfterConnected()
,D/MtpService( 2721): addStorageLocked 65537 /storage/emulated/0
,D/Mms/MessagingNotification( 3885): sDisableVibrateForCamera = false
,D/TP/MmsSmsProvider( 2751): match 7:Elapsed time : 3.689 ms
D/Mms/MessagingNotification( 3885): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3885): isDefault true
,I/Mms/ReservationManager( 3885): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 2751): match 200:Elapsed time : 2.873 ms
,I/SELinux ( 4776): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4776):  
,D/Mms/TelephonyPermission( 3885): isDefault true
,D/Mms/SmsReceiverService( 3885): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiverService( 3885): [start]    handleBootCompleted()
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000003)PID: 4720, TID: 4732
,D/TP/MmsSmsProvider( 2751): deleteConversation threadId: 9223372036854775806
,D/MediaScanner( 2721): Constructor set externalStorageSdPath : /storage/extSdCard
,D/MtpService( 2721): starting MTP server in MTP mode
,E/MtpServerJNI( 2721): could not open MTP driver, errno: 2
D/MtpService( 2721): addStorageLocked 65537 /storage/emulated/0
,E/MtpServerJNI( 2721): server is null in add_storage
,D/TP/MmsSmsProvider( 2751): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/MtpServerJNI( 2721): server is null in run
,E/MtpServerJNI( 2721): server is null in cleanup
,I/SELinux ( 4776): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4776):  
I/SELinux ( 4776):  
,I/SELinux ( 4776): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4776): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4776): >>>>> Normal User
,E/dalvikvm( 4776): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10051 ]
,E/SELinux ( 4776): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4776): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4776): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4776): Added TimaKesytore provider
,D/dalvikvm( 2751): GC_EXPLICIT freed 1832K, 26% free 10306K/13900K, paused 6ms+6ms, total 58ms
D/TP/MmsSmsProvider( 2751): delete threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 2751): need read changed broadcast:false
,D/Mms/Conversation( 3885): deleteTempConversation(),deleted=0
,D/SmsProvider( 2751): Update uri=content://sms/outbox, match=8
,D/TP/MmsSmsProvider( 2751): need read changed broadcast:false
,D/BadgeProvider( 4284): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/Mms/SmsReceiverService( 3885): sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 3885): [SIM-1]sendFirstQueuedMessage()
,D/MediaScanner( 2721): Prescan. DB items number : 158 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/BadgeProvider( 4284): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 4284): sendNotify, [notify] : null
D/BadgeProvider( 4284): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 4284): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4284): update, [UpdateCount] : 1
,D/Launcher.Model( 2782): reloadBadges entered.
,D/Mms/MessagingNotification( 3885): setBadgeCount(), count=0
,D/MessagingNotification( 3885): remove alarm
,D/dalvikvm( 4776): GC_CONCURRENT freed 2998K, 32% free 9567K/13916K, paused 2ms+2ms, total 22ms
D/Mms/MessagingNotification( 3885): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 3885): isBlockingModeEnable() = false
D/dalvikvm( 4776): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Mms/TelephonyPermission( 3885): isDefault true
,W/dalvikvm( 4776): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/Mms/MessagingNotification( 3885): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 3885): [end]    nonBlockingUpdateMessageIndicator()
,I/SecureStorage( 4720): [INFO]: SPID(0x00000000)Processing data has been completed
,D/SafetyAssuranceAppFeatures( 4776): init start
,I/SafetyAssuranceAppFeatures( 4776): mLoadBaiduMap:false
,D/SafetyAssuranceAppFeatures( 4776): init end
,D/SafetyAssuranceReceiver( 4776): onReceive
,I/SafetyAssuranceApp( 4776): Acquire WL
,D/TP/MmsSmsProvider( 2751): match 200:Elapsed time : 1.533 ms
,D/SafetyAssuranceConfig( 4776): getAppState : 1
D/SafetyAssuranceReceiver( 4776): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
,D/SafetyAssuranceReceiver( 4776): Init App state
,D/SafetyAssuranceConfig( 4776): setAppState : 1
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10051
D/SafetyAssuranceApp( 4776): topActivity's name is=.MainActivity
I/SafetyAssuranceApp( 4776): Release WL
,V/MediaScanner( 2721): processDirectory :  /system/media
,D/BadgeProvider( 4284): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/NearbySettings( 2828): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 2828): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 2828): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 2828): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 2828): MountReceiver.onReceive - Internal Path
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/Launcher.Model( 2782): reloadBadges entered.
D/BadgeProvider( 4284): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 4284): sendNotify, [notify] : null
D/BadgeProvider( 4284): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 4284): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4284): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3885): setBadgeCount(), count=0
,D/MessagingNotification( 3885): remove alarm
,D/Mms/MessagingNotification( 3885): updateAllHistoryAsRead()
,D/SensorService( 2419):   0.2 -0.0 9.9
D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 285, prevStep = 4, currStep = 4
,D/Mms/SmsReceiverService( 3885): [end]    handleBootCompleted()
,I/AccessibilityManagerService( 2419): setmDNIeNegative (false)
,W/Settings( 2828): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/MediaScanner( 2721):  prescan time: 248ms (DB items: 158)
V/MediaScanner( 2721):     scan time: 202ms (Caching mode: true), (makeEntry time: 79ms ~39%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 2721): postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 2721):    total time: 451ms
,V/MediaScanner( 2721): checked files: 149  directories : 7  (I: 0, U: 0)
,D/MediaScanner( 2721): checkDefaultSounds
,D/MediaScanner( 2721): system alarm_alert  : Vwiurug_etwofi5wgg
,D/MediaScanner( 2721): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 2721): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 2721): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 2721): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 2721): OK. ringtone is already exist in setting DB.
,D/MediaScannerService( 2721): !@done scanning volume internal
,D/MediaScannerService( 2721): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/[SBeam] ( 2828): SBeamEnabler.initPreferenceForSbeam : 0
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started
I/SettingSearch/SearchIntentReceiver( 2828): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 2828): search setting db init!!
,D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,W/ContextImpl( 2828): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
D/MediaProvider( 2721): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
I/SettingSearch/SearchIntentReceiver( 2828): BOOT_COMPLETED call InitSerachDBThread thread start!
D/MediaProvider( 2721): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 2721): Prescan. DB items number : 25 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/SELinux ( 4803): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4803):  
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,I/BootupListener( 2751): mPendingNetworkManualSelection : false
I/SELinux ( 4803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4803):  
I/SELinux ( 4803):  
,I/SELinux ( 4803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4803): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4803): >>>>> Normal User
,E/dalvikvm( 4803): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10162 ]
,E/SELinux ( 4803): [DEBUG] seapp_context_lookup: seinfoCategory = release
,V/MediaScanner( 2721): processDirectory :  /storage/emulated/0
,I/ManualSelectionReceiver( 2751): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,D/TimaKeyStoreProvider( 4803): in addTimaSignatureService
,I/SELinux ( 4815): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4815):  
,D/MediaScanner( 2721): Skipping:
,D/MediaScanner( 2721): 7klwibgf7fvntblfd7(75ebcf7
,D/TimaKeyStoreProvider( 4803): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4803): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 3659:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10896K, paused 5ms+3ms, total 35ms
I/SELinux ( 4815): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4815):  
I/SELinux ( 4815):  
,I/SELinux ( 4815): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4815): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4815): >>>>> Normal User
,E/dalvikvm( 4815): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 4815): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4815): in addTimaSignatureService
,I/iu.UploadsManager( 3158): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 4ms+4ms, total 30ms
,D/TimaKeyStoreProvider( 4815): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4815): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 3ms+3ms, total 30ms
D/MediaScanner( 2721): Skipping:
,D/MediaScanner( 2721): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 2721): processDirectory :  /storage/extSdCard
W/MediaScanner( 2721): Error opening directory, reason : Permission denied.
,W/MediaScanner( 2721): 7klwibgf7fxlKdCbid7
,D/dalvikvm( 4803): GC_CONCURRENT freed 3002K, 32% free 9566K/13916K, paused 4ms+2ms, total 29ms
D/dalvikvm( 4803): WAIT_FOR_CONCURRENT_GC blocked 22ms
,V/MediaScanner( 2721): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@423b7010
,V/MediaScanner( 2721): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@423b7010
V/MediaScanner( 2721):  prescan time: 64ms (DB items: 25)
V/MediaScanner( 2721):     scan time: 123ms (Caching mode: true), (makeEntry time: 91ms ~73%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 2721): postscan time: 14ms (bulkDeleter : 0), (delete DeadThumbnail time : 11ms)
V/MediaScanner( 2721):    total time: 201ms
V/MediaScanner( 2721): checked files: 6  directories : 19  (I: 0, U: 0)
,D/MediaScannerService( 2721): !@done scanning volume external
,D/MediaScannerService( 2721): send command to ssrm : REQ_DROP_CACHE
,I/ActivityManager( 2419): Killing 3708:com.sec.spp.push/u0a39 (adj 15): empty #43
,D/dalvikvm( 4815): GC_CONCURRENT freed 3011K, 32% free 9562K/13920K, paused 2ms+1ms, total 29ms
,D/dalvikvm( 4815): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/iu.UploadsManager( 3158): End new media; added: 0, uploading: 0, time: 110 ms
,I/DBG_DM  ( 4815): [][Line:95][onCreate] 
E/DBG_DM  ( 4815): BootingfileStream is null
,E/DBG_DM  ( 4815): xdmCreateBootingFilestream
,I/DBG_DM  ( 4815): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 4815): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 4815): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 4815): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/DBG_DM  ( 4815): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 4815): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 4815): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 4815): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 4815): [3.19.140541][Line:74][onCreate] XDMApplication Start ! - Fumo State
W/ContextImpl( 4815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 com.wssyncmldm.XDMApplication.onCreate:75 android.app.Instrumentation.callApplicationOnCreate:1013 android.app.ActivityThread.handleBindApplication:4790 
,I/DBG_DM  ( 4815): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 4815): [3.19.140541][Line:2764][xdmWakeLockAcquire] 
,I/DBG_DM  ( 4815): [3.19.140541][Line:2769][xdmWakeLockAcquire] m_WakeLock is acquire!!
,D/OverheatReceiver( 2578): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 2578): into the SAFE_MODE_ACTION
D/OverheatReceiver( 2578): VZW on -> change to Global UX [safe mode]
,I/DBG_DM  ( 4815): [3.19.140541][Line:2629][xdmGetRootingPrefValue] 0
,D/OverheatReceiver( 2578): isSafeMode = false
,I/DBG_DM  ( 4815): [3.19.140541][Line:118][xdmGetRootingFeature] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 4815): [3.19.140541][Line:2672][xdmGetRoamingPrefValue] 0
,I/DBG_DM  ( 4815): [3.19.140541][Line:265][xdmGetRoamingCheckFeature] Roaming Check : true
,I/DBG_DM  ( 4815): [3.19.140541][Line:2757][xdmGetValidationPrefValue] 0
,I/DBG_DM  ( 4815): [3.19.140541][Line:297][xdmGetValidationCheckFeature] validation Check On
,I/DBG_DM  ( 4815): [3.19.140541][Line:2714][xdmGetSSLPrefValue] 0
,I/DBG_DM  ( 4815): [3.19.140541][Line:278][xdmGetSSLCheckFeature] SSL Check On
,I/DBG_DM  ( 4815): [3.19.140541][Line:177][xdmAgentTaskHandler] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 4815): [3.19.140541][Line:152][xdmAgentSetSyncMode] nSync = 0
W/ContextImpl( 4815): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.wssyncmldm.ui.XUINotificationManager.BindService:74 com.wssyncmldm.ui.XUINotificationManager.xuiSetIndicator:114 com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler:181 
,I/DBG_DM  ( 4815): [3.19.140541][Line:395][xdmInitExternalStorageState] 
,D/HandsFreeActivity( 3449): shouldBeEnabled: locale=en-US
,D/HandsFreeActivity( 3449): Voice dialer enabled state: true
,I/DBG_DM  ( 4815): [3.19.140541][Line:450][xdmInitExternalStorageState] bExternalStorageAvailable [true]
,I/DBG_DM  ( 4815): [3.19.140541][Line:451][xdmInitExternalStorageState] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 4815): [3.19.140541][Line:2790][xdmWakeLockRelease] 
,I/DBG_DM  ( 4815): [3.19.140541][Line:2795][xdmWakeLockRelease] m_WakeLock is release!!
,I/DBG_DM  ( 4815): [3.19.140541][Line:223][onStartCommand] 
,I/DBG_DM  ( 4815): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,I/DBG_DM  ( 4815): [3.19.140541][Line:1951][xdbDMffs_Init] xdbDMffs_Init
,W/GAV2    ( 3449): Thread[Thread-132,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 3449): Thread[Thread-132,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/Tethering( 2419): No numeric data
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering( 2419): No numeric data
,E/Tethering( 2419): No numeric data
,E/Tethering( 2419): No numeric data
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering( 2419): No numeric data
,E/Tethering( 2419): No numeric data
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
,I/DBG_DM  ( 4815): [3.19.140541][Line:187][xdmAgentTaskHandler] XEVENT_PHONEBOOK_INITIALIZED
,D/dalvikvm( 2419): GC_EXPLICIT freed 604K, 20% free 24076K/29916K, paused 8ms+18ms, total 198ms
,I/DBG_DM  ( 4815): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4815): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 4815): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/SELinux ( 4840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4840):  
,I/dalvikvm( 2419): Jit: resizing JitTable from 8192 to 16384
,I/DBG_DM  ( 4815): [3.19.140541][Line:1331][onCallStateChanged] >>>>>>>>>>> onCallStateChanged
,E/Tethering( 2419): No numeric data
,E/Tethering( 2419): No numeric data
,E/Tethering( 2419): No numeric data
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/DBG_DM  ( 4815): [3.19.140541][Line:1356][onCallStateChanged] >>>>>>>>>>> CALL_STATE_IDLE
,E/Tethering( 2419): No numeric data
,I/ConnectivityService( 2419): defaultVal : 1, tetherEnabledInSettings : true
I/DBG_DM  ( 4815): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
I/DBG_DM  ( 4815): [3.19.140541][Line:51][onServiceConnected] 
I/SELinux ( 4840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4840):  
I/SELinux ( 4840):  
I/SELinux ( 4840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4840): >>>>> Normal User
E/dalvikvm( 4840): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 4840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4840): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4840): Cannot add TimaSignature Service, License check Failed
,V/VibratorService( 2419): hasVibrator - useVibetonz: false
D/ActivityThread( 4840): Added TimaKesytore provider
,D/dalvikvm( 4840): GC_CONCURRENT freed 2997K, 32% free 9573K/13920K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 4840): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2828): GC_CONCURRENT freed 1850K, 30% free 9782K/13908K, paused 1ms+2ms, total 25ms
,D/dalvikvm( 2828): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/UserAnalysis.PlaceProvider( 4840): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 4840): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 4840): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4840): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4840): Open Place.db in secure mode
,I/LockPatternUtils( 2828): isSmartCardAuthenticationAvailable: false
,I/SQLiteSecureOpenHelper( 4840): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4840): ...getDatabaseLocked(b,b,pwd)
I/SQLiteSecureOpenHelper( 4840): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4840): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 4840): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 4840): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4840): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4840): Open Place.db in secure mode
,V/VibratorService( 2419): hasVibrator - useVibetonz: false
,W/NotificationAccessSettings( 2828): Skipping notification listener service com.android.settings/com.android.settings.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/SQLiteSecureOpenHelper( 4840): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4840): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 4854): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4854):  
I/ActivityManager( 2419): Killing 3734:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,D/dalvikvm( 2828): GC_CONCURRENT freed 1505K, 26% free 10322K/13908K, paused 3ms+5ms, total 60ms
,I/SELinux ( 4854): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4854):  
I/SELinux ( 4854):  
,I/SELinux ( 4854): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4854): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4854): >>>>> Normal User
,E/dalvikvm( 4854): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 4854): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4854): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4854): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4854): Added TimaKesytore provider
,I/LockPatternUtils( 2828): isSmartCardAuthenticationAvailable: false
,D/dalvikvm( 4854): GC_CONCURRENT freed 2994K, 32% free 9570K/13916K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 4854): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/sCloudBackupApp( 4854): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 4867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4867):  
I/ActivityManager( 2419): Killing 3794:com.android.documentsui/u0a93 (adj 15): empty #43
,I/SELinux ( 4867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4867):  
I/SELinux ( 4867):  
,I/SELinux ( 4867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4867): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 4867): >>>>> Normal User
,E/dalvikvm( 4867): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 4867): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4867): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4867): Added TimaKesytore provider
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 0 sec
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/dalvikvm( 4867): GC_CONCURRENT freed 2998K, 32% free 9570K/13916K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 4867): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4880): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4880):  
,I/ActivityManager( 2419): Killing 3810:com.android.externalstorage/u0a9 (adj 15): empty #43
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10064
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10064
,W/ContextImpl( 2828): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
I/SettingSearch/SearchIntentReceiver( 2828): InitSerachDBThread thread end!
,I/SELinux ( 4880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4880):  
I/SELinux ( 4880):  
,I/SELinux ( 4880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4880): >>>>> Normal User
,E/dalvikvm( 4880): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 4880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4880): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4880): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4880): Added TimaKesytore provider
,D/dalvikvm( 4880): GC_CONCURRENT freed 3001K, 32% free 9572K/13920K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 4880): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/NPS_WSSNPS( 4880): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,D/NPS_WSSNPS( 4880): [] Service onCreate!!
W/BroadcastQueue( 2419): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.services.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/SELinux ( 4892): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4892):  
,D/NPS_WSSNPS( 4880): [] NpsServiceTask Start
,I/NPS_WSSNPS( 4880): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 4880): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 4880): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x422908e8
,D/dalvikvm( 4880): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x422908e8
,D/NPS_WSSNPS( 4880): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 4880): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 4880): [44.140541] IsRemain_AsyncBulkCheck
,I/SELinux ( 4892): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4892):  
I/SELinux ( 4892):  
,I/SELinux ( 4892): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4892): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/NPS_WSSNPS( 4880): [44.140541] IsRemain_Asyncing nothing
E/dalvikvm( 4892): >>>>> Normal User
,E/dalvikvm( 4892): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10067 ]
,E/SELinux ( 4892): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/NPS_WSSNPS( 4880): [44.140541] Service onDestroy
I/NPS_WSSNPS( 4880): [44.140541] smlBRConfigurationDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4880): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 4880): [44.140541] cpuBooster release : false
D/TimaKeyStoreProvider( 4892): in addTimaSignatureService
,D/NPS_WSSNPS( 4880): [44.140541] dsServerSocket close
,D/TimaKeyStoreProvider( 4892): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2419): Killing 3859:com.sec.android.omc/1000 (adj 15): empty #43
D/ActivityThread( 4892): Added TimaKesytore provider
,D/dalvikvm( 4892): GC_CONCURRENT freed 2999K, 32% free 9573K/13920K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 4892): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 4908): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4908):  
I/ActivityManager( 2419): Killing 3847:com.google.android.apps.docs/u0a94 (adj 15): empty #43
,I/SELinux ( 4908): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4908):  
I/SELinux ( 4908):  
,I/SELinux ( 4908): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4908): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4908): >>>>> Normal User
,E/dalvikvm( 4908): >>>>> com.samsung.android.app.airwakeupview [ userId:0 | appId:10069 ]
,E/SELinux ( 4908): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4908): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4908): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4908): Added TimaKesytore provider
,D/dalvikvm( 4908): GC_CONCURRENT freed 3003K, 32% free 9566K/13916K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 4908): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 4920): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4920):  
I/ActivityManager( 2419): Killing 3978:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SELinux ( 4920): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4920):  
I/SELinux ( 4920):  
,I/SELinux ( 4920): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4920): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4920): >>>>> Normal User
,E/dalvikvm( 4920): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 4920): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
W/ActivityThread( 2419): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/TimaKeyStoreProvider( 4920): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4920): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4920): Added TimaKesytore provider
,I/System.out( 2419): Thread-162(HTTPLog):isShipBuild true
,I/System.out( 2419): Thread-162(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 4920): GC_CONCURRENT freed 2989K, 32% free 9576K/13916K, paused 9ms+2ms, total 35ms
,D/dalvikvm( 4920): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/FileShare-Server( 4920): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 1 sec
,I/SELinux ( 4936): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4936):  
,I/ActivityManager( 2419): Killing 3991:com.sec.modem.settings/1000 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
I/SELinux ( 4936): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4936):  
I/SELinux ( 4936):  
I/SELinux ( 4936): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4936): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4936): >>>>> Normal User
E/dalvikvm( 4936): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10074 ]
E/SELinux ( 4936): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4936): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4936): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4936): Added TimaKesytore provider
,D/dalvikvm( 4936): GC_CONCURRENT freed 2986K, 32% free 9574K/13912K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 4936): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/AllShare(ASF-DMSLIB)( 4936): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10074
,I/SELinux ( 4948): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4948):  
I/ActivityManager( 2419): Killing 4003:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/SELinux ( 4948): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4948):  
I/SELinux ( 4948):  
,I/SELinux ( 4948): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4948): >>>>> Normal User
,E/dalvikvm( 4948): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 4948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4948): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4948): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4948): Added TimaKesytore provider
,D/dalvikvm( 4948): GC_CONCURRENT freed 3003K, 32% free 9566K/13916K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 4948): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/ContextImpl( 4948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/SELinux ( 4961): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4961):  
,I/SELinux ( 4961): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4961):  
I/SELinux ( 4961):  
,I/SELinux ( 4961): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4961): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4961): >>>>> Normal User
,E/dalvikvm( 4961): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 4961): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4961): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4961): Cannot add TimaSignature Service, License check Failed
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/ActivityThread( 4961): Added TimaKesytore provider
,D/dalvikvm( 4961): GC_CONCURRENT freed 3000K, 32% free 9572K/13920K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 4961): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/BluetoothBDAdrressReceiver( 4961): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4961): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 4961): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,D/BluetoothBDTestService( 2751): onCreate()
E/BluetoothBDTestService( 2751): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 2751): bd_address_path: /efs/bluetooth/bt_addr
,I/SELinux ( 4973): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4973):  
,E/BluetoothBDTestService( 2751): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/ActivityManager( 2419): Killing 4030:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10896K, paused 3ms+3ms, total 39ms
I/SELinux ( 4973): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4973):  
I/SELinux ( 4973):  
,I/SELinux ( 4973): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4973): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4973): >>>>> Normal User
,E/dalvikvm( 4973): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 4973): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4973): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+4ms, total 27ms
,D/TimaKeyStoreProvider( 4973): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4973): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 4973): GC_CONCURRENT freed 2998K, 32% free 9572K/13916K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 4973): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/SELinux ( 4985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4985):  
I/ActivityManager( 2419): Killing 3947:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131165197
I/SELinux ( 4985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4985):  
I/SELinux ( 4985):  
,I/SELinux ( 4985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4985): >>>>> Normal User
,E/dalvikvm( 4985): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131165194
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4985): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4985): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4985): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 2 sec
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm( 4985): GC_CONCURRENT freed 3006K, 32% free 9555K/13912K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 4985): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 4948): GC_CONCURRENT freed 433K, 14% free 12086K/13916K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 4948): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
E/PersonaManagerService( 2419): returning null in  getPersonasForUser
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/SELinux ( 4997): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4997):  
I/ActivityManager( 2419): Killing 4053:com.sec.phone/1001 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/SELinux ( 4997): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4997):  
I/SELinux ( 4997):  
,I/SELinux ( 4997): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4997): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4997): >>>>> Normal User
,E/dalvikvm( 4997): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 4997): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131165194
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4997): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4997): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4997): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm( 4997): GC_CONCURRENT freed 2988K, 32% free 9582K/13920K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 4997): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/        ( 4948): PNG_doEncode true 159, 159
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 4948): Resource data:2131165195
I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 4948): Resource data:2131165204
I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 4948): Resource data:2131165204
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4948): Resource data:2131165204
I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4069): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4069): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 4948): Resource data:2131099676
,I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10088
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 5011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5011):  
I/ActivityManager( 2419): Killing 4121:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
I/SELinux ( 5011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5011):  
I/SELinux ( 5011):  
,I/SELinux ( 5011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5011): >>>>> Normal User
,E/dalvikvm( 5011): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 5011): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
,D/TimaKeyStoreProvider( 5011): in addTimaSignatureService
,I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 5011): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5011): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/dalvikvm( 5011): GC_CONCURRENT freed 2997K, 32% free 9573K/13916K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 5011): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 5023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5023):  
I/ActivityManager( 2419): Killing 2977:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 5023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5023):  
I/SELinux ( 5023):  
,I/SELinux ( 5023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5023): >>>>> Normal User
,E/dalvikvm( 5023): >>>>> com.dropbox.android [ userId:0 | appId:10095 ]
,E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5023): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5023): Cannot add TimaSignature Service, License check Failed
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/ActivityThread( 5023): Added TimaKesytore provider
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 3 sec
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/dalvikvm( 5023): GC_CONCURRENT freed 3002K, 32% free 9565K/13916K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 5023): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/com.dropbox.android.service.DropboxNetworkReceiver( 5023): Setting receiver enabled: false
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
,I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/        ( 4948): PNG_doEncode true 106, 106
,I/com.dropbox.sync.android.a( 5023): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/com.dropbox.sync.android.aa( 5023): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800F armeabi-v7a; en_US))
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 5044): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5044):  
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/ActivityManager( 2419): Killing 4178:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43176940 u0 com.samsung.android.providers.context/.ContextService}
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
I/SELinux ( 5044): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5044):  
I/SELinux ( 5044):  
,I/SELinux ( 5044): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5044): >>>>> Normal User
,E/dalvikvm( 5044): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 5044): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5044): in addTimaSignatureService
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 5044): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5044): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
D/dalvikvm( 5044): GC_CONCURRENT freed 3006K, 32% free 9565K/13920K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 5044): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/elm:14132( 5044): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 5044): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5044): MDMBridge.setEnterpriseBridge()
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/elm:14132( 5044): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 5044): ElmAgentService : onCreate()
,D/elm:14132( 5044): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 5044): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 5044): BootCompletedState : startBootCompleted() call
,D/elm:14132( 5044): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 5059): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5059):  
,D/        ( 4948): PNG_doEncode true 106, 106
,D/elm:14132( 5044): MDMBridge.getAllLicenseInfoFromSDK()
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/elm:14132( 5044): Get License : 0
,D/elm:14132( 5044): ElmAgentService : onDestroy().
I/ActivityManager( 2419): Killing 4198:com.n7mobile.muzodajnia:main/u0a184 (adj 15): empty #43
,I/SELinux ( 5059): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5059):  
I/SELinux ( 5059):  
,I/SELinux ( 5059): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5059): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5059): >>>>> Normal User
,E/dalvikvm( 5059): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 5059): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 5059): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5059): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5059): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/System.out( 5023): Thread-362(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5023): Thread-362(ApacheHTTPLog):isShipBuild true
,I/System.out( 5023): Thread-362(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/dalvikvm( 5059): GC_CONCURRENT freed 2992K, 32% free 9576K/13916K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 5059): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 5073): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5073):  
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099648
I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/ActivityManager( 2419): Killing 4284:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 5073): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5073):  
I/SELinux ( 5073):  
,I/SELinux ( 5073): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5073): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5073): >>>>> Normal User
,E/dalvikvm( 5073): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,I/GAV2    ( 3449): Thread[GAThread,5,main]: No campaign data found.
,E/SELinux ( 5073): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/TimaKeyStoreProvider( 5073): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5073): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5073): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/dalvikvm( 5073): GC_CONCURRENT freed 2996K, 32% free 9565K/13912K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 5073): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/CameraApp( 5073): CameraApp.onCreate()... mFeature : null
,I/testFeature( 5073): Feature.Feature(context)
I/testFeature( 5073): Feature.readInternalDefaultXml()
,I/testFeature( 5073): ResetFeatureValue
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/CameraFirmware_broadcast( 5073): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 5073): CameraApp.getAppFeature()...
,I/SELinux ( 5087): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5087):  
I/ActivityManager( 2419): Killing 4271:com.sec.dsm.system/1000 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 4 sec
,I/SELinux ( 5087): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5087):  
I/SELinux ( 5087):  
,I/SELinux ( 5087): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5087): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5087): >>>>> Normal User
,E/dalvikvm( 5087): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 5087): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4948): Resourc,e data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131099671
I/AMMetaDataParserService( 4948): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,D/TimaKeyStoreProvider( 5087): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5087): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5087): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5087): GC_CONCURRENT freed 3005K, 32% free 9555K/13912K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 5087): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/PackageIntentReceiver( 5087): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 5087): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 2419): Killing 4297:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,D/dalvikvm( 4948): GC_CONCURRENT freed 1822K, 21% free 12312K/15480K, paused 3ms+5ms, total 43ms
,D/dalvikvm( 4948): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131165216
,I/SELinux ( 5100): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5100):  
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/        ( 4948): PNG_doEncode true 80, 80
,I/AMMetaDataParserService( 4948): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,I/SELinux ( 5100): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5100):  
I/SELinux ( 5100):  
,I/SELinux ( 5100): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5100): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5100): >>>>> Normal User
,E/dalvikvm( 5100): >>>>> com.google.android.gm [ userId:0 | appId:10106 ]
,E/SELinux ( 5100): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,D/TimaKeyStoreProvider( 5100): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5100): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5100): Added TimaKesytore provider
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429071
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429071
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429071
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297114
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wifi_settings
,I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429073
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429073
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/bluetooth_settings
,I/AMMetaDataParserService( 4948): getResourceTypeNameid
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429095
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429071
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297114
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429146
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298419
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/dalvikvm( 5100): GC_CONCURRENT freed 2991K, 32% free 9579K/13920K, paused 6ms+2ms, total 35ms
D/dalvikvm( 5100): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298419
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298419
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429103
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SoundSettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429103
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DisplaySettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429099
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429099
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429109
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429113
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DockSettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429113
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297804
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429155
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429055
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429055
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429055
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429054
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429054,
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429055
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429055
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
,I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429055
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429080
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296750
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SecuritySettings
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429050
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296750
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296750
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429114
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429114
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298587
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429114
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298587
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429118
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429107
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429150
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429152
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429092
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429152
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429150
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297938
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429150
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297938
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429088
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429090
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429094
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131296695
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429148
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429148
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429046
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429144
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429135
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429213
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429151
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429128
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429112
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429112
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4948): Resource data:2131299843
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429112
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429112
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429149
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429113
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4948): Resource data:1
W/ResourceType( 4948): No package identifier when getting name for resource number 0x00000001
W/System.err( 4948): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 4948): 	at android.content.res.Resources.getResourceName(Resources.java:2988)
W/System.err( 4948): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 4948): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 4948): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4948): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4948): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429126
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4948): Resource data:2131301070
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297804
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429130
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429120
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429121
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429133
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4948): Resource data:2131300118
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429123
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429187
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429124
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429218
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429155
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429126
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429126
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429126
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429126
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$OneHandEditMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429100
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429212
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429099
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4948): Resource data:2131301505
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429130
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429130
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4948): Resource data:2131302906
W/GAV2    ( 5100): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429106
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2130838226
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4948): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429143
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429136
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:2131429136
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429104
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429139
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429140
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429080
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131302078
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429080
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131302078
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429080
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131302107
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429086
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429044
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429049
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429122
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131297804
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429078
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429131
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
,I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429131
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429122
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2130838278
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 4948): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2130838278
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 4948): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429129
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429129
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131165371
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:xml/searchable
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429051
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429114
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4948): Resource data:2131298587
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4948): getResourceTypeNamestring
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429125
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429185
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429147
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429147
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429203
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429203
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429075
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429169
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429138
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2130838226
,I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4948): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4948): Resource data:2131429119
I/AMMetaDataParserService( 4948): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 4948): getResourceTypeNameid
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,D/dalvikvm( 3158): GC_CONCURRENT freed 1508K, 20% free 12029K/14884K, paused 7ms+6ms, total 72ms
,I/SELinux ( 5125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5125):  
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131034120
,I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/SELinux ( 5125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5125):  
I/SELinux ( 5125):  
I/SELinux ( 5125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
E/SELinux ( 5125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4948): Resource data:2131034113
E/dalvikvm( 5125): >>>>> Normal User
,E/dalvikvm( 5125): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,E/SELinux ( 5125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5125): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5125): Cannot add TimaSignature Service, License check Failed
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/ActivityThread( 5125): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131034113
I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/dalvikvm( 2419): GC_EXPLICIT freed 1764K, 19% free 24381K/29916K, paused 6ms+17ms, total 181ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/Gmail   ( 5100): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 5 sec
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/Gmail   ( 5100): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5100): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5100): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/dalvikvm( 5125): GC_CONCURRENT freed 3001K, 32% free 9569K/13916K, paused 3ms+1ms, total 44ms
,D/dalvikvm( 5125): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4948): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4948): Resource data:Loop for running activityalias.DialShortcut
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131034112
,I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,I/SELinux ( 5143): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5143):  
,D/dalvikvm( 5023): GC_CONCURRENT freed 1946K, 24% free 10693K/13984K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 5023): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
I/ActivityManager( 2419): Killing 4314:com.sec.factory/1000 (adj 15): empty #43
,I/System.out( 5023): pool-4-thread-1 calls detatch()
,I/SELinux ( 5143): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5143):  
I/SELinux ( 5143):  
,I/SELinux ( 5143): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5143): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5143): >>>>> Normal User
,E/dalvikvm( 5143): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,D/dalvikvm( 1922): GC_EXPLICIT freed 45K, 13% free 9502K/10896K, paused 3ms+3ms, total 40ms
,E/SELinux ( 5143): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,D/TimaKeyStoreProvider( 5143): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 5143): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5143): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 25ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,D/dalvikvm( 4948): GC_CONCURRENT freed 2008K, 22% free 12276K/15632K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 5143): GC_CONCURRENT freed 3005K, 32% free 9565K/13916K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 5143): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
,I/knox    ( 5143): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131034113
,W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,I/knox    ( 5143): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/knox    ( 5143): KNOXAgentService : onCreate()
,D/knox    ( 5143): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5143): KNOXAgentService. startJobThread() start
,D/knox    ( 5143): KNOXAgentService. JobThread()
D/knox    ( 5143): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5143): KNOXAgentService. startJobThread() wait
,I/SELinux ( 5157): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5157):  
,D/knox    ( 5143): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 5143): KNOXAgentService : onDestroy().
,D/knox    ( 5143): ModuleBase.cancelAllAlarmManageModule()
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 5157): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5157):  
I/SELinux ( 5157):  
,I/SELinux ( 5157): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5157): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5157): >>>>> Normal User
,E/dalvikvm( 5157): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 5157): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/TimaKeyStoreProvider( 5157): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5157): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5157): Added TimaKesytore provider
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131034116
I/AMMetaDataParserService( 4948): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131099668
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/dalvikvm( 5157): GC_CONCURRENT freed 2996K, 32% free 9566K/13912K, paused 3ms+1ms, total 29ms
D/dalvikvm( 5157): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/AMMetaDataParserService( 4948): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 4948): Resource data:2131099650
I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,E/KnoxSetupWizardClient( 5157): isShipMode : 1
,I/KnoxSetupWizardClient( 5157): onReceive : android.intent.action.BOOT_COMPLETED
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,D/ShortcutReceiver2( 5157):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
I/yash    ( 5157): setDisableWidget>size:0
,W/System.err( 5157): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 5157): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5157): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5157): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5157): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5157): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 5157): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
W/System.err( 5157): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
,W/System.err( 5157): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5157): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5157): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
,W/System.err( 5157): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5157): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
,W/System.err( 5157): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 5157): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/SELinux ( 5170): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5170):  
I/ActivityManager( 2419): Killing 3141:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #43
,D/dalvikvm( 4948): GC_FOR_ALLOC freed 761K, 24% free 12013K/15632K, paused 34ms, total 34ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/SELinux ( 5170): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5170):  
I/SELinux ( 5170):  
,I/SELinux ( 5170): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5170): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5170): >>>>> Normal User
,E/dalvikvm( 5170): >>>>> com.LocalFota [ userId:0 | appId:10113 ]
E/SELinux ( 5170): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4948): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/TimaKeyStoreProvider( 5170): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5170): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5170): Added TimaKesytore provider
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserSe,rvice( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131099667,
,I/AMMetaDataParserService( 4948): getResourceName:com.android.email:xml/email_assistant_menu,
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml,
,D/        ( 4948): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4948): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559,
,D/dalvikvm( 5170): GC_CONCURRENT freed 2994K, 32% free 9565K/13912K, paused 2ms+1ms, total 29ms
,D/dalvikvm( 5170): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 5170): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 5170): [20.0040.140326][Line:27][<init>] First call
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 5170): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 5170): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 5170): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 5170): [20.0040.140326][Line:41][onReceive] nStatus : -1
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 5185): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5185):  
I/ActivityManager( 2419): Killing 4374:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/SELinux ( 5185): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5185):  
I/SELinux ( 5185):  
,I/SELinux ( 5185): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5185): >>>>> Normal User
,E/dalvikvm( 5185): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,D/TimaKeyStoreProvider( 5185): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5185): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5185): Added TimaKesytore provider
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 4948): Resource data:2131099689
I/AMMetaDataParserService( 4948): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4948): Resource data:2131099685
I/AMMetaDataParserService( 4948): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 4948): getResourceTypeNamexml
I/AMMetaDataParserService( 4948): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4948): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4948): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 4948): Resource data:2130903052
,I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 4948): getResourceTypeNamelayout
I/AMMetaDataParserService( 4948): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4948): Resource data:2131034112
I/AMMetaDataParserService( 4948): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 4948): getResourceTypeNamexml
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 6 sec
,D/dalvikvm( 5185): GC_CONCURRENT freed 2997K, 32% free 9574K/13920K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 5185): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/        ( 4948): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4948): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/StatusChecker( 5185): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 4948): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/SELinux ( 5199): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5199):  
I/ActivityManager( 2419): Killing 3828:com.fmm.dm/1000 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 4405:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,I/SELinux ( 5199): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5199):  
I/SELinux ( 5199):  
,I/SELinux ( 5199): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5199): >>>>> Normal User
,E/dalvikvm( 5199): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10135 ]
,E/SELinux ( 5199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5199): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5199): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5199): Added TimaKesytore provider
,D/dalvikvm( 5199): GC_CONCURRENT freed 2995K, 32% free 9573K/13920K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 5199): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/QuickConnect( 5199): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 5199): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 5199): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10135
,V/QuickConnect( 5199): SconnectManager.getInstance - () return existing instance null
,W/ContextImpl( 5199): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,I/QuickConnect( 5199): PeriphService.onCreate - [START]
,I/SELinux ( 5211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5211):  
,I/QuickConnect( 5199): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 5199): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 5199): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 5199): PeriphService.setState - 0 >> 1
,V/QuickConnect( 5199): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 5199): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@422ad920
,I/QuickConnect[1.1][2] ( 5199): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@422998f0
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 5199): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 5199): BluetoothHelper.BluetoothHelper - 
,I/SELinux ( 5211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5211):  
I/SELinux ( 5211):  
,I/SELinux ( 5211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5211): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5211): >>>>> Normal User
,E/dalvikvm( 5211): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 5211): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5211): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 5199): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,D/TimaKeyStoreProvider( 5211): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5211): Added TimaKesytore provider
,V/QuickConnect[1.1][2] ( 5199): BleHelper.BleHelper - Constructor
,E/QuickConnect[1.1][2] ( 5199): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 5199): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@422c49c8
D/BluetoothRadioManager( 5199):  addRadioReference enabled = false
,D/BluetoothRadioManager( 5199):  BLE Radio count is : 1
,D/BluetoothRadioManager( 5199): addRadioReference()  registerRadioClient mUUID = 5b0246d0-0fb9-4aa6-8996-3dc8a1493826
,D/BluetoothManagerService( 2419): foregroundUser: 0
,E/BluetoothManagerService( 2419): Package is exist.
,D/BluetoothRadioManager( 5199): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 5199): BleHelper.mSearchWearable - true
I/bluedroid( 4069): update_radio_count
,D/BluetoothAdapterState( 4069): CURRENT_STATE=ON, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 4069): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 4069): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 4069): enable
E/bt-btif ( 4069): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 4069): btif_sock_init, radio_req:1, rfc_init:1, vhci_init:1
,D/BluetoothAdapterState( 4069): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
I/BluetoothAdapterState( 4069): Bluetooth adapter radio state changed: 14
D/BluetoothAdapterService( 4069): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4069): updateAdapterState state is 14
,D/BluetoothAdapterService( 4069): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 4069): Autoconnection is available 
D/BluetoothManagerService( 2419): Broadcasting Radio() to 1 Radio Mgr receivers.
,D/BluetoothAdapterService( 4069): updateAdapterState prevState = 12newState = 14
I/BluetoothAdapterState( 4069): Entering On State from state = 12
,D/BluetoothRadioManager( 5199): onBTRadioStateChange:  up = true
D/dalvikvm( 5211): GC_CONCURRENT freed 3005K, 32% free 9565K/13920K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5211): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/BezelQuickConnect( 5211): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 5211): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 5211): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
V/QuickConnect[1.1][2] ( 5199): UpnpHelper.UpnpHelper - 
,I/BezelQuickConnect( 5211): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 5211): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/QuickConnect[1.1][2] ( 5199): JmdnsHelper.JmdnsHelper - Constructor
,E/QuickConnect[1.1][2] ( 5199): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@42311350
,W/ContextImpl( 5211): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
V/QuickConnect[1.1][2] ( 5199): P2pHelper.P2pHelper - EXEC
V/PhoneStatusBar( 2578): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
D/QuickConnect[1.1][2] ( 5199): p2pHelperWorkThread.p2pHelperWorkThread - created!
E/QuickConnect[1.1][2] ( 5199): BleHelper.onGattServiceStateChange - Radio turned on
,E/NetworkSettingsReceiver( 3964): onReceive: android.intent.action.BOOT_COMPLETED
,D/STATUSBAR-PhoneStatusBar( 2578): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
D/QuickConnect[1.1][2] ( 5199): WifiHelper.WifiHelper -  -- 
,D/WifiDisplayAdapter( 2419): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/BroadcastQueue( 2419): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/QuickConnect[1.1][2] ( 5199): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 5199): BluetoothOppActionHelper.BluetoothOppActionHelper - 
,V/QuickConnect[1.1][2] ( 5199): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
,V/QuickConnect[1.1][2] ( 5199): SmartHomeActionHelper.SmartHomeActionHelper - --
,V/QuickConnect[1.1][2] ( 5199): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
,V/QuickConnect[1.1][2] ( 5199): BluetoothActionHelper.BluetoothActionHelper - 
,I/SELinux ( 5228): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5228):  
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/BluetoothHeadset( 5199): BTStateChangeCB is registed
,E/BluetoothHeadset( 5199): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@422b07b0
,V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
,V/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 5199): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 5199): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.changeResponseSetting - changed: 2
,V/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
,I/SELinux ( 5228): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5228):  
I/SELinux ( 5228):  
,I/SELinux ( 5228): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/QuickConnect[1.1][2] ( 5199): WifiHelper.isEnableMobileAP - HOTSPOT Disabled
E/SELinux ( 5228): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5228): >>>>> Normal User
,E/dalvikvm( 5228): >>>>> com.sec.android.app.camera [ userId:0 | appId:10149 ]
,V/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.updateRespTarget - 
,E/SELinux ( 5228): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.initializeAdvData - name: S5mini-1(8)
D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.initializeAdvData - name selected: S5mini-1(8)
,V/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getMyMobileNumber - 
,D/TimaKeyStoreProvider( 5228): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5228): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5228): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getMyMobileNumber - null 
D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = 0
,D/QuickConnect[1.1][2] ( 5199): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
W/QuickConnect[1.1][2] ( 5199): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
D/QuickConnect[1.1][2] ( 5199): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5199): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5199): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5199): PeriphService.registerUserReceiver - mIsUserReceiver == false
I/QuickConnect[1.1][2] ( 5199): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 5199): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 5199): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
D/QuickConnect[1.1][2] ( 5199): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 5199): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5199): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothA2dp( 5199): Proxy object connected
D/WifiP2pService( 2419): InactiveState{ what=139287 }
D/WifiP2pService( 2419): P2pEnabledState{ what=139287 }
,D/WifiP2pService( 2419): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 5199): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/QuickConnect[1.1][2] ( 5199): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothInputDevice( 5199): Proxy object connected
,D/QuickConnect[1.1][2] ( 5199): HidProfile.onServiceConnected - Bluetooth service connected
,D/QuickConnect[1.1][2] ( 5199): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/dalvikvm( 5228): GC_CONCURRENT freed 3004K, 32% free 9567K/13916K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 5228): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/dalvikvm( 5228): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,I/ActivityManager( 2419): Killing 3469:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5242): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5242):  
,I/QuickConnect[1.1][2] ( 5199): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 5199): registerCallback()
,D/BluetoothGattServer( 5199): registerCallback() - UUID=5d48c9e0-21b7-4519-9d90-ddfaf13fb03f
,D/BtGatt.GattService( 4069): registerServer() - UUID=5d48c9e0-21b7-4519-9d90-ddfaf13fb03f
D/BtGatt.btif( 4069): btif_gatts_register_app
D/BtGatt.btif( 4069): btgatts_handle_event: Event 2000
E/bt-btif ( 4069): register application first_unuse rcb_idx = 0
D/BtGatt.btif( 4069): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 4069): onServerRegistered() - UUID=5d48c9e0-21b7-4519-9d90-ddfaf13fb03f, serverIf=5
,D/BluetoothGattServer( 5199): onServerRegistered() - status=0 serverIf=5
V/QuickConnect[1.1][2] ( 5199): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5199): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
V/QuickConnect[1.1][2] ( 5199): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
D/QuickConnect[1.1][2] ( 5199): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5199): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5199): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5199): BleHelper.startScan - shouldScanBleFg = false
,I/SELinux ( 5242): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5242):  
I/SELinux ( 5242):  
,I/SELinux ( 5242): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5242): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5242): >>>>> Normal User
,E/dalvikvm( 5242): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 5242): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5242): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5242): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5242): Added TimaKesytore provider
,D/dalvikvm( 5242): GC_CONCURRENT freed 2990K, 32% free 9574K/13916K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 5242): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 7 sec
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 5259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5259):  
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 5259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5259):  
I/SELinux ( 5259):  
I/SELinux ( 5259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5259): >>>>> Normal User
,E/dalvikvm( 5259): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5259): in addTimaSignatureService
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5259): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5259): Added TimaKesytore provider
,I/SELinux ( 5278): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5278):  
,I/ActivityManager( 2419): Killing 4439:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 4425:com.samsung.klmsagent/u0a18 (adj 15): empty #44
,I/SELinux ( 5278): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5278):  
I/SELinux ( 5278):  
,I/SELinux ( 5278): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5278): >>>>> Normal User
,E/dalvikvm( 5278): >>>>> com.android.exchange [ userId:0 | appId:10158 ]
,E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5278): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5278): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5278): Added TimaKesytore provider
,D/dalvikvm( 5259): GC_CONCURRENT freed 3001K, 32% free 9569K/13920K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 5259): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Process ( 5242): Sending signal. PID: 5242 SIG: 9
,D/BadgeProvider( 5259): onCreate
,D/BadgeProvider( 5259): DatabaseHelper
,I/ActivityManager( 2419): Process com.android.email (pid 5242) (adj 9) has died.
,D/dalvikvm( 5278): GC_CONCURRENT freed 2991K, 32% free 9575K/13912K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 5278): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 5291): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5291):  
,I/SELinux ( 5296): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5296):  
,I/SELinux ( 5291): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5291):  
I/SELinux ( 5291):  
,I/SELinux ( 5291): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5291): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5291): >>>>> Normal User
,E/dalvikvm( 5291): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 5291): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9502K/10896K, paused 4ms+4ms, total 45ms
,I/SELinux ( 5296): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5296):  
I/SELinux ( 5296):  
,I/SELinux ( 5296): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5296): >>>>> Normal User
,E/dalvikvm( 5296): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 5296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5291): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5291): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5291): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5296): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 4ms+4ms, total 36ms
,D/TimaKeyStoreProvider( 5296): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5296): Added TimaKesytore provider
I/ActivityManager( 2419): Waited long enough for: ServiceRecord{433598b0 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/ActivityManager( 2419): Killing 4453:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 3ms+4ms, total 32ms
,D/dalvikvm( 5291): GC_CONCURRENT freed 3002K, 32% free 9568K/13920K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 5291): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 5296): GC_CONCURRENT freed 2981K, 32% free 9578K/13912K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 5296): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 5318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5318):  
,I/ActivityManager( 2419): Killing 4467:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 5318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5318):  
I/SELinux ( 5318):  
,I/SELinux ( 5318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5318): >>>>> Normal User
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,E/dalvikvm( 5318): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5318): Added TimaKesytore provider
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 8 sec
,I/Process ( 5278): Sending signal. PID: 5278 SIG: 9
,D/SensorService( 2419):   0.2 -0.0 9.9
,D/BadgeProvider( 5259): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/dalvikvm( 5318): GC_CONCURRENT freed 3013K, 32% free 9558K/13920K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 5318): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/BadgeProvider( 5259): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5259): sendNotify, [notify] : null
D/BadgeProvider( 5259): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5259): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5259): update, [UpdateCount] : 1
,D/Launcher.Model( 2782): reloadBadges entered.
I/ActivityManager( 2419): Process com.android.exchange (pid 5278) (adj 9) has died.
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 5340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5340):  
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 287, prevStep = 4, currStep = 4
,I/SELinux ( 5340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5340):  
I/SELinux ( 5340):  
,I/SELinux ( 5340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5340): >>>>> Normal User
,E/dalvikvm( 5340): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5340): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5340): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5340): Added TimaKesytore provider
,D/dalvikvm( 5340): GC_CONCURRENT freed 2994K, 32% free 9565K/13912K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 5340): WAIT_FOR_CONCURRENT_GC blocked 18ms
V/AlarmManager( 2419): waitForAlarm result :4
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2419): GC_EXPLICIT freed 1234K, 19% free 24354K/29916K, paused 9ms+12ms, total 200ms
,I/SELinux ( 5361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5361):  
,D/NotiRemoteService( 5340): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 5340): connectToPeelService 0
,W/ContextImpl( 5340): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:68 tv.peel.samsung.widget.NotiRemoteService.a:554 
,D/NotiRemoteService( 5340): onServiceOn() mServiceState = 1
,D/NotiRemoteService( 5340): Send action to self com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 5340): action com.peel.widget.notification.SERVICE_BINDED
,D/dalvikvm( 2721): GC_EXPLICIT freed 940K, 29% free 9987K/13904K, paused 3ms+5ms, total 46ms
,D/NotiRemoteService( 5340): feature is Off. Stop service
,D/NotiRemoteService( 5340): Send action to self com.peel.widget.notification.STOP_PROCESS
I/SELinux ( 5361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5361):  
I/SELinux ( 5361):  
,I/SELinux ( 5361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5361): >>>>> Normal User
,E/dalvikvm( 5361): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/NotiRemoteService( 5340): action com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5340): onDestroy()
,D/NotiRemoteService( 5340): mOrientationChangeReceier was not registered
,I/iu.UploadsManager( 3158): End new media; added: 0, uploading: 0, time: 375 ms
,D/TimaKeyStoreProvider( 5361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5361): Added TimaKesytore provider
,D/dalvikvm( 5361): GC_CONCURRENT freed 2998K, 32% free 9566K/13916K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 5361): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/SmartcardService( 5361): main Received broadcast
,V/SmartcardService( 5361): Starting smartcard service after boot completed
I/ActivityManager( 2419): Killing 4480:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
,I/SELinux ( 5375): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5375):  
,I/SELinux ( 5375): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5375):  
I/SELinux ( 5375):  
,I/SELinux ( 5375): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5375): >>>>> Normal User
,E/dalvikvm( 5375): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,E/SELinux ( 5375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5375): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5375): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5375): Added TimaKesytore provider
,D/dalvikvm( 5375): GC_CONCURRENT freed 3018K, 32% free 9548K/13916K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 5375): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/ContextImpl( 5375): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5387):  
,I/SELinux ( 5387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5387):  
I/SELinux ( 5387):  
,I/SELinux ( 5387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5387): >>>>> Normal User
,E/dalvikvm( 5387): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 9 sec
,D/TimaKeyStoreProvider( 5387): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5387): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5387): GC_CONCURRENT freed 2999K, 32% free 9573K/13920K, paused 5ms+3ms, total 36ms
,D/dalvikvm( 5387): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SELinux ( 5400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5400):  
I/ActivityManager( 2419): Killing 4495:com.sec.pcw.device/1000 (adj 15): empty #43
,I/SELinux ( 5400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5400):  
I/SELinux ( 5400):  
,I/SELinux ( 5400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5400): >>>>> Normal User
,E/dalvikvm( 5400): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5400): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5400): Added TimaKesytore provider
,D/dalvikvm( 5400): GC_CONCURRENT freed 3020K, 32% free 9548K/13920K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 5400): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Intent to TravelDirActivity( 5400): inside TravelBroadcastReceiver
,I/SELinux ( 5412): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5412):  
I/ActivityManager( 2419): Killing 4389:com.android.chrome/u0a85 (adj 15): empty #43
,I/SELinux ( 5412): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5412):  
I/SELinux ( 5412):  
,I/SELinux ( 5412): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5412): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5412): >>>>> Normal User
,E/dalvikvm( 5412): >>>>> com.sec.android.daemonapp [ userId:0 | appId:10173 ]
,E/SELinux ( 5412): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5412): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5412): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5412): Added TimaKesytore provider
,D/dalvikvm( 5412): GC_CONCURRENT freed 2989K, 32% free 9578K/13916K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 5412): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/GAV2    ( 5100): Thread[GAThread,5,main]: No campaign data found.
,D/comsamsungapp( 5412): [MSC_Daemon]>>> KWCP:218 [0:0] KWeather Provider Created
,D/comsamsungapp( 5412): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WCP:1080 [0:0] Provider Created
,D/comsamsungapp( 5412): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5412): [MSC_Daemon]>>> CCP:223 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 5412): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WNCP:204 [0:0] WeatherNewsJP Provider Created
,D/comsamsungapp( 5412): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 5412): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:false
D/comsamsunglog( 5412): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5412): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5412): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5412): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:48 [0:0] WeatherClockService start : 
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10173
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1452527860942
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1452531000000
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
,D/daemonapp( 5412): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1452531000000
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 9
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1452531000000
,D/daemonapp( 5412): [MSC_Daemon]>>> WCS:40 [0:0] onStartcommand()
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WCS:63 [0:0] CP Name cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5412): [MSC_Daemon]>>> WCS:82 [0:0] td null
,D/comdaemonstockapp( 5412): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 5412): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 5427): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5427):  
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 10 sec
I/SELinux ( 5427): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5427):  
I/SELinux ( 5427):  
,I/SELinux ( 5427): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5427): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5427): >>>>> Normal User
,E/dalvikvm( 5427): >>>>> com.gameloft.android.GloftGF2H [ userId:0 | appId:10179 ]
,E/SELinux ( 5427): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5427): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5427): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5427): Added TimaKesytore provider
,D/dalvikvm( 5427): GC_CONCURRENT freed 2994K, 32% free 9566K/13912K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 5427): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 5440): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5440):  
I/ActivityManager( 2419): Killing 4521:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/SELinux ( 5440): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5440):  
I/SELinux ( 5440):  
,I/SELinux ( 5440): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5440): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5440): >>>>> Normal User
,E/dalvikvm( 5440): >>>>> com.gameloft.android.GloftKLMF [ userId:0 | appId:10180 ]
,E/SELinux ( 5440): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5440): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5440): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5440): Added TimaKesytore provider
,D/dalvikvm( 5440): GC_CONCURRENT freed 3008K, 32% free 9558K/13912K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 5440): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SELinux ( 5453): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5453):  
,I/ActivityManager( 2419): Killing 4572:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 5453): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5453):  
I/SELinux ( 5453):  
,I/SELinux ( 5453): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5453): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5453): >>>>> Normal User
,E/dalvikvm( 5453): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
,E/SELinux ( 5453): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5453): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5453): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5453): Added TimaKesytore provider
,D/PowerManagerService( 2419): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2419): lcd : 2 +
,D/RampAnimator( 2419): Light Animator Finished currentValue=2
D/dalvikvm( 5453): GC_CONCURRENT freed 3002K, 32% free 9568K/13920K, paused 2ms+3ms, total 27ms
D/dalvikvm( 5453): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/lights  ( 2419): lcd : 2 -
,I/SELinux ( 5468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5468):  
I/ActivityManager( 2419): Killing 4720:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9502K/10896K, paused 4ms+5ms, total 47ms
,I/SELinux ( 5468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5468):  
I/SELinux ( 5468):  
,I/SELinux ( 5468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5468): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5468): >>>>> Normal User
,E/dalvikvm( 5468): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 5468): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 3ms+3ms, total 35ms
,D/TimaKeyStoreProvider( 5468): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5468): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5468): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 5468): GC_CONCURRENT freed 2998K, 32% free 9576K/13920K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 5468): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/dalvikvm( 5468): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 5468): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 5468): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 5468): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0037
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 11 sec
,W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5468): Link of class 'Ldqp;' failed
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5468): Link of class 'Ldqp;' failed
,I/dalvikvm( 5468): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 5468): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 5468): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5468): Link of class 'Ldqp;' failed
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5468): Link of class 'Ldqp;' failed
I/dalvikvm( 5468): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 5468): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
,W/dalvikvm( 5468): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5468): Link of class 'Ldqp;' failed
W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 5468): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5468): Link of class 'Ldqp;' failed
I/dalvikvm( 5468): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 5468): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5468): Link of class 'Lax;' failed
E/dalvikvm( 5468): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 5468): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5468): Link of class 'Laz;' failed
E/dalvikvm( 5468): Could not find class 'az', referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 5468): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 5468): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
,W/dalvikvm( 5468): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 5468): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 5468): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 5468): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 5468): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5468): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 5468): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5468): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5468): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 5468): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5468): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 5468): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 5468): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 5468): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 5468): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 5468): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 5468): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 5468): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 5468): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 5468): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 5468): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 5468): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5468): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5468): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 5468): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5468): Link of class 'Lax;' failed
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 5468): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5468): Link of class 'Laz;' failed
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 5468): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422aba80
,D/dalvikvm( 5468): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422aba80
,D/SensorService( 2419):   0.2 -0.0 9.9
,I/dalvikvm( 5468): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 5468): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 5468): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5468): MmsConfig.loadMmsSettings
I/Babel_SMS( 5468): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 5468): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5468): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5468): MmsConfig.loadFromResources
,E/Babel_SMS( 5468): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5468): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 5468): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5468): Link of class 'Lfzc;' failed
E/dalvikvm( 5468): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 5468): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 5468): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 5468): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 5468): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 5468): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 5468): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 5468): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 5468): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5468): Link of class 'Lfzc;' failed
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
W/ServiceManager( 2419): Permission failure: com.samsung.permission.SSENSOR from uid=10109 pid=5468
D/PermissionCache( 2419): checking com.samsung.permission.SSENSOR for uid=10109 => denied (315 us)
E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 5468): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 5468): GC_CONCURRENT freed 1794K, 23% free 10857K/13996K, paused 4ms+4ms, total 37ms
D/dalvikvm( 5468): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 5468): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/Babel_Crash( 5468): startup - clean
,I/dalvikvm( 5468): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 5468): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 5468): deleted: false for 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 5468): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 5468): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5468): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 5468): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 5468): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5468): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 5468): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 5468): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 5468): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 5468): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 5468): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 5468): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 5468): VFY: replacing opcode 0x6e at 0x0074
,E/dalvikvm( 5468): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 5468): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 5468): VFY: replacing opcode 0x1f at 0x0014
,I/vclib   ( 5468): onServiceConnected
,W/Babel   ( 5468): Attempted to change video mute state without an active call.
,I/SELinux ( 5491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5491):  
I/ActivityManager( 2419): Killing 4736:com.osp.app.signin/u0a44 (adj 15): empty #43
,I/SELinux ( 5491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5491):  
I/SELinux ( 5491):  
,I/SELinux ( 5491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5491): >>>>> Normal User
,E/dalvikvm( 5491): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5491): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5491): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5491): Added TimaKesytore provider
,D/dalvikvm( 5491): GC_CONCURRENT freed 3007K, 32% free 9563K/13920K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 5491): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5468): GC_CONCURRENT freed 1007K, 17% free 11890K/14252K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 5468): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 5468): GC_FOR_ALLOC freed 508K, 18% free 12399K/15020K, paused 38ms, total 38ms
,D/dalvikvm( 5468): GC_FOR_ALLOC freed 1759K, 24% free 12770K/16612K, paused 32ms, total 32ms
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 12 sec
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,E/dalvikvm( 5491): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 5491): VFY: replacing opcode 0x22 at 0x0000
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,W/dalvikvm( 5491): Unable to resolve superclass of Lal; (749)
,W/dalvikvm( 5491): Link of class 'Lal;' failed
E/dalvikvm( 5491): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm( 5491): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5491): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5491): Link of class 'Lan;' failed
E/dalvikvm( 5491): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
D/dalvikvm( 5491): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 5491): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5491): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 5491): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 5491): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5491): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 5491): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 5491): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm( 5491): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5491): Link of class 'Lal;' failed
,D/dalvikvm( 5491): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5491): Unable to resolve superclass of Lan; (749)
,W/dalvikvm( 5491): Link of class 'Lan;' failed
D/dalvikvm( 5491): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 5491): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 5491): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5491): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5491): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5491): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5491): VFY: unable to resolve instance field 36
,D/dalvikvm( 5491): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 5491): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5491): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5491): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5491): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5491): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5491): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42345a78
,D/dalvikvm( 5491): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42345a78
,D/dalvikvm( 5491): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42345a78, skipping init
,D/dalvikvm( 5491): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42345a78
D/dalvikvm( 5491): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42345a78
,V/JNIHelp ( 5491): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5491): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42345a78
,D/dalvikvm( 5491): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42345a78
D/dalvikvm( 5491): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42345a78
,D/dalvikvm( 5491): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42345a78
,I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5491): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5491): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 5491): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5491): VFY: replacing opcode 0x71 at 0x004e
,I/ProviderInstaller( 5491): Installed default security provider GmsCore_OpenSSL
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/dalvikvm( 5491): DexOpt: --- BEGIN 'ads93790834.jar' (bootstrap=0) ---
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4069): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4069): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/YouTube MDX( 5491): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 5518): DexOpt: load 4ms, verify+opt 18ms, 194052 bytes
,D/dalvikvm( 5491): DexOpt: --- END 'ads93790834.jar' (success) ---
,D/dalvikvm( 5491): DEX prep '/data/data/com.google.android.youtube/cache/ads93790834.jar': unzip in 0ms, rewrite 136ms
,D/dalvikvm( 5491): GC_CONCURRENT freed 1857K, 23% free 10778K/13980K, paused 5ms+5ms, total 50ms
,D/dalvikvm( 5491): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5491): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
,W/dalvikvm( 5491): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
,W/dalvikvm( 5491): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5491): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 5491): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5491): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5491): Found 10012
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,I/System.out( 5491): Thread-506(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5491): Thread-506(ApacheHTTPLog):isShipBuild true
,I/System.out( 5491): Thread-506(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/ActivityManager( 2419): Killing 4754:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 13 sec
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 3158): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 3158): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 3158): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3158): VFY: replacing opcode 0x62 at 0x0021
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 3158): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3158): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3158): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3158): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 3158): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
,I/dalvikvm( 3158): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 3158): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,D/FileApkUtils( 3158): Spent 54ms computing apk sha1.
,D/FileApkUtils( 3158): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 3158): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 3158): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 3158): Beginning GMS chimera module scan
,W/InstanceID/Rpc( 3158): Found 10012
,D/ChimeraCfgMgr( 3158): Beginning module configuration check
,D/ChimeraCfgMgr( 3158): Module APKs unchanged, check complete
,I/System.out( 5491): Thread-506 calls detatch()
,E/dalvikvm( 3158): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 3158): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 3158): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 3158): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 3158): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 3158): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 3158): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 3158): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 3158): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 3158): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 3158): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 3158): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 3158): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 3158): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/dalvikvm( 2735): GC_CONCURRENT freed 1632K, 21% free 11482K/14532K, paused 6ms+6ms, total 73ms
,E/dalvikvm( 2735): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 2735): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 2735): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 2735): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2735): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
E/dalvikvm( 3158): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 3158): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 3158): VFY: replacing opcode 0x1f at 0x000e
W/dalvikvm( 2735): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2735): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 2735): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 2735): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 2735): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2735): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 2735): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 3158): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 3158): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 3158): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 3158): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 3158): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 3158): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 3158): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3158): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3158): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 3158): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 3158): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/GCM     ( 3158): COMPAT: Multi user not supported
,I/CheckinService( 3158): Checkin interval check for package: unspecified last checkin: 1452482426840 min interval config: 0 actual interval: 45437784
,I/GCoreUlr( 3158): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 2735): DispatchingService.onCreate()
,D/dalvikvm( 2850): GC_EXPLICIT freed 165K, 25% free 10459K/13888K, paused 6ms+8ms, total 61ms
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
,I/CheckinService( 3158): Disabling old GoogleServicesFramework version
I/dalvikvm( 2850): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 2850): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0059
,W/dalvikvm( 3158): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3158): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/dalvikvm( 2850): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 2850): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0022
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 3158): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 3158): Got an BootCompleted event.
,D/BootCompletedReceiver( 3158): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 3158): onCreate
,I/CheckinService( 3158): Checking schedule, now: 1452527864811 next: 1453040769761
,I/CheckinService( 3158): active receiver: disabled
,D/SystemUpdateService( 3158): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 3158): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 3158): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 3158): VFY: replacing opcode 0x6e at 0x0409
,V/AuthZen ( 3158): Handling intent: android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
,I/SystemUpdateService( 3158): cancelUpdate (empty URL)
,I/SystemUpdateService( 3158): active receiver: disabled
,D/GCM     ( 2850): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 2850): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,W/dalvikvm( 3158): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x001c
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 2850): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0053
,D/SystemUpdateService( 3158): onDestroy
,W/Auth    ( 2850): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/AuthZenEventHandler( 3158): Handling event: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/BaseAppContext( 3158): Using Auth Proxy for data requests.
,I/dalvikvm( 3158): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 3158): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 3158): VFY: replacing opcode 0x6e at 0x002f
,I/AuthZen ( 3158): Fetching signing key...
,I/GCM     ( 2850): GCM config loaded
,I/AuthZen ( 3158): Signing key fetched successfully!
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 14 sec
,W/BaseAppContext( 3158): Using Auth Proxy for data requests.
,D/dalvikvm( 2850): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 2419): GC_EXPLICIT freed 1971K, 19% free 24480K/29916K, paused 8ms+17ms, total 197ms
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/AuthZenTransactionCache( 3158): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 3158): Clearing transaction cache
,D/dalvikvm( 3158): GC_CONCURRENT freed 1749K, 20% free 12346K/15388K, paused 11ms+17ms, total 90ms
,I/dalvikvm( 2850): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x001f
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
V/AlarmManager( 2419): waitForAlarm result :4
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 2850): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 2850): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 2850): VFY: replacing opcode 0x6e at 0x0041
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/PersistentNotificationBroadcastReceiver( 2735): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/SELinux ( 5617): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5617):  
,I/SELinux ( 5617): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5617):  
I/SELinux ( 5617):  
,I/SELinux ( 5617): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5617): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5617): >>>>> Normal User
,E/dalvikvm( 5617): >>>>> com.sec.spp.push [ userId:0 | appId:10039 ]
,E/SELinux ( 5617): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5617): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5617): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5617): Added TimaKesytore provider
,D/dalvikvm( 5617): GC_CONCURRENT freed 2994K, 32% free 9570K/13916K, paused 6ms+2ms, total 29ms
,D/dalvikvm( 5617): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/SPPClientService( 5617): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5617): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 5617): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 5617): [SystemStateMoniter] Current Time : 67973
D/SPPClientService( 5617): PushLog.txt file is not deleted.
D/SPPClientService( 5617): PushLog.txt file is not deleted.
,D/SPPClientService( 5617): ============PushLog. stop!
,D/Volley  ( 3750): [183] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3750): [176] DiskBasedCache.clear: Cache cleared.
,D/ConnectivityService( 2419): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,D/WearableService( 2735): callingUid 10012, callindPid: 2735
,D/SensorService( 2419):   0.3 -0.0 9.9
,E/MDM     ( 2735): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 3158): Restart initialization of location
,D/AuthorizationBluetoothService( 2850): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2850): Proximity feature is not enabled.
,W/GCoreFlp( 2735): No location to return for getLastLocation()
,W/FusedLocationProvider( 2735): location=null
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager( 2419): waitForAlarm result :4
,E/MDM     ( 2735): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 3158): Restart initialization of location
,D/AuthorizationBluetoothService( 2850): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2850): Proximity feature is not enabled.
,W/GCoreFlp( 2735): No location to return for getLastLocation()
,W/FusedLocationProvider( 2735): location=null
V/AlarmManager( 2419): waitForAlarm result :4
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 5647): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5647):  
,I/SELinux ( 5647): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5647):  
I/SELinux ( 5647):  
,I/SELinux ( 5647): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5647): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5647): >>>>> Normal User
,E/dalvikvm( 5647): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5647): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5647): in addTimaSignatureService
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 15 sec
,D/TimaKeyStoreProvider( 5647): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5647): Added TimaKesytore provider
,D/dalvikvm( 5647): GC_CONCURRENT freed 3014K, 32% free 9559K/13920K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 5647): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/KLMS-2.3.201 : ( 5647): KLMSValidator() : checkQATesting()
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/KLMS-2.3.201 : ( 5647): ELMReceiver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : com.sec.esdk.elm.action.DEACTIVE_PACKAGE , timestamp: 1452527866293
,I/KLMS-2.3.201 : ( 5647): ELMReceiver() : ELM_DEACTIVATE_LICENSE
,I/KLMS-2.3.201 : ( 5647): KnoxLicenseServicesImpl() : deactivateLicense()
,I/KLMS-2.3.201 : ( 5647): DeviceServices() : Deactivation initiator=1001 | packageName=ELM
,I/KLMS-2.3.201 : ( 5647): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager( 2419): Killing 3885:com.android.mms/u0a49 (adj 15): empty #43
,D/CountryDetector( 2419): No listener is left
,V/AlarmManager( 2419): waitForAlarm result :4
,I/HomeSyncInstallReceiver( 2756): This pkg do not need BT addr. Do nothing
,I/SELinux ( 5660): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5660):  
,I/SELinux ( 5660): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5660):  
I/SELinux ( 5660):  
,I/SELinux ( 5660): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5660): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5660): >>>>> Normal User
,E/dalvikvm( 5660): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 5660): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5660): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5660): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5660): Added TimaKesytore provider
,D/dalvikvm( 5660): GC_CONCURRENT freed 3001K, 32% free 9563K/13916K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 5660): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SELinux ( 5675): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5675):  
,I/ActivityManager( 2419): Killing 4776:com.sec.android.app.safetyassurance/u0a51 (adj 15): empty #43
,I/SELinux ( 5675): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5675):  
I/SELinux ( 5675):  
,I/SELinux ( 5675): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5675): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5675): >>>>> Normal User
,E/dalvikvm( 5675): >>>>> com.samsung.groupcast [ userId:0 | appId:10015 ]
,E/SELinux ( 5675): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5675): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5675): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5675): Added TimaKesytore provider
,D/dalvikvm( 5675): GC_CONCURRENT freed 3005K, 32% free 9566K/13920K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5675): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/GroupCast_FileTools( 5675): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 5675): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.mv.player
W/System.err( 5675): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 5675): 	at com.samsung.groupcast.application.App.preLoadShareVideoCheck(App.java:325)
W/System.err( 5675): 	at com.samsung.groupcast.application.App.onCreate(App.java:145)
W/System.err( 5675): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5675): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5675): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5675): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 5675): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5675): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5675): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 5675): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 5675): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 5675): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
,W/System.err( 5675): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5675): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5675): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 5675): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5675): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 5675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5675): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5675): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 5675): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5675): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 5675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 5675): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 5687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5687):  
I/ActivityManager( 2419): Killing 2828:com.android.settings/1000 (adj 15): empty #43
,I/SELinux ( 5687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5687):  
I/SELinux ( 5687):  
,I/SELinux ( 5687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5687): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5687): >>>>> Normal User
,E/dalvikvm( 5687): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 5687): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5687): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5687): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5687): Added TimaKesytore provider
,D/dalvikvm( 5687): GC_CONCURRENT freed 3002K, 32% free 9565K/13916K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 5687): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 5700): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5700):  
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 16 sec
,I/SELinux ( 5700): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5700):  
I/SELinux ( 5700):  
,I/SELinux ( 5700): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5700): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5700): >>>>> Normal User
,E/dalvikvm( 5700): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 5700): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 5700): Enabling JNI app bug workarounds for target SDK version 8...
I/ActivityManager( 2419): Killing 4803:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5700): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5700): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5700): Added TimaKesytore provider
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5700): GC_CONCURRENT freed 3001K, 32% free 9571K/13920K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 5700): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/PCWCLIENTTRACE_PushUtil( 5700): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5700): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5700): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 5700): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5700): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5700): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/SELinux ( 5713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5713):  
I/ActivityManager( 2419): Killing 3449:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty #43
,I/SELinux ( 5713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5713):  
I/SELinux ( 5713):  
,I/SELinux ( 5713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5713): >>>>> Normal User
,E/dalvikvm( 5713): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
,E/SELinux ( 5713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5713): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5713): Added TimaKesytore provider
,D/dalvikvm( 5713): GC_CONCURRENT freed 2993K, 32% free 9569K/13912K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 5713): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 2419): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2419): Nap time...
,D/PowerManagerService( 2419): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2419): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2419): Going to sleep due to screen timeout...
D/PowerManagerService( 2419): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/DisplayPowerController( 2419): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2419): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2419): unregisterListener ::   
I/SurfaceFlinger( 1921): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2419): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2419): !@ElectronBeam entry
,D/SensorManager( 2419): unregisterListener ::   
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = 0
,W/System.err( 5713): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5713): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 5713): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 5713): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 5713): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
,W/System.err( 5713): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5713): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5713): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5713): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 5713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5713): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5713): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 5713): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5713): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5713): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5713): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 5713): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 5713): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5713): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 5713): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 5713): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 5713): 	... 21 more
,D/GalaxyFinderApplication( 5713): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 5713): [Slink platform] use state of slink location service is [false] to [true]
,I/SELinux ( 5727): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5727):  
,I/ActivityManager( 2419): Killing 4840:com.samsung.android.intelligenceservice/u0a5 (adj 15): empty #43
D/lights  ( 2419): lcd : 0 +
,D/lights  ( 2419): lcd : 0 -
D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2419): WindowOrientationListener disabled
D/SensorService( 2419): AutoRotationSensor::activate (ident=0x7bd9ad58, enabled=0)
,I/Sensors ( 2419): HAL: batch Dry Run is complete
D/PowerManagerService( 2419): blankAllDisplays() is called.
D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2419): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2419): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/input/input0/enabled: 0
D/KeyguardViewMediator( 2578): onScreenTurnedOff(3)
D/SensorManager( 2419): unregisterListener ::   
D/InputDispatcher( 2419): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2419): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2419): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2419): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2419): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/PowerManagerService( 2419): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x40987550
,D/LockPatternUtils( 2578): isPcwEnable = 10
,I/SELinux ( 5727): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5727):  
I/SELinux ( 5727):  
,I/SELinux ( 5727): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5727): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5727): >>>>> Normal User
,E/dalvikvm( 5727): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 5727): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5727): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5727): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5727): Added TimaKesytore provider
,D/KeyguardViewMediator( 2578): setting alarm to turn off keyguard, seq = 1
,D/LightsService( 2419): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2419) 
,D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2419): turn on LED for fully charged
D/VibratorService( 2419): JNI vibratorOff()
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 17 sec
,D/SurfaceControl( 2419): Excessive delay in blankDisplay() while turning screen off: 207ms
I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2419): !@[s] autosuspend_autosleep_enable done
D/STATUSBAR-NotificationService( 2419): ACTION_SCREEN_OFF
D/PowerManagerService( 2419): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 209ms
D/PowerManagerService( 2419): SecHardwareInterface.setBatteryADC : false
D/LightsService( 2419): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2419) 
D/LightsService( 2419): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
I/PowerManagerService( 2419): [PWL] Off : 0s ago
I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=21214)
,I/PowerManagerService( 2419): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/SecExternalDisplayIntents_Java( 2419): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2419): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2419): Bridge Server is not available
,D/PersonaManagerService( 2419): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2419): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2578): makeExpandedInvisible
D/PhoneStatusBarView( 2578): marqueeStatusBar:121, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2578):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
E/NfcService( 2756): callback == null
,D/dalvikvm( 5727): GC_CONCURRENT freed 2996K, 32% free 9568K/13916K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 5727): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = 0
,D/QuickConnect[1.1][2] ( 5199): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5199): BleHelper.shouldScanBleBg - 
D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/SensorManager( 2419): unregisterListener ::   
D/QuickConnect[1.1][2] ( 5199): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
V/QuickConnect[1.1][2] ( 5199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b07b0
,D/QuickConnect[1.1][2] ( 5199): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5199): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5199): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5199): stopLeScan()
D/lights  ( 2419): led_pattern : 5 +
,D/QuickConnect[1.1][2] ( 5199): BleHelper.stopScan - call stopLeScan() complete
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2419): led_pattern : 5 -
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 2419): [PWL] sb release: PowerManagerService.Broadcasts
,W/ContextImpl( 5727): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 5748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5748):  
,E/Device Type Shared Preferences( 5727): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 5727): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 5727): ContentProvider is not null
,W/ResourceType( 5727): No package identifier when getting value for resource number 0x00000000
,I/System.out( 5727): resource Id::2131361807
,I/SELinux ( 5748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5748):  
I/SELinux ( 5748):  
,I/SELinux ( 5748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5748): >>>>> Normal User
,E/dalvikvm( 5748): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 5748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5748): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5748): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5748): Added TimaKesytore provider
,D/com.sec.android.app.shealth.SHealthApplication( 5727): Success during batch insertion in App registry:0
,D/dalvikvm( 5748): GC_CONCURRENT freed 3000K, 32% free 9567K/13920K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 5748): WAIT_FOR_CONCURRENT_GC blocked 26ms
,V/MediaPlayer( 5727): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1925): decode(26, 30565892, 48105)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
,V/StagefrightPlayer( 1925): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 18 sec
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b5058, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 5727): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1925): decode(26, 30501792, 10421)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30501792, 10421)
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 1925): notify(0x444f7d70, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444f7d70, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
,V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 6, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f7d70, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1925): decode(26, 34044116, 34198)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f9f30, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(60, 30449260, 7405)
,V/MediaPlayerService( 1925): decode(26, 30449260, 7405)
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b3048, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 5727): decode(61, 34134748, 5555)
,V/MediaPlayerService( 1925): decode(27, 34134748, 5555)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 34134748, 5555)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44150cf8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
,V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x44150cf8, 200, 973, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44150cf8, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x44150cf8, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
,V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x44150cf8, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
,V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44150cf8, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x44150cf8, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): addBatteryData
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44150cf8, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(62, 26954540, 5085)
,V/MediaPlayerService( 1925): decode(26, 26954540, 5085)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf9d0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 6, 0, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
,V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf9d0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf9d0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(63, 26959684, 21552)
,V/MediaPlayerService( 1925): decode(25, 26959684, 21552)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(25, 26959684, 21552)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
,V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
I/AudioPlayer( 1925): First fillBuffer call!!
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
,V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(64, 34130460, 4230)
V/MediaPlayerService( 1925): decode(26, 34130460, 4230)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
,V/StagefrightPlayer( 1925): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
,V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
V/MediaPlayerService( 1925): wait for playback complete
I/AudioPlayer( 1925): First fillBuffer call!!
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
,V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 5727): decode(65, 26923896, 9400)
V/MediaPlayerService( 1925): decode(27, 26923896, 9400)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): constructor
,V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
,V/StagefrightPlayer( 1925): setDataSource(27, 26923896, 9400)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 8, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1925): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 6, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/SELinux ( 5807): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5807):  
,I/ActivityManager( 2419): Killing 4867:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 4854:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #44
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
,V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
,V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x442b15b0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9502K/10896K, paused 4ms+5ms, total 48ms
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
,V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(66, 30512272, 44276)
,V/MediaPlayerService( 1925): decode(27, 30512272, 44276)
,V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
,V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 30512272, 44276)
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 8, 0, 0)
I/SELinux ( 5807): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5807):  
I/SELinux ( 5807):  
V/AudioCache( 1925): ignored
,I/SELinux ( 5807): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,E/SELinux ( 5807): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5807): >>>>> Normal User
,E/dalvikvm( 5807): >>>>> com.policydm [ userId:0 | appId:1000 ]
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
,E/SELinux ( 5807): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
,V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 3ms+4ms, total 38ms
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,D/dalvikvm( 5748): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422a3710, skipping init
I/SecureStorage( 5748): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 5748): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5748
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/SecureStorage( 5748): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 3ms+4ms, total 37ms
,D/TimaKeyStoreProvider( 5807): in addTimaSignatureService
,I/SecureStorage( 5748): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5748
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,D/TimaKeyStoreProvider( 5807): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5807): Added TimaKesytore provider
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x44188388, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(67, 30472480, 29256)
,V/MediaPlayerService( 1925): decode(26, 30472480, 29256)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 30472480, 29256)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
,V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
,V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
,V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
,V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,D/dalvikvm( 5807): GC_CONCURRENT freed 3010K, 32% free 9559K/13920K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 5807): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/MediaPlayer( 5727): decode(68, 34078380, 52024)
,V/MediaPlayerService( 1925): decode(26, 34078380, 52024)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/SELinux ( 5835): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5835):  
,I/ActivityManager( 2419): Killing 4880:com.wssnps/1000 (adj 15): empty #43
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/SELinux ( 5835): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5835):  
I/SELinux ( 5835):  
,I/SELinux ( 5835): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5835): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
E/dalvikvm( 5835): >>>>> Normal User
,E/dalvikvm( 5835): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
,E/SELinux ( 5835): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
V/AudioCache( 1925): wait - success
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(69, 30556608, 9226)
,V/MediaPlayerService( 1925): decode(26, 30556608, 9226)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
,V/StagefrightPlayer( 1925): setDataSource(26, 30556608, 9226)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
,V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
,I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
D/TimaKeyStoreProvider( 5835): in addTimaSignatureService
I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 200, 973, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 5, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 1, 0, 0)
V/AudioCache( 1925): prepared
,V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
,V/StagefrightPlayer( 1925): start
,V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,D/TimaKeyStoreProvider( 5835): Cannot add TimaSignature Service, License check Failed
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ActivityThread( 5835): Added TimaKesytore provider
,I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1925): notify(0x444cf010, 6, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
,V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
,V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1925): addBatteryData
V/AudioCache( 1925): wait - success
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444cf010, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/MediaPlayer( 5727): decode(70, 26989388, 4509)
,V/MediaPlayerService( 1925): decode(27, 26989388, 4509)
V/MediaPlayerService( 1925): player type = 3
V/AwesomePlayer( 1925): setDefault
,V/AwesomePlayer( 1925): constructor
V/AwesomePlayer( 1925): setDefault
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): StagefrightPlayer
V/AwesomePlayer( 1925): setListener
V/StagefrightPlayer( 1925): initCheck
V/AwesomePlayer( 1925): setAudioSink
V/StagefrightPlayer( 1925): setDataSource(27, 26989388, 4509)
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
V/AwesomePlayer( 1925): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1925): mBitrate = -1 bits/sec
V/AwesomePlayer( 1925): current audio track index (0) is added to vector
V/AwesomePlayer( 1925): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1925): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1925): prepare
V/AwesomePlayer( 1925): prepareAsync
V/MediaPlayerService( 1925): wait for prepare
V/AwesomePlayer( 1925): onPrepareAsyncEvent
I/SecMediaClock( 1925): SecMediaClock constructor
I/SecMediaClock( 1925): reset
V/AwesomePlayer( 1925): initAudioDecoder
V/AwesomePlayer( 1925): checkOffloadExceptions is true
,I/OMXCodec( 1925): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1925): mDispatchers.add
,I/OMXCodec( 1925): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1925): finishAsyncPrepare_l
V/AwesomePlayer( 1925): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 200, 973, 0)
,V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 5, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 1, 0, 0)
V/AudioCache( 1925): prepared
V/AudioCache( 1925): wait - success
V/MediaPlayerService( 1925): start
V/StagefrightPlayer( 1925): start
V/AwesomePlayer( 1925): play
V/AwesomePlayer( 1925): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1925): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1925):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1925): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1925): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 6, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): addBatteryData
,V/MediaPlayerService( 1925): wait for playback complete
,V/AwesomePlayer( 1925): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1925): onCheckAudioStatus
V/AwesomePlayer( 1925): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1925): onStreamDone
V/AwesomePlayer( 1925): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1925): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 2, 0, 0)
V/AudioCache( 1925): playback complete - thread will wake up later
V/AwesomePlayer( 1925): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 7, 0, 0)
V/AudioCache( 1925): ignored
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1925): wait - success
V/AwesomePlayer( 1925): addBatteryData
V/StagefrightPlayer( 1925): reset
,V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1925): notify(0x444f8df0, 8, 0, 0)
V/AudioCache( 1925): ignored
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1925): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1925): reset out
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1925): SecMediaClock destructor
V/AwesomePlayer( 1925): mSecMediaClock clear
V/StagefrightPlayer( 1925): ~StagefrightPlayer
,V/StagefrightPlayer( 1925): reset
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AwesomePlayer( 1925): destructor
V/AwesomePlayer( 1925): reset_l()
V/AwesomePlayer( 1925): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1925): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1925): mAudioTrackVector clear
V/AwesomePlayer( 1925): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1925): mSecMediaClock clear
,V/AlarmManager( 2419): waitForAlarm result :12
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5835): GC_CONCURRENT freed 2990K, 32% free 9569K/13912K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 5835): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/linker  ( 5375): libcordon.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/dalvikvm( 5375): No JNI_OnLoad found in /system/lib/libcordon.so 0x42293508, skipping init
,D/dalvikvm( 5807): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422a16b0, skipping init
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 19 sec
,I/SecureStorage( 5807): [INFO]: SPID(0x00000000)Processing data
,D/ActivityThread( 5835): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5835): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5835): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,I/SELinux ( 5867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5867):  
,I/SELinux ( 5867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5867):  
I/SELinux ( 5867):  
,I/SELinux ( 5867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5867): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5867): >>>>> Normal User
,E/dalvikvm( 5867): >>>>> com.osp.app.signin [ userId:0 | appId:10044 ]
,E/SELinux ( 5867): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5867): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5867): Added TimaKesytore provider
,D/dalvikvm( 5867): GC_CONCURRENT freed 2987K, 32% free 9579K/13912K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 5867): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/ActivityManager( 2419): Killing 4892:com.samsung.android.app.accesscontrol/u0a67 (adj 15): empty #43
,I/SA      ( 5867): [SSP] onCreated
,I/SA      ( 5867): [TPM] There is no property file
,I/SA      ( 5867): [SCU] isHaveSA() - false
I/SA      ( 5867): [TPM] getModelProperty : null
,I/SA      ( 5867): [TPM] getCSCProperty : null
,I/SA      ( 5867): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5867): [DM] init START
,I/SA      ( 5867): [DM] This device is not a Vodafone
I/SA      ( 5867): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5867): support phone number id : false
I/SA      ( 5867): [DM] init END
,I/SA      ( 5867): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5867): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager( 2419): Killing 4908:com.samsung.android.app.airwakeupview/u0a69 (adj 15): empty #43
,I/SELinux ( 5885): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5885):  
,I/SELinux ( 5885): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5885):  
I/SELinux ( 5885):  
,I/SELinux ( 5885): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5885): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5885): >>>>> Normal User
,E/dalvikvm( 5885): >>>>> com.android.mms [ userId:0 | appId:10049 ]
,E/SELinux ( 5885): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5885): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5885): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5885): Added TimaKesytore provider
,D/dalvikvm( 5885): GC_CONCURRENT freed 2997K, 32% free 9571K/13920K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 5885): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/dalvikvm( 5885): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)PID: 5748, TID: 5759
I/SecureStorage( 1965): [INFO]: SPID(0x00000005)Credentials: uid 1000, gid 1000, pid 5807
,I/SecureStorage( 1965): [INFO]: SPID(0x00000005)Received function mask & code: 00000106
,D/Mms/MmsApp( 5885): [start]    onCreate()
,D/Mms/TelephonyPermission( 5885): start operation mode monitor
,D/Mms/TelephonyPermission( 5885): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 5885): isDefault true
,D/Mms/MmsApp( 5885): onCreate() com.android.mms
,D/Mms/MmsConfig( 5885): before partial update
,D/Mms/MmsConfig( 5885): Load Resize quality : 80
,D/Mms/MmsConfig( 5885):  enable multiwindow = false
,E/Mms/MessageUtils( 5885): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 5885): updateCountryIso : update country iso info 
,D/CountryDetector( 2419): The first listener is added
,I/SecureStorage( 5748): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 5748): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 5748): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 5748): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 5748): Open platform.db in secure mode
,D/TP/MmsSmsProvider( 2751): match 13:Elapsed time : 1.668 ms
,D/Mms/Conversation( 5885): init()
,D/TP/MmsSmsProvider( 2751): match 12:Elapsed time : 1.899 ms
,D/TP/MmsSmsProvider( 2751): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 2751): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/TP/MmsSmsProvider( 2751): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 2751): need read changed broadcast:false
,I/SQLiteSecureOpenHelper( 5748): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 5748): ...getDatabaseLocked(b,b,pwd)
,I/Mms/ReservationManager( 5885): ReservationManager()
,I/Mms/ReservationManager( 5885): resetAfterConnected()
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 20 sec
,D/dalvikvm( 2419): GC_EXPLICIT freed 2546K, 17% free 24869K/29916K, paused 5ms+14ms, total 165ms
,D/TP/MmsSmsProvider( 2751): match 7:Elapsed time : 171.317 ms
,I/Mms/ReservationManager( 5885): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 5885): [end]    onCreate()
,D/Mms/PackageInstallReceiver( 5885): loadAuthorityPref(): sEnableAuthority = true
,D/Mms/DownloadManager( 5885): Service state changed: Bundle[mParcelledData.dataSize=740]
D/Mms/DownloadManager( 5885): roaming ------> false
,D/Mms/DownloadManager( 5885): mAutoDownload ------> true
,I/SELinux ( 5907): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5907):  
I/ActivityManager( 2419): Killing 4920:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,I/SELinux ( 5907): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5907):  
I/SELinux ( 5907):  
,I/SELinux ( 5907): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5907): >>>>> Normal User
,E/dalvikvm( 5907): >>>>> com.android.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5907): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5907): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5907): Added TimaKesytore provider
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{433499d0 u0 com.sec.knox.seandroid/.service.SEAndroidLauncher}
,D/dalvikvm( 5907): GC_CONCURRENT freed 2983K, 32% free 9584K/13916K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 5907): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 5920): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5920):  
I/ActivityManager( 2419): Killing 4936:com.sec.android.nearby.mediaserver/u0a74 (adj 15): empty #43
,I/SELinux ( 5920): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5920):  
I/SELinux ( 5920):  
,I/SELinux ( 5920): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5920): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5920): >>>>> Normal User
,E/dalvikvm( 5920): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 5920): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5920): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5920): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5920): Added TimaKesytore provider
,I/SecureStorage( 1965): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000005)PID: 5807, TID: 5827
,D/dalvikvm( 5920): GC_CONCURRENT freed 2982K, 32% free 9587K/13920K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 5920): WAIT_FOR_CONCURRENT_GC blocked 13ms
,W/ContextImpl( 4948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/Icing.InternalIcingCorporaProvider( 5920): Updating corpora: A: com.example.hello, C: MAYBE
,I/SELinux ( 5934): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5934):  
,I/SecureStorage( 5807): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SELinux ( 5934): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5934):  
I/SELinux ( 5934):  
,I/SELinux ( 5934): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5934): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5934): >>>>> Normal User
,E/dalvikvm( 5934): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 5934): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 5934): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5934): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5934): Added TimaKesytore provider
,D/LocationManagerService( 2419): getProviders()=[passive]
,D/dalvikvm( 5934): GC_CONCURRENT freed 3003K, 32% free 9566K/13920K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 5934): WAIT_FOR_CONCURRENT_GC blocked 36ms
V/AlarmManager( 2419): waitForAlarm result :4
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/CapabilityManagerService New( 5934): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,D/PackageIntentReceiver( 5087): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5087): Not GearManger package! 
,I/SELinux ( 5954): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5954):  
I/ActivityManager( 2419): Killing 4961:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #43
,D/dalvikvm( 5375): GC_CONCURRENT freed 2272K, 27% free 10255K/13912K, paused 3ms+16ms, total 56ms
,I/SELinux ( 5954): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5954):  
I/SELinux ( 5954):  
,I/SELinux ( 5954): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5954): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5954): >>>>> Normal User
,E/dalvikvm( 5954): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
,E/SELinux ( 5954): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5954): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5954): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5954): Added TimaKesytore provider
,D/dalvikvm( 5954): GC_CONCURRENT freed 2989K, 32% free 9574K/13916K, paused 4ms+1ms, total 30ms
,D/dalvikvm( 5954): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 21 sec
,D/MagazineService Version( 5954): Magazine-Channel: 13
,D/MagazineService Version( 5954): Magazine-Provider: 13
,D/MagazineService Version( 5954): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5954): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5954): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/MagazineService::MagazineService( 5954): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 5968): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5968):  
,D/MagazineService::MagazineService( 5954): [onHandleIntent] Send broadcast to (com.example.hello).
,I/ActivityManager( 2419): Killing 4973:com.blurb.checkout/u0a79 (adj 15): empty #43
,I/SELinux ( 5968): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5968):  
I/SELinux ( 5968):  
,I/SELinux ( 5968): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5968): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5968): >>>>> Normal User
,E/dalvikvm( 5968): >>>>> com.google.android.apps.plus [ userId:0 | appId:10133 ]
,E/SELinux ( 5968): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5968): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5968): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5968): Added TimaKesytore provider
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{4326b048 u0 com.samsung.android.sconnect/.periph.PeriphService}
,D/dalvikvm( 5968): GC_CONCURRENT freed 2986K, 32% free 9586K/13920K, paused 4ms+1ms, total 24ms
,D/dalvikvm( 5968): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 5988): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5988):  
,I/ActivityManager( 2419): Killing 4985:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/iu.UploadsManager( 5968): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
I/SELinux ( 5988): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5988):  
I/SELinux ( 5988):  
,I/SELinux ( 5988): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5988): >>>>> Normal User
E/dalvikvm( 5988): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 5988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5988): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5988): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5988): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 5920): UpdateCorporaTask done [took 1012 ms] updated apps [took 1012 ms] 
,I/ActivityManager( 2419): Killing 4997:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5988): GC_CONCURRENT freed 2997K, 32% free 9566K/13912K, paused 3ms+2ms, total 40ms
,D/dalvikvm( 5988): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/iu.Environment( 5968): update battery state; isPlugged? true*
,I/iu.Environment( 5968): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 5968): Start processing all media
,I/iu.UploadsManager( 5968): End new media; added: 0, uploading: 0, time: 169 ms
,I/iu.FingerprintManager( 5968): Start processing media store URI: content://media/external/images/media
,D/KidsPlatformStub( 5988): Package not found : com.sec.android.app.kidshome
,I/iu.FingerprintManager( 5968): Start processing media store URI: content://media/external/video/media
,I/Mms/MmsApp( 5885):  start initViewCache mms
,I/SELinux ( 6002): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6002):  
,I/iu.FingerprintManager( 5968): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5968): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5968): Finished generating fingerprints; 0.070 seconds
,I/iu.FingerprintManager( 5968):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ActivityManager( 2419): Killing 5011:com.samsung.android.app.colorblind/1000 (adj 15): empty #43
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 22 sec
I/PowerManagerService( 2419): [PWL] Off : 5s ago
I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=26215)
I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3158, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=263)
,I/SELinux ( 6002): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6002):  
I/SELinux ( 6002):  
,I/SELinux ( 6002): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6002): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6002): >>>>> Normal User
,E/dalvikvm( 6002): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6002): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6002): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6002): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6002): Added TimaKesytore provider
,D/dalvikvm( 6002): GC_CONCURRENT freed 3001K, 32% free 9567K/13920K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6002): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/UMC:Core( 6002): onCreate(): 
,D/USER_AGENT( 6002): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/Mms/ComposeMessageFragment( 5885): fillCache, easy = false
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4069): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4069): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 5375): GC_CONCURRENT freed 1990K, 27% free 10215K/13912K, paused 4ms+10ms, total 69ms
,D/[SAMSUNG SMARCART NATIVE]( 6002): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6002): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6002): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6002): FINISHED: initialize rv:0
,D/AbsListView( 5885): Get MotionRecognitionManager
,D/MotionRecognitionService( 2419):  ssp status : false
,I/dalvikvm( 5885): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
,W/dalvikvm( 5885): VFY: unable to resolve static method 1401: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
,D/dalvikvm( 5885): VFY: replacing opcode 0x71 at 0x03bb
,I/dalvikvm( 5885): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
,W/dalvikvm( 5885): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 5885): VFY: replacing opcode 0x74 at 0x0759
,I/dalvikvm( 5885): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 5885): VFY: unable to resolve virtual method 1402: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 5885): VFY: replacing opcode 0x74 at 0x07e8
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,V/WebViewChromium( 5885): Binding Chromium to the main looper Looper (main, tid 1) {422a02c0}
,I/chromium( 5885): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5885): Initializing chromium process, renderers=0
,D/dalvikvm( 6002): GC_CONCURRENT freed 1875K, 24% free 10764K/13984K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 6002): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/chromium( 5885): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 5885): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 5885): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/UMC:SecurityUtils( 6002): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6002): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6002): New Flow
I/        ( 2419): CCM JNI: In ccm_register_for_default_cert
I/        ( 2419): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2419): &ctx = 0x7bc3c618
I/TLC_TZ_CCM: ( 2419): creating new ccm context...
I/TLC_TZ_CCM: ( 2419): initializing ccm context...
I/TLC_TZ_CCM: ( 2419): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2419): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2419): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2419): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2419): root = 0, root_len = 1
I/TZ: client_server_communication( 2419): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2419): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2419): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2419): Client_Server_Open was called
D/TimaService( 2419): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2419): TIMA: in getTimaVersion
I/TZ: client_server_communication( 2419): IClientServer::IClientServer()
I/TZ: client_server_communication( 2419): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2508): creating new ccm context...
I/TZ_CCM_SERVER( 2508): initializing ccm context...
I/TZ_CCM_SERVER( 2508): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2508): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2508): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2508): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2508): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2508): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2508): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2508): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2508): device_id = 0x0
I/TZ: mc_tlc_communication( 2508): tlc_open() was called
I/TZ: mc_tlc_communication( 2508): Opening MobiCore device
I/TZ: mc_tlc_communication( 2508): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2508): Opening the session
D/libEGL  ( 5885): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 5885): Mali API Version : 401
,I/Mali    ( 5885): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/TZ: mc_tlc_communication( 2508): tlc_open() succeeded
I/TZ: client_server_communication( 2419): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2419): ctx = 0x78c262c8, comm = 0x8a5e0b20, sendmsg = 0x7a842008, recvmsg = 0x7a846c08
I/TZ_init: ( 2419): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
E/Parcel  ( 2419): nm 19456
E/TZ_init: ( 2419): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2419): trustlet initialization failed
,I/TZ_init: ( 2419): TZ_init_START...
,I/TZ_init: ( 2419): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2419): nm 19456
I/TZ_init: ( 2419): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2419): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,I/Icing   ( 3158): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
E/Parcel  ( 2419): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2419): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2419): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
E/Parcel  ( 2419): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2419): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2419): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: ( 2419): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
E/Parcel  ( 2419): nm 19456
I/TZ: client_server_communication( 2419): Client_Server_Close was called
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2508): tlc_close() was called
,I/TZ: mc_tlc_communication( 2508): Closing the session
I/TZ: mc_tlc_communication( 2508): Free WSM
,I/TZ: mc_tlc_communication( 2508): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2508): tlc_close() succeeded
,I/TZ: client_server_communication( 2419): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6002): TIMA service call for password change success!!
,D/UMC:AdminManager( 6002): init - start
,D/dalvikvm( 5885): GC_CONCURRENT freed 876K, 17% free 11702K/13936K, paused 4ms+3ms, total 39ms
,D/UMC:AdminManager( 6002): loadAdmins
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/UMC:AdminManager( 6002): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6002): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6002): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6002): init - end
,V/UMC:AlarmHandler( 6002): Enter loadList
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
,D/SPPApp  ( 6002): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6002): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,I/SELinux ( 6032): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6032):  
,D/Icing   ( 3158): Loaded CLD2 Version V2.0 - 20141016
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9502K/10896K, paused 3ms+3ms, total 30ms
,I/SELinux ( 6032): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6032):  
I/SELinux ( 6032):  
,I/SELinux ( 6032): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6032): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6032): >>>>> Normal User
,E/dalvikvm( 6032): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6032): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/ActivityManager( 2419): Killing 5023:com.dropbox.android/u0a95 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 27ms
,V/AlarmManager( 2419): waitForAlarm result :8
D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/TimaKeyStoreProvider( 6032): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6032): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6032): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10896K, paused 2ms+3ms, total 28ms
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 23 sec
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,W/ContextImpl( 5375): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
,I/DBG_DM  ( 4815): [3.19.140541][Line:838][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 4815): [3.19.140541][Line:842][onReceive] status  = 1
,E/DBG_DM  ( 4815): Warning!!! [3.19.140541][Line:853][onReceive] Device is ok
,I/Process ( 5375): Sending signal. PID: 5375 SIG: 9
,I/DBG_DM  ( 4815): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.example.hello.MainActivity
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/dalvikvm( 6032): GC_CONCURRENT freed 2998K, 32% free 9573K/13920K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 6032): WAIT_FOR_CONCURRENT_GC blocked 27ms
I/ActivityManager( 2419): Process com.sec.android.app.sysscope (pid 5375) (adj 0) has died.
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/ApplicationPromenada( 6032): Application OnCreate start
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/ApplicationPromenada( 6032): Application OnCreate po on Create
,I/Icing   ( 3158): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
D/CrashReporter( 6032): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@422eefa0
D/CrashReporter( 6032): Swaping uncaught exception handler
,D/ApplicationPromenada( 6032): Application OnCreate App Loader start
,D/ApplicationPromenada( 6032): Application OnCreate App Loader finish
,D/checkbox( 5885): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 5885): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 5885): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 5885): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/Mms/BubbleViewCache( 5885): fillCache bubble = 8
,D/Mms/Synchronizer( 5885): [start]    dbSync()
,D/TP/MmsSmsProvider( 2751): match 0:Elapsed time : 1.621 ms
,D/TP/MmsSmsProvider( 2751): update uri: content://mms-sms/db_synchronization
,V/TP/MmsSmsProvider( 2751): syncDBData start
,V/TP/MmsSmsProvider( 2751): syncDBData sms end
,V/TP/MmsSmsProvider( 2751): syncDBData mms end
,V/TP/MmsSmsProvider( 2751): syncDBData end
,D/Mms/Synchronizer( 5885): [end]    dbSync()
,D/Mms/MessagingNotification( 5885): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/MmsSmsProvider( 2751): match 6:Elapsed time : 1.553 ms
,D/p2.ApplicationLoader( 6032): ############################## cached apps: 
,V/WebViewChromium( 6032): Binding Chromium to the background looper Looper (main, tid 1) {422a8130}
,I/chromium( 6032): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6032): Initializing chromium process, renderers=0
,W/chromium( 6032): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6032): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6032): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6032): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6032): Mali API Version : 401
,I/Mali    ( 6032): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6032): Application OnCreate Finish
,I/SELinux ( 6064): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6064):  
I/ActivityManager( 2419): Killing 5044:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,I/SELinux ( 6064): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6064):  
I/SELinux ( 6064):  
,I/SELinux ( 6064): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6064): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6064): >>>>> Normal User
,E/dalvikvm( 6064): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10041 ]
,E/SELinux ( 6064): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6064): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6064): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6064): Added TimaKesytore provider
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43369cc0 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,D/dalvikvm( 6064): GC_CONCURRENT freed 2990K, 32% free 9569K/13912K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 6064): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/PackageManager( 2419): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@430f62d8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@431fba78, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,D/RegisteredServicesCache( 2756): empty dynamic service
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 2419): Killing 5059:com.sec.android.fwupgrade/1000 (adj 15): empty #43
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 6032): GC_CONCURRENT freed 1787K, 23% free 10811K/13944K, paused 2ms+4ms, total 94ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2756): empty dynamic service
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageBroadcastService( 3158): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3158): Module APK com.google.android.play.games already loaded
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4815): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 24 sec
,I/DBG_DM  ( 4815): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4815): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.example.hello.MainActivity
,I/DBG_DM  ( 4815): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3158): Module APK com.google.android.play.games already loaded
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
,D/AsyncTaskServiceImpl( 3158): Submit a task: k
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4815): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4815): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4815): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4815): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4815): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4815): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Scheme: "smsto"
,I/DBG_DM  ( 4815): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4815): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4815): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4815): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4815): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4815): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4815): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4815): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.example.hello.MainActivity
,I/DBG_DM  ( 4815): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/k       ( 3158): Processing package: com.example.hello
,I/DBG_DM  ( 4815): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4815): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4815): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,D/GassUtils( 3158): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 3158): Found info for package com.example.hello in db.
,I/dalvikvm( 4815): Total arena pages for JIT: 11
I/dalvikvm( 4815): Total arena pages for JIT: 12
,I/dalvikvm( 4815): Total arena pages for JIT: 13
,I/dalvikvm( 4815): Total arena pages for JIT: 14
,I/dalvikvm( 4815): Total arena pages for JIT: 15
I/dalvikvm( 4815): Total arena pages for JIT: 16
,I/dalvikvm( 4815): Total arena pages for JIT: 17
,I/DBG_DM  ( 4815): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/dalvikvm( 4815): Total arena pages for JIT: 18
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 4815): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
E/Watchdog( 2419): !@Sync 2
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(1) - 4
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2578): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42306790
,D/dalvikvm( 2419): GC_EXPLICIT freed 2641K, 17% free 25093K/29916K, paused 8ms+17ms, total 230ms
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ApplicationsProvider( 2954): Could not fetch usage stats
W/ApplicationsProvider( 2954): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2954): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2954): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2954): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6086): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6086):  
,I/DBG_DM  ( 4815): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4815): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4815): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423b07c0
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{432df370 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/SELinux ( 6086): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6086):  
I/SELinux ( 6086):  
,I/SELinux ( 6086): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6086): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6086): >>>>> Normal User
,E/dalvikvm( 6086): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 6086): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,I/SurfaceFlinger( 1921): id=17 createSurf (1x1),1 flag=4, Uoast
,D/TimaKeyStoreProvider( 6086): in addTimaSignatureService
D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/TimaKeyStoreProvider( 6086): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6086): Added TimaKesytore provider
,W/ApplicationsProvider( 2954): Could not fetch usage stats
W/ApplicationsProvider( 2954): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2954): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2954): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2954): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 6086): GC_CONCURRENT freed 2994K, 32% free 9568K/13912K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 6086): WAIT_FOR_CONCURRENT_GC blocked 19ms
,E/SPPClientService( 6086): ============PushLog. commonIsShipBuild. stop!
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 6086): [PushClientApplication] Push log off : This is Ship build version
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SPPClientService( 6086): PushLog.txt file is not deleted.
D/SPPClientService( 6086): PushLog.txt file is not deleted.
,D/SPPClientService( 6086): ============PushLog. stop!
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 2419): Killing 5073:com.sec.factory.camera/1000 (adj 15): empty #43
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Finsky  ( 3750): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/SELinux ( 6102): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6102):  
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6102): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6102):  
I/SELinux ( 6102):  
,I/SELinux ( 6102): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6102): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6102): >>>>> Normal User
,E/dalvikvm( 6102): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10154 ]
,E/SELinux ( 6102): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6102): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6102): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6102): Added TimaKesytore provider
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 6032): GC_CONCURRENT freed 2364K, 27% free 10428K/14140K, paused 3ms+4ms, total 51ms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/dalvikvm( 6102): GC_CONCURRENT freed 2997K, 32% free 9567K/13912K, paused 3ms+2ms, total 40ms
,D/dalvikvm( 6102): WAIT_FOR_CONCURRENT_GC blocked 36ms
,V/TaskCloserActivity( 6102): TaskCloserActivity enter()
,I/GCoreNlp( 2735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager( 2419): Killing 5157:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #43
,W/ResourceType( 6032): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,I/knox    ( 5143): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/PackageManager( 6032): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6032): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6032): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6032): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6032): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6032): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6032): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6032): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6032): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6032): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6032): 	at java.lang.Thread.run(Thread.java:841)
W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5143): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5143): KNOXAgentService : onCreate()
,D/knox    ( 5143): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5143): KNOXAgentService. startJobThread() start
,D/knox    ( 5143): KNOXAgentService. JobThread()
,D/knox    ( 5143): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5143): KNOXAgentService. startJobThread() wait
,D/knox    ( 5143): KNOXAgentService : onDestroy().
,D/knox    ( 5143): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 6118): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6118):  
,I/SELinux ( 6118): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6118):  
I/SELinux ( 6118):  
,I/SELinux ( 6118): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6118): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6118): >>>>> Normal User
,E/dalvikvm( 6118): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 6118): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/LocationProviderProxy( 2419): applying state to connected service
,D/LocationProviderProxy( 2419): applying state to connected service
,D/TimaKeyStoreProvider( 6118): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6118): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6118): Added TimaKesytore provider
D/QuickConnect[1.1][2] ( 5199): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 5885): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 5885): performUpdate:widgetCount=0
,D/ContactProvider( 3429): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5199): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 3429): getAllContactInfoList End
,I/syncContacts( 3429): thread: 127, onChange
,D/dalvikvm( 6118): GC_CONCURRENT freed 3007K, 32% free 9559K/13916K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6118): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/FactoryTestApp( 6118): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 6118): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 6118): User mode
,I/SELinux ( 6131): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6131):  
I/ActivityManager( 2419): Killing 5170:com.LocalFota/u0a113 (adj 15): empty #43
,I/Icing   ( 3158): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/SELinux ( 6131): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6131):  
I/SELinux ( 6131):  
,I/SELinux ( 6131): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6131): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6131): >>>>> Normal User
,E/dalvikvm( 6131): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 6131): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6131): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6131): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6131): Added TimaKesytore provider
,D/dalvikvm( 3158): GC_CONCURRENT freed 1756K, 20% free 12627K/15728K, paused 8ms+8ms, total 76ms
,D/dalvikvm( 6131): GC_CONCURRENT freed 3005K, 32% free 9566K/13920K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 6131): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/Icing   ( 3158): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,E/MTPRx   ( 6131): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 6131): check value of boot_completed is1
,E/MTPRx   ( 6131): check booting is completed_sys.boot_completed
,E/MTPRx   ( 6131): Sd-Card path/storage/extSdCard
E/MTPRx   ( 6131): Status for mount/Unmount :removed
,E/MTPRx   ( 6131): SDcard is not available
W/MTPRx   ( 6131): value of connected istrue
W/MTPRx   ( 6131): value of configured istrue
W/MTPRx   ( 6131): value of mtpEnabled istrue
,W/MTPRx   ( 6131): value of ptpEnabled isfalse
E/MTPRx   ( 6131): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 6131): mFirstTime: false
,D/dalvikvm( 6032): GC_CONCURRENT freed 1991K, 27% free 10359K/14140K, paused 4ms+18ms, total 57ms
,D/        ( 6131): MTP: reading debug level property
E/MTPRx   ( 6131):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 6131): Getting CryptionKey from JAVA
,E/MTPRx   ( 6131): currentUserId is 0
,E/MTPRx   ( 6131): Start observing USB_STATE_MATCH 
E/MTPRx   ( 6131): usbMode is 0200
,E/MTPRx   ( 6131): is_secretmode is NOT 1
,D/MTPRx   ( 6131):  inside checkKnoxStatus
,D/MTPRx   ( 6131):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 6131): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 6131): noti = 17
,E/MTPRx   ( 6131): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 6131): else part ... so first time!!!
E/MTPPlaObsrvr( 6131): inside setContext()
,E/MTPPlaObsrvr( 6131):  inside createplafiles
,E/MTPPlaObsrvr( 6131): playlist count is0
,E/MTPPlaObsrvr( 6131):  inside try branch createplafiles
,E/MTPPlaObsrvr( 6131):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 6131): Inside registerContentObserver
E/MtpAdbObserver( 6131): inside setContext()
E/MtpAdbObserver( 6131): Inside registerContentObserver
,W/Settings( 6131): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 6131): onCreate.
,E/MtpService( 6131): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6131): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 6131): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 6131): onStartCommand.
,E/MtpService( 6131): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 6131): calling native method
,E/MTPJNIInterface( 6131): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 6131): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 6131): noti = 10
,E/MtpService( 6131): onStartCommand.
,E/MtpService( 6131): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 6131): calling native method
E/MTPRx   ( 6131): Checking the driver time out
E/MTPJNIInterface( 6131): noti = 2
,D/        ( 6131): deleting sockets before message queue initialization
,D/        ( 6131): event handler thread is created, so set the flag
E/MTPRx   ( 6131): called native method
E/MTPJNIInterface( 6131): setting Media scanner status0
E/MTPJNIInterface( 6131): After setting Media scanner status0
,W/MTPRx   ( 6131): notification from stack 1
,E/MTPJNIInterface( 6131): Getting media scanner status0
,E/MTPJNIInterface( 6131): DeviceName is S5mini-1
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5412): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5412): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5412): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5412): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1452531000000
,D/daemonapp( 5412): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1452527877519
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5412): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 5907): onReceive
,I/SELinux ( 6148): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6148):  
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 6148): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6148):  
I/SELinux ( 6148):  
I/SELinux ( 6148): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6148): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6148): >>>>> Normal User
E/dalvikvm( 6148): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
E/SELinux ( 6148): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/dalvikvm( 6148): Enabling JNI app bug workarounds for target SDK version 7...
,D/TimaKeyStoreProvider( 6148): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6148): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6148): Added TimaKesytore provider
,D/dalvikvm( 6148): GC_CONCURRENT freed 3010K, 32% free 9559K/13916K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 6148): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/System.err( 6148): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,W/System.err( 6148): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6148): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6148): 	at java.util.Scanner.<init>(Scanner.java:158)
,W/System.err( 6148): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6148): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6148): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
,W/System.err( 6148): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6148): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6148): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6148): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 6148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6148): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6148): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6148): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 6148): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6148): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6148): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6148): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6148): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 6148): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6148): 	... 20 more
,W/System.err( 6148): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6148): Excternal dir: /mnt/sdcard
,V/MaBo    ( 6148): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6148): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6148): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6148): moge zapisać w resDir?true
,W/GAV2    ( 6148): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 6148): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6148): init tracking...
,I/AUDIOTEKA_GA( 6148): app started!
,D/p2.ApplicationLoader( 6032): Process time: 3798
,I/BugSenseHandler( 6148): Registering default exceptions handler
,D/p2.ApplicationLoader( 6032): ##############################  apps after loading: 
,D/dalvikvm( 6032): GC_CONCURRENT freed 1941K, 27% free 10365K/14140K, paused 5ms+4ms, total 54ms
,D/AuthorizationBluetoothService( 2850): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/MTPJNIInterface( 6131): Status for mount/Unmount :removed
,E/MTPJNIInterface( 6131): SDcard is not available
,I/knox    ( 5143): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 5143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/MTPJNIInterface( 6131): Status for mount/Unmount :removed
E/MTPJNIInterface( 6131): SDcard is not available
E/SQLiteLog( 6131): (21) API call with NULL database connection pointer
E/SQLiteLog( 6131): (21) misuse at line 96835 of [00bb9c9ce4]
E/SQLiteLog( 6131): (21) API call with NULL database connection pointer
E/SQLiteLog( 6131): (21) misuse at line 93311 of [00bb9c9ce4]
E/SQLiteLog( 6131): (21) API call with NULL database connection pointer
E/SQLiteLog( 6131): (21) misuse at line 93311 of [00bb9c9ce4]
E/SQLiteLog( 6131): (21) API call with NULL database connection pointer
E/SQLiteLog( 6131): (21) misuse at line 96835 of [00bb9c9ce4]
W/MTPRx   ( 6131): notification from stack 2
D/        ( 6131): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 6131): [mtp_init_device]  After open the MTP fd = 55 and line = 678...
D/        ( 6131): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 6131): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,I/DownloadService( 6148): Tworzenie serwisu - onCreate()
,I/DownloadService( 6148): Start serwisu - onStart()
,I/knox    ( 5143): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 5143): KNOXAgentService : onCreate()
D/knox    ( 5143): KNOXAgentService : set alarms for deniallog and usage data upload

```
