#### Test 5841644866d9c0e_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 3591): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3591):  
I/SELinux ( 3591): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3591):  
I/SELinux ( 3591):  
I/SELinux ( 3591): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3591): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3591): >>>>> Normal User
E/dalvikvm( 3591): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3591): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3591): in addTimaSignatureService
D/TimaKeyStoreProvider( 3591): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3591): Added TimaKesytore provider
E/SMD     (  241): DCD ON
--------- beginning of /dev/log/system
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=3591, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3608): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3608):  
I/ActivityManager(  731): Killing 2656:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
I/SELinux ( 3608): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3608):  
I/SELinux ( 3608):  
I/SELinux ( 3608): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3608): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3608): >>>>> Normal User
E/dalvikvm( 3608): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 3608): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 3608): in addTimaSignatureService
D/TimaKeyStoreProvider( 3608): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3608): Added TimaKesytore provider
I/Intent to TravelDirActivity( 3608): inside TravelBroadcastReceiver
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=3608, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  731): Killing 2052:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
W/BackupManagerService(  731): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1455019756330
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1455041280000
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/daemonapp( 1463): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1455041280000
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 3
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1455041280000
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/SELinux ( 3623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3623):  
I/ActivityManager(  731): Waited long enough for: ServiceRecord{4373f9a0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
I/SELinux ( 3623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3623):  
I/SELinux ( 3623):  
I/SELinux ( 3623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3623): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3623): >>>>> Normal User
E/dalvikvm( 3623): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3623): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3623): in addTimaSignatureService
D/TimaKeyStoreProvider( 3623): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3623): Added TimaKesytore provider
D/AndroidRuntime( 3609): 
D/AndroidRuntime( 3609): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3609): CheckJNI is OFF
D/AndroidRuntime( 3609): setted country_code = Poland
D/AndroidRuntime( 3609): setted countryiso_code = PL
D/AndroidRuntime( 3609): setted sales_code = XEO
D/AndroidRuntime( 3609): readGMSProperty: start
D/AndroidRuntime( 3609): readGMSProperty: already setted!!
D/AndroidRuntime( 3609): readGMSProperty: end
D/AndroidRuntime( 3609): addProductProperty: start
D/dalvikvm( 3609): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3609): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3609): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3609): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3609): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=3623, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
E/memtrack( 3609): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3609): failed to load memtrack module: -2
E/YouTube ( 3623): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/dalvikvm( 3609): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 3609): Calling main entry com.android.commands.am.Am
D/YouTube ( 3623): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/AndroidRuntime( 3609): Shutting down VM
D/dalvikvm( 3609): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 1ms+1ms, total 3ms
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3623): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3623): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3623): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3623): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3623): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  731): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  731): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  731): getStreamVolume 3 index 0
I/MediaRouter( 3623): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3623): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3623): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1455019757&data=screen_name%3D%3CAndroid_YT_Open_App%3E
I/System.out( 3623): Thread-355(HTTPLog):isShipBuild true
I/System.out( 3623): Thread-355(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3623): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3623): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/YouTube ( 3623): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3623): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/WifiDisplayAdapter(  731): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/YouTube ( 3623): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/YouTube ( 3623): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
I/SELinux ( 3681): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3681):  
I/ActivityManager(  731): Killing 2761:com.policydm/1000 (adj 15): empty #43
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
I/SELinux ( 3681): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3681):  
I/SELinux ( 3681):  
I/SELinux ( 3681): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/YouTube ( 3623): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
E/SELinux ( 3681): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3681): >>>>> Normal User
E/dalvikvm( 3681): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
D/YouTube ( 3623): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
E/SELinux ( 3681): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/YouTube ( 3623): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/TimaKeyStoreProvider( 3681): in addTimaSignatureService
D/TimaKeyStoreProvider( 3681): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3681): Added TimaKesytore provider
E/AtFwd AutoBoot( 3681): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3681): onCreate method
I/AtFwdService( 3681): Instantiate AtCmdFwd Service
W/ContextImpl( 3681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
D/AtCkpdCmdHandler( 3681): De-queing command
W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
I/GoogleConversionPing( 3623): Ping responded with response code 200
I/SELinux ( 3696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3696):  
I/SELinux ( 3696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3696):  
I/SELinux ( 3696):  
I/SELinux ( 3696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3696): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3696): >>>>> Normal User
E/dalvikvm( 3696): >>>>> com.android.vending [ userId:0 | appId:10030 ]
E/SELinux ( 3696): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3696): in addTimaSignatureService
D/TimaKeyStoreProvider( 3696): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3696): Added TimaKesytore provider
D/AmoledAdjustTimer(  731): prevTemp = 290, currTemp = 293, prevStep = 4, currStep = 4
I/dalvikvm( 3696): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3696): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 3696): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/dalvikvm( 3696): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 3696): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 3696): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 3696): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 3696): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3696): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3696): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 3696): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3696): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 3696): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3696): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 3696): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3696): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3696): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3696): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3696): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 3696): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3696): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 3696): Skipping gmscore version check
,D/Volley  ( 3696): [351] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3696): [344] DiskBasedCache.clear: Cache cleared.
,D/Finsky  ( 3696): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3696): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3696): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3696): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1755): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1755): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1755): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1755): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1755): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1755): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1755): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1755): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1755): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1755): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1755): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,W/InstanceID/Rpc( 1755): Found 10011
,D/FileApkUtils( 1755): Spent 74ms computing apk sha1.
,D/FileApkUtils( 1755): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1755): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1755): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1755): Reading stored module config
,D/GmsModuleFndr( 1755): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1755): Beginning module configuration check
,D/ChimeraCfgMgr( 1755): Module APKs unchanged, check complete
,E/dalvikvm( 1755): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1755): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 1755): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1755): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1755): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1755): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1755): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1755): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1755): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1755): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1755): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1755): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1755): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1216): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1216): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1216): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1216): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm( 1216): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1216): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
E/dalvikvm( 1755): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1755): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1755): VFY: replacing opcode 0x1f at 0x000e
,E/dalvikvm( 1755): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1755): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1755): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,I/dalvikvm( 1755): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1755): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0004
,D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1755): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1755): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1755): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1755): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/dalvikvm( 1291): GC_EXPLICIT freed 754K, 46% free 10364K/19084K, paused 3ms+3ms, total 30ms
,I/CheckinService( 1755): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 446001832
,I/CheckinService( 1755): Disabling old GoogleServicesFramework version
,D/GCM     ( 1755): COMPAT: Multi user not supported
,D/GCM     ( 1291): COMPAT: Multi user not supported
,I/dalvikvm( 1291): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1291): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 1755): GC_CONCURRENT freed 1618K, 42% free 11250K/19084K, paused 3ms+7ms, total 41ms
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1755): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1216): DispatchingService.onCreate()
I/dalvikvm( 1291): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x0010
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1755): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1755): Got an BootCompleted event.
,D/BootCompletedReceiver( 1755): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1755): onCreate
,D/SystemUpdateService( 1755): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 1755): Checking schedule, now: 1455019758405 next: 1455161282380
,I/CheckinService( 1755): active receiver: disabled
,I/dalvikvm( 1755): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1755): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0409
,V/AuthZen ( 1755): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 1755): cancelUpdate (empty URL)
,I/SystemUpdateService( 1755): active receiver: disabled
,I/dalvikvm( 1755): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 1755): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x002b
,D/EnterpriseDeviceManagerService(  731): Creating context as user 0
,W/dalvikvm( 1291): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1291): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1291): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1291): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x00bb
,D/dalvikvm( 1291): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1291): VFY: unable to resolve instance field 161
,D/dalvikvm( 1291): VFY: replacing opcode 0x52 at 0x0006
,I/GCoreUlr( 1216): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1755): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c14c00
,D/dalvikvm( 1216): GC_CONCURRENT freed 1602K, 41% free 11428K/19084K, paused 3ms+7ms, total 44ms
,D/dalvikvm( 1755): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c14c00
,D/dalvikvm( 1755): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c14c00, skipping init
,D/AuthZenEventHandler( 1755): Handling event: android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService(  731): Creating context as user 0
,D/SystemUpdateService( 1755): onDestroy
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
I/dalvikvm( 1291): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1291): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x0059
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1755): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1755): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x00bb
,I/GCoreUlr( 1216): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/BaseAppContext( 1755): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/dalvikvm( 1291): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1291): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x0022
I/GCoreUlr( 1216): Unbound from all location providers
,I/GCoreUlr( 1216): Place inference reporting - stopped
,I/GCoreUlr( 1216): DispatchingService.onDestroy()
,I/GCoreUlr( 1216): Stopping handler for UlrDispSvcFast
I/dalvikvm( 1755): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1755): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x002f
,I/GCoreUlr( 1216): Unbound from all location providers
,I/GCoreUlr( 1216): Place inference reporting - stopped
,I/AuthZen ( 1755): Fetching signing key...
,D/GCM     ( 1291): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1291): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x001c
,I/AuthZen ( 1755): Signing key fetched successfully!
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1291): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x0053
,W/Auth    ( 1291): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1066): isPcwEnable = null
,I/dalvikvm( 1291): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x001f
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1291): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1291): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1291): VFY: replacing opcode 0x6e at 0x0041
,D/dalvikvm(  731): GC_EXPLICIT freed 1508K, 14% free 23403K/27064K, paused 4ms+10ms, total 136ms
,D/AuthZenTransactionCache( 1755): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1755): Clearing transaction cache
,D/PersistentNotificationBroadcastReceiver( 1216): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/WearableService( 1216): callingUid 10011, callindPid: 1216
,E/MDM     ( 1216): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1755): Restart initialization of location
,D/AuthorizationBluetoothService( 1291): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1291): Proximity feature is not enabled.
,I/GCM     ( 1291): GCM config loaded
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1216): No location to return for getLastLocation()
,W/FusedLocationProvider( 1216): location=null
,V/AlarmManager(  731): waitForAlarm result :8
,E/MDM     ( 1216): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1755): Restart initialization of location
,D/AuthorizationBluetoothService( 1291): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1291): Proximity feature is not enabled.
,W/GCoreFlp( 1216): No location to return for getLastLocation()
,W/FusedLocationProvider( 1216): location=null
,V/GLSActivity( 1291): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  731): waitForAlarm result :8
,D/SensorService(  731):   -0.1 -0.1 9.6
V/AlarmManager(  731): waitForAlarm result :8
,E/SMD     (  241): DCD ON
,I/Atfwd_Daemon(  378): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  378): ATFWD --> QMI Port : rmnet1
I/Atfwd_Daemon(  378): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  378): Trying to register 8 commands:
,I/Atfwd_Daemon(  378): cmd0: +CKPD
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  378): cmd1: +CTSA
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  378): cmd2: +CFUN
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  378): cmd3: +CMAR
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  378): cmd4: +CDIS
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  378): cmd5: +CRSL
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  378): cmd6: +CSS
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  378): cmd7: $QCPWRDN
I/Atfwd_Daemon(  378): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  378): Registered AT Commands event handler
,I/SELinux ( 3815): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3815):  
,D/Mms/Contact( 1668): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3337): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1668): performUpdate:widgetCount=0
,D/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2357): getAllContactInfoList Start
,D/dalvikvm(  249): GC_EXPLICIT freed 44K, 51% free 9507K/19084K, paused 3ms+4ms, total 32ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9507K/19084K, paused 2ms+4ms, total 23ms
,D/ContactProvider( 2357): getAllContactInfoList End
I/syncContacts( 2357): thread: 155, onChange
,I/SELinux ( 3815): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3815):  
I/SELinux ( 3815):  
,I/SELinux ( 3815): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3815): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3815): >>>>> Normal User
,E/dalvikvm( 3815): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3815): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9507K/19084K, paused 1ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 3815): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3815): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3815): Added TimaKesytore provider
,D/Mms/Contact( 1668): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3337): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getMyMobileNumber - 
,D/ContactProvider( 2357): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3337): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2357): getAllContactInfoList End
,I/syncContacts( 2357): thread: 156, onChange
,V/TaskCloserActivity( 3815): TaskCloserActivity enter()
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=3815, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3829): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3829):  
,I/SELinux ( 3829): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3829):  
I/SELinux ( 3829):  
,I/SELinux ( 3829): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3829): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3829): >>>>> Normal User
,E/dalvikvm( 3829): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3829): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3829): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3829): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3829): Added TimaKesytore provider
,D/FactoryTestApp( 3829): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3829): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3829): User mode
,I/SELinux ( 3841): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3841):  
I/ActivityManager(  731): Killing 2779:com.sec.spp.push/u0a38 (adj 15): empty #43
,D/ConnectivityService(  731): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 3841): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3841):  
I/SELinux ( 3841):  
,I/SELinux ( 3841): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3841): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3841): >>>>> Normal User
,E/dalvikvm( 3841): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3841): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3841): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3841): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3841): Added TimaKesytore provider
,E/MTPRx   ( 3841): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3841): check value of boot_completed is1
,E/MTPRx   ( 3841): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3841): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3841): Status for mount/Unmount :removed
,E/MTPRx   ( 3841): SDcard is not available
W/MTPRx   ( 3841): value of connected istrue
W/MTPRx   ( 3841): value of configured istrue
W/MTPRx   ( 3841): value of mtpEnabled istrue
,W/MTPRx   ( 3841): value of ptpEnabled isfalse
E/MTPRx   ( 3841): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3841): mFirstTime: false
,D/        ( 3841): MTP: reading debug level property
E/MTPRx   ( 3841):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 3841): Getting CryptionKey from JAVA
,E/MTPRx   ( 3841): currentUserId is 0
,E/MTPRx   ( 3841): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3841): usbMode is 0200
,E/MTPRx   ( 3841): is_secretmode is NOT 1
,W/MTPRx   ( 3841): Phone is lockedtrue
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/MTPRx   ( 3841):  inside checkKnoxStatus
,D/MTPRx   ( 3841):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3841): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3841): noti = 17
,E/MTPRx   ( 3841): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3841): else part ... so first time!!!
E/MTPPlaObsrvr( 3841): inside setContext()
,E/MTPPlaObsrvr( 3841):  inside createplafiles
,E/MTPPlaObsrvr( 3841): playlist count is0
,E/MTPPlaObsrvr( 3841):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3841):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3841): Inside registerContentObserver
,E/MtpAdbObserver( 3841): inside setContext()
E/MtpAdbObserver( 3841): Inside registerContentObserver
,W/Settings( 3841): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,E/MtpService( 3841): onCreate.
,E/MtpService( 3841): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3841): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3841): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3841): onStartCommand.
W/MTPRx   ( 3841): calling native method
,E/MTPJNIInterface( 3841): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3841): < MTP > Registering BroadCast receiver :::::::
I/knox    ( 3279): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/MTPJNIInterface( 3841): noti = 10
,E/MtpService( 3841): onStartCommand.
W/MTPRx   ( 3841): calling native method
,E/MTPRx   ( 3841): Checking the driver time out
E/MtpService( 3841): handleMessage. msg= { when=-5ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3841): noti = 2
,D/        ( 3841): deleting sockets before message queue initialization
D/        ( 3841): event handler thread is created, so set the flag
,E/MTPRx   ( 3841): called native method
E/MTPJNIInterface( 3841): setting Media scanner status0
,E/MTPJNIInterface( 3841): After setting Media scanner status0
,E/MTPJNIInterface( 3841): Getting media scanner status0
,W/MTPRx   ( 3841): notification from stack 1
,E/MTPJNIInterface( 3841): DeviceName is Galaxy S5-2
,I/knox    ( 3279): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3279): KNOXAgentService : onCreate()
D/knox    ( 3279): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3279): KNOXAgentService. startJobThread() start
D/knox    ( 3279): KNOXAgentService. JobThread()
D/knox    ( 3279): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3279): KNOXAgentService. startJobThread() wait
E/MtpService( 3841): handleMessage. msg= { when=-10ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/knox    ( 3279): KNOXAgentService : onDestroy().
D/knox    ( 3279): ModuleBase.cancelAllAlarmManageModule()
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455041280000
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455019759849
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1314): onReceive
,D/AuthorizationBluetoothService( 1291): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3279): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3279): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/knox    ( 3279): KNOXAgentService : onCreate()
,D/knox    ( 3279): KNOXAgentService : set alarms for deniallog and usage data upload
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,D/knox    ( 3279): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/dalvikvm( 1463): GC_CONCURRENT freed 7445K, 47% free 10133K/19084K, paused 3ms+2ms, total 82ms
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/knox    ( 3279): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3279): KNOXAgentService. startJobThread() start
,D/knox    ( 3279): KNOXAgentService. JobThread()
D/knox    ( 3279): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3279): KNOXAgentService. startJobThread() wait
,D/FileShare-Server( 3017): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/knox    ( 3279): KNOXAgentService : onDestroy().
,I/knox    ( 3279): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
,D/knox    ( 3279): ModuleBase.cancelAllAlarmManageModule()
,D/FileShare-Server( 3017): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3877): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3877):  
,I/SELinux ( 3877): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3877):  
I/SELinux ( 3877):  
,I/SELinux ( 3877): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3877): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3877): >>>>> Normal User
,E/dalvikvm( 3877): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3877): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3877): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3877): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3877): Added TimaKesytore provider
,D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/System.out( 3877): Inside WakeupProvider
,I/System.out( 3877): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3877): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3877): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3877): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3877): initQueue()
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1314):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1314): showing allowed
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  731): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=731
,D/DisplayPowerController(  731): animation target = 64 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  731): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/lights  (  731): lcd : 45 +
,D/lights  (  731): lcd : 45 -
,D/lights  (  731): lcd : 64 +
D/RampAnimator(  731): Light Animator Finished currentValue=64
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/lights  (  731): lcd : 64 -
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/LocalBluetoothProfileManager( 1314): Adding local A2DP profile
,D/dalvikvm( 1314): GC_CONCURRENT freed 7526K, 48% free 10067K/19084K, paused 6ms+2ms, total 82ms
,D/LocalBluetoothProfileManager( 1314): Adding local HEADSET profile
W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1314): BTStateChangeCB is registed
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 1314): BluetoothHeadset service is binded
,D/Bluetoothsap( 1314): bindService called to Bluetooth SAP Service
W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
D/LocalBluetoothProfileManager( 1314): PANU : true
D/LocalBluetoothProfileManager( 1314): Adding local MAP profile
W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/BluetoothMap( 1314): Create BluetoothMap proxy object
D/dalvikvm( 1204): GC_EXPLICIT freed 3900K, 48% free 10045K/19084K, paused 4ms+7ms, total 44ms
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,E/MTPJNIInterface( 3841): Status for mount/Unmount :removed
E/MTPJNIInterface( 3841): SDcard is not available
D/Bluetoothsap( 1314): bindService called to Bluetooth SAP Service
,W/ContextImpl( 1314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/LocalBluetoothProfileManager( 1314): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 1314): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1314): onReceive
D/BluetoothA2dp( 1314): Proxy object connected
D/A2dpProfile( 1314): Bluetooth service connected
,D/BtConfig.SecureMode( 1943): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1291): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1291): Proximity feature is not enabled.
I/PowerManagerService(  731): [PWL] On : 0 (54572 ms ago)
I/PowerManagerService(  731): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  731): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1066, ws=null) (elapsedTime=17015)
I/PowerManagerService(  731): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=731, ws=WorkSource{1000}) (elapsedTime=248)
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/MTPJNIInterface( 3841): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3841): SDcard is not available
,E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 96833 of [00bb9c9ce4]
,E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
E/SQLiteLog( 3841): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3841): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3841): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3841): notification from stack 2
D/        ( 3841): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3841): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3841): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3841): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,I/SELinux ( 3905): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3905):  

```
