#### Test 58751238ee11130_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 3627): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3627):  
I/SELinux ( 3627):  
I/SELinux ( 3627): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3627): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3627): >>>>> Normal User
E/dalvikvm( 3627): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3627): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/daemonapp( 1458): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1458): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1458): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
D/TimaKeyStoreProvider( 3627): in addTimaSignatureService
D/TimaKeyStoreProvider( 3627): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3627): Added TimaKesytore provider
D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
,--------- beginning of /dev/log/system
I/ActivityManager(  752): Waited long enough for: ServiceRecord{431f3b98 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
W/ActivityManager(  752): Permission Denial: getCurrentUser() from pid=3627, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
E/YouTube ( 3627): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/YouTube ( 3627): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/AndroidRuntime( 3648): 
D/AndroidRuntime( 3648): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3648): CheckJNI is OFF
D/AndroidRuntime( 3648): setted country_code = Poland
D/AndroidRuntime( 3648): setted countryiso_code = PL
D/AndroidRuntime( 3648): setted sales_code = XEO
D/AndroidRuntime( 3648): readGMSProperty: start
D/AndroidRuntime( 3648): readGMSProperty: already setted!!
D/AndroidRuntime( 3648): readGMSProperty: end
D/AndroidRuntime( 3648): addProductProperty: start
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3627): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/dalvikvm( 3648): Trying to load lib libjavacore.so 0x0
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/dalvikvm( 3648): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3648): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3648): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3648): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/YouTube ( 3627): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3627): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3627): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3627): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  752): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  752): getStreamVolume 3 index 0
I/MediaRouter( 3627): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  752): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3627): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
E/memtrack( 3648): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3648): failed to load memtrack module: -2
I/GoogleConversionPing( 3627): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1455027660&data=screen_name%3D%3CAndroid_YT_Open_App%3E
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3627): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
I/System.out( 3627): Thread-355(HTTPLog):isShipBuild true
I/System.out( 3627): Thread-355(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/YouTube ( 3627): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/dalvikvm( 3648): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/YouTube ( 3627): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3627): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/WifiDisplayAdapter(  752): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3627): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/AndroidRuntime( 3648): Calling main entry com.android.commands.am.Am
D/YouTube ( 3627): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
I/SELinux ( 3705): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3705):  
I/ActivityManager(  752): Killing 2774:com.policydm/1000 (adj 15): empty #43
D/YouTube ( 3627): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3627): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
I/SELinux ( 3705): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3705):  
I/SELinux ( 3705):  
I/SELinux ( 3705): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3705): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3705): >>>>> Normal User
E/dalvikvm( 3705): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
E/SELinux ( 3705): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/YouTube ( 3627): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/TimaKeyStoreProvider( 3705): in addTimaSignatureService
D/TimaKeyStoreProvider( 3705): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3705): Added TimaKesytore provider
D/AndroidRuntime( 3648): Shutting down VM
D/dalvikvm( 3648): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
W/ContextImpl( 3705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3705): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3705): onCreate method
I/AtFwdService( 3705): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 3705): De-queing command
W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
I/GoogleConversionPing( 3627): Ping responded with response code 200
I/SELinux ( 3725): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3725):  
I/SELinux ( 3725): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3725):  
I/SELinux ( 3725):  
I/SELinux ( 3725): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3725): >>>>> Normal User
E/dalvikvm( 3725): >>>>> com.android.vending [ userId:0 | appId:10030 ]
E/SELinux ( 3725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3725): in addTimaSignatureService
D/TimaKeyStoreProvider( 3725): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3725): Added TimaKesytore provider
,D/AmoledAdjustTimer(  752): prevTemp = 288, currTemp = 290, prevStep = 4, currStep = 4
I/dalvikvm( 3725): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3725): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 3725): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/dalvikvm( 3725): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 3725): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 3725): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 3725): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 3725): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3725): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3725): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 3725): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3725): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 3725): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3725): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 3725): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3725): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3725): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3725): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x0385
I/dalvikvm( 3725): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3725): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 3725): VFY: replacing opcode 0x6e at 0x0019
D/Volley  ( 3725): [344] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3725): Skipping gmscore version check
D/Finsky  ( 3725): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3725): [1] Libraries$2.run: Finished loading 1 libraries.
D/Volley  ( 3725): [351] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 3725): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 3725): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
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
,D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1781): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1781): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1781): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1781): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1781): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1781): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1781): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1781): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1781): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1781): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1781): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,D/FileApkUtils( 1781): Spent 55ms computing apk sha1.
,D/FileApkUtils( 1781): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1781): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1781): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1781): Reading stored module config
,D/dalvikvm( 1305): GC_EXPLICIT freed 760K, 46% free 10364K/19060K, paused 3ms+4ms, total 32ms
,D/GmsModuleFndr( 1781): Beginning GMS chimera module scan
,W/InstanceID/Rpc( 1781): Found 10011
,D/ChimeraCfgMgr( 1781): Beginning module configuration check
,D/ChimeraCfgMgr( 1781): Module APKs unchanged, check complete
,E/dalvikvm( 1781): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1781): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1781): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1781): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1781): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1781): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1781): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1781): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1781): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1781): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1216): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1216): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1216): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
E/dalvikvm( 1781): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1781): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1781): VFY: replacing opcode 0x1f at 0x000e
I/dalvikvm( 1216): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1216): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1216): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1216): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1216): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/GCM     ( 1781): COMPAT: Multi user not supported
E/dalvikvm( 1781): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1781): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1781): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1781): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1781): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1781): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1781): VFY: replacing opcode 0x62 at 0x0008
,D/GCM     ( 1305): COMPAT: Multi user not supported
D/dalvikvm( 1781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1781): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
I/dalvikvm( 1305): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1305): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x000f
,I/CheckinService( 1781): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 453905736
,I/GCoreUlr( 1781): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1216): DispatchingService.onCreate()
,I/CheckinService( 1781): Disabling old GoogleServicesFramework version
I/dalvikvm( 1305): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1305): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x0010
,D/dalvikvm( 1781): GC_CONCURRENT freed 1771K, 40% free 11488K/19060K, paused 4ms+4ms, total 50ms
,D/dalvikvm( 1781): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1216): GC_CONCURRENT freed 1639K, 40% free 11451K/19060K, paused 5ms+3ms, total 50ms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/EnterpriseDeviceManagerService(  752): Creating context as user 0
,D/BootCompletedReceiver( 1781): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1781): Got an BootCompleted event.
,D/BootCompletedReceiver( 1781): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1781): onCreate
,I/CheckinService( 1781): Checking schedule, now: 1455027662309 next: 1455161282380
,I/CheckinService( 1781): active receiver: disabled
,W/dalvikvm( 1305): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1305): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1305): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1781): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1781): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0409
I/dalvikvm( 1305): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1305): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x00bb
,D/dalvikvm( 1305): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1305): VFY: unable to resolve instance field 161
,D/dalvikvm( 1305): VFY: replacing opcode 0x52 at 0x0006
,I/GCoreUlr( 1216): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 1781): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 1781): cancelUpdate (empty URL)
,I/SystemUpdateService( 1781): active receiver: disabled
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/EnterpriseDeviceManagerService(  752): Creating context as user 0
,I/dalvikvm( 1305): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1305): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x0059
,D/SystemUpdateService( 1781): onDestroy
,I/dalvikvm( 1305): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1305): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x0022
,I/GCoreUlr( 1216): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/AuthZenEventHandler( 1781): Handling event: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1216): Unbound from all location providers
,I/GCoreUlr( 1216): Place inference reporting - stopped
,I/GCoreUlr( 1216): DispatchingService.onDestroy()
,I/GCoreUlr( 1216): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1216): Unbound from all location providers
,I/GCoreUlr( 1216): Place inference reporting - stopped
,D/GCM     ( 1305): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/dalvikvm( 1305): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1305): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x001c
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1781): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1781): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x00bb
,E/BaseAppContext( 1781): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/dalvikvm( 1781): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1781): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x002f
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1305): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1305): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x0053
,I/AuthZen ( 1781): Fetching signing key...
,W/Auth    ( 1305): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AuthZen ( 1781): Signing key fetched successfully!
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1066): isPcwEnable = null
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/dalvikvm( 1305): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
,W/dalvikvm( 1305): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x001f
,I/GCM     ( 1305): GCM config loaded
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1305): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1305): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1305): VFY: replacing opcode 0x6e at 0x0041
,D/dalvikvm(  752): GC_EXPLICIT freed 1508K, 14% free 23434K/27000K, paused 5ms+11ms, total 125ms
,D/AuthZenTransactionCache( 1781): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1781): Clearing transaction cache
,D/PersistentNotificationBroadcastReceiver( 1216): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,V/AlarmManager(  752): waitForAlarm result :8
,D/WearableService( 1216): callingUid 10011, callindPid: 1216
,D/LocationInitializer( 1781): Restart initialization of location
D/Mms/Contact( 1666): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3350): PreDiscoveryHelper.mContentObserver - Contact Data changed
V/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1666): performUpdate:widgetCount=0
,E/MDM     ( 1216): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1305): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1305): Proximity feature is not enabled.
,D/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2403): getAllContactInfoList Start
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1216): No location to return for getLastLocation()
,W/FusedLocationProvider( 1216): location=null
V/AlarmManager(  752): waitForAlarm result :8
,E/MDM     ( 1216): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1781): Restart initialization of location
,D/ContactProvider( 2403): getAllContactInfoList End
D/AuthorizationBluetoothService( 1305): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1305): Proximity feature is not enabled.
,I/syncContacts( 2403): thread: 164, onChange
,E/SMD     (  241): DCD ON
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1216): No location to return for getLastLocation()
,W/FusedLocationProvider( 1216): location=null
V/AlarmManager(  752): waitForAlarm result :8
,I/SELinux ( 3845): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3845):  
,D/QuickConnect[1.1][2] ( 3350): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1666): sContactsObserver.onChange(),selfUpdate=false
,D/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3350): CONTACT_Info.getMyMobileNumber - null 
,D/dalvikvm(  248): GC_EXPLICIT freed 44K, 51% free 9509K/19060K, paused 2ms+3ms, total 25ms
,D/ContactProvider( 2403): getAllContactInfoList Start
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+2ms, total 19ms
,D/ContactProvider( 2403): getAllContactInfoList End
I/syncContacts( 2403): thread: 165, onChange
I/SELinux ( 3845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3845):  
I/SELinux ( 3845):  
,I/SELinux ( 3845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3845): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3845): >>>>> Normal User
E/dalvikvm( 3845): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
E/SELinux ( 3845): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+4ms, total 22ms
,D/TimaKeyStoreProvider( 3845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3845): Added TimaKesytore provider
,V/TaskCloserActivity( 3845): TaskCloserActivity enter()
W/ActivityManager(  752): Permission Denial: getCurrentUser() from pid=3845, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3858):  
,D/ConnectivityService(  752): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,I/SELinux ( 3858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3858):  
I/SELinux ( 3858):  
,I/SELinux ( 3858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3858): >>>>> Normal User
,E/dalvikvm( 3858): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3858): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3858): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3858): Added TimaKesytore provider
,D/SensorService(  752):   -0.0 -0.1 9.6
,D/FactoryTestApp( 3858): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3858): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3858): User mode
,I/knox    ( 3286): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/ActivityManager(  752): Killing 2794:com.sec.spp.push/u0a38 (adj 15): empty #43
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3286): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3286): KNOXAgentService : onCreate()
D/knox    ( 3286): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3286): KNOXAgentService. startJobThread() start
D/knox    ( 3286): KNOXAgentService. JobThread()
D/knox    ( 3286): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3286): KNOXAgentService. startJobThread() wait
D/knox    ( 3286): KNOXAgentService : onDestroy().
D/knox    ( 3286): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 3875): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3875):  
,I/SELinux ( 3875): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3875):  
I/SELinux ( 3875):  
,I/SELinux ( 3875): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3875): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3875): >>>>> Normal User
,E/dalvikvm( 3875): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3875): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3875): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3875): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3875): Added TimaKesytore provider
,E/MTPRx   ( 3875): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 3875): check value of boot_completed is1
,E/MTPRx   ( 3875): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3875): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3875): Status for mount/Unmount :removed
,E/MTPRx   ( 3875): SDcard is not available
,W/MTPRx   ( 3875): value of connected istrue
W/MTPRx   ( 3875): value of configured istrue
W/MTPRx   ( 3875): value of mtpEnabled istrue
,W/MTPRx   ( 3875): value of ptpEnabled isfalse
E/MTPRx   ( 3875): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3875): mFirstTime: false
,D/        ( 3875): MTP: reading debug level property
E/MTPRx   ( 3875):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 3875): Getting CryptionKey from JAVA
,E/MTPRx   ( 3875): currentUserId is 0
,E/MTPRx   ( 3875): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3875): usbMode is 0200
,E/MTPRx   ( 3875): is_secretmode is NOT 1
,W/MTPRx   ( 3875): Phone is lockedtrue
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/MTPRx   ( 3875):  inside checkKnoxStatus
,D/MTPRx   ( 3875):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3875): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3875): noti = 17
,E/MTPRx   ( 3875): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3875): else part ... so first time!!!
,E/MTPPlaObsrvr( 3875): inside setContext()
,E/MTPPlaObsrvr( 3875):  inside createplafiles
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,E/MTPPlaObsrvr( 3875): playlist count is0
,E/MTPPlaObsrvr( 3875):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3875):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3875): Inside registerContentObserver
E/MtpAdbObserver( 3875): inside setContext()
E/MtpAdbObserver( 3875): Inside registerContentObserver
,W/Settings( 3875): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3875): onCreate.
,E/MtpService( 3875): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3875): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3875): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3875): onStartCommand.
W/MTPRx   ( 3875): calling native method
,E/MTPJNIInterface( 3875): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3875): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3875): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3875): noti = 10
,E/MtpService( 3875): onStartCommand.
,W/MTPRx   ( 3875): calling native method
E/MTPRx   ( 3875): Checking the driver time out
E/MTPJNIInterface( 3875): noti = 2
,D/        ( 3875): deleting sockets before message queue initialization
,D/        ( 3875): event handler thread is created, so set the flag
E/MTPRx   ( 3875): called native method
E/MTPJNIInterface( 3875): setting Media scanner status0
E/MTPJNIInterface( 3875): After setting Media scanner status0
,W/MTPRx   ( 3875): notification from stack 1
E/MtpService( 3875): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3875): Getting media scanner status0
,E/MTPJNIInterface( 3875): DeviceName is Galaxy S5-2
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1458): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1458): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1458): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1458): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455049200000
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455027663791
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/knox    ( 3286): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3286): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3286): KNOXAgentService : onCreate()
,D/knox    ( 3286): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3286): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/knox    ( 3286): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
,D/knox    ( 3286): KNOXAgentService. startJobThread() start
D/knox    ( 3286): KNOXAgentService. JobThread()
D/knox    ( 3286): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3286): KNOXAgentService. startJobThread() wait
D/knox    ( 3286): KNOXAgentService : onDestroy().
,D/knox    ( 3286): ModuleBase.cancelAllAlarmManageModule()
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/knox    ( 3286): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/FileShare-Server( 3050): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 3050): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3898): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3898):  
,D/dalvikvm( 1458): GC_CONCURRENT freed 7439K, 47% free 10182K/19060K, paused 3ms+3ms, total 142ms
,I/SELinux ( 3898): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3898):  
I/SELinux ( 3898):  
,I/SELinux ( 3898): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3898): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3898): >>>>> Normal User
,E/dalvikvm( 3898): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3898): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3898): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3898): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3898): Added TimaKesytore provider
,I/System.out( 3898): Inside WakeupProvider
,I/System.out( 3898): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3898): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3898): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3898): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/Atfwd_Daemon(  290): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  290): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  290): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  290): Trying to register 8 commands:
,I/Atfwd_Daemon(  290): cmd0: +CKPD
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd1: +CTSA
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd2: +CFUN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd3: +CMAR
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd4: +CDIS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd5: +CRSL
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd6: +CSS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd7: $QCPWRDN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): Registered AT Commands event handler
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/DialogFlow( 3898): initQueue()
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1309): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1309): Adding local HEADSET profile
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1309): BTStateChangeCB is registed
,E/BluetoothHeadset( 1309): BluetoothHeadset service is binded
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1309): bindService called to Bluetooth SAP Service
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1309): PANU : true
,D/LocalBluetoothProfileManager( 1309): Adding local MAP profile
,D/BluetoothMap( 1309): Create BluetoothMap proxy object
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,D/dalvikvm( 1309): GC_CONCURRENT freed 7566K, 48% free 10045K/19060K, paused 3ms+3ms, total 46ms
W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1309): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1309): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1309): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BluetoothA2dp( 1309): Proxy object connected
D/A2dpProfile( 1309): Bluetooth service connected
D/BtConfig.SecureMode( 1943): isSecureModeOn:false
,D/HeadsetProfile( 1309): Bluetooth service connected
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1305): Proximity feature is not enabled.
,D/BluetoothInputDevice( 1309): Proxy object connected
,D/HidProfile( 1309): Bluetooth service connected
,D/BluetoothPan( 1309): BluetoothPAN Proxy object connected
,D/PanProfile( 1309): Bluetooth service connected
,D/BluetoothMap( 1309): Proxy object connected
,D/MapProfile( 1309): Bluetooth service connected
,D/BluetoothPbap( 1309): Proxy object connected
,D/PbapServerProfile( 1309): Bluetooth service connected
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,W/BluetoothAdapter( 1943): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1943): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1943): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/BtOppRfcommListener( 1943): Accept thread started.
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1309):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1309): showing allowed
,D/GKI_LINUX( 1943): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/dalvikvm(  752): GC_EXPLICIT freed 1389K, 14% free 23444K/27000K, paused 4ms+11ms, total 124ms
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/dalvikvm( 1204): GC_EXPLICIT freed 3900K, 48% free 10048K/19060K, paused 3ms+6ms, total 40ms
,I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  752): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=752
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/DisplayPowerController(  752): animation target = 45 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  752): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,I/SELinux ( 3941): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3941):  
,D/lights  (  752): lcd : 41 +
W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  752): [PWL] On : 0 (54551 ms ago)
I/PowerManagerService(  752): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  752): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1066, ws=null) (elapsedTime=16910)
I/PowerManagerService(  752): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=752, ws=WorkSource{1000}) (elapsedTime=23)
,E/MTPJNIInterface( 3875): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3875): SDcard is not available
D/lights  (  752): lcd : 41 -
,D/lights  (  752): lcd : 45 +
D/RampAnimator(  752): Light Animator Finished currentValue=45
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/lights  (  752): lcd : 45 -
E/MTPJNIInterface( 3875): Status for mount/Unmount :removed
E/MTPJNIInterface( 3875): SDcard is not available
E/SQLiteLog( 3875): (21) API call with NULL database connection pointer
E/SQLiteLog( 3875): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3875): (21) API call with NULL database connection pointer
E/SQLiteLog( 3875): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3875): (21) API call with NULL database connection pointer
E/SQLiteLog( 3875): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3875): (21) API call with NULL database connection pointer
E/SQLiteLog( 3875): (21) misuse at line 96833 of [00bb9c9ce4]
D/        ( 3875): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3875): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3875): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 3875): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
W/MTPRx   ( 3875): notification from stack 2
I/SELinux ( 3941): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3941):  
I/SELinux ( 3941):  
I/SELinux ( 3941): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3941): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3941): >>>>> Normal User
E/dalvikvm( 3941): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux ( 3941): [DEBUG] seapp_context_lookup: seinfoCategory = platform

```
