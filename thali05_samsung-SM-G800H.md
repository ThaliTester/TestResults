#### Test 587523534d3a10e_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 3566): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3566):  
I/SELinux ( 3566):  
I/SELinux ( 3566): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SELinux ( 3574): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3574):  
E/SELinux ( 3566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3566): >>>>> Normal User
E/dalvikvm( 3566): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
E/SELinux ( 3566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3566): in addTimaSignatureService
D/TimaKeyStoreProvider( 3566): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3566): Added TimaKesytore provider
E/SMD     (  243): DCD ON
I/SELinux ( 3574): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3574):  
I/SELinux ( 3574):  
I/SELinux ( 3574): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3574): >>>>> Normal User
E/dalvikvm( 3574): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
E/SELinux ( 3574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3574): in addTimaSignatureService
--------- beginning of /dev/log/system
W/ActivityManager(  767): Permission Denial: getCurrentUser() from pid=3566, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 3574): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3574): Added TimaKesytore provider
D/SSRMv2:SIOP(  767): SIOP:: AP = 330, Delta = 0
W/ContextImpl( 3574): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3600): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3600):  
I/SELinux ( 3600): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3600):  
I/SELinux ( 3600):  
I/SELinux ( 3600): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3600): >>>>> Normal User
E/dalvikvm( 3600): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3600): in addTimaSignatureService
D/TimaKeyStoreProvider( 3600): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3600): Added TimaKesytore provider
W/ActivityManager(  767): Permission Denial: getCurrentUser() from pid=3600, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3613): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3613):  
I/ActivityManager(  767): Killing 2057:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 3613): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3613):  
I/SELinux ( 3613):  
I/SELinux ( 3613): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3613): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3613): >>>>> Normal User
E/dalvikvm( 3613): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 3613): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 3613): in addTimaSignatureService
D/TimaKeyStoreProvider( 3613): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3613): Added TimaKesytore provider
I/ActivityManager(  767): Waited long enough for: ServiceRecord{42d01290 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
I/Intent to TravelDirActivity( 3613): inside TravelBroadcastReceiver
W/ActivityManager(  767): Permission Denial: getCurrentUser() from pid=3613, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  767): Killing 2794:com.policydm/1000 (adj 15): empty #43
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
W/BackupManagerService(  767): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1455029351987
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1455050880000
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/daemonapp( 1463): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1455050880000
D/AndroidRuntime( 3598): 
D/AndroidRuntime( 3598): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 3
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1455050880000
D/AndroidRuntime( 3598): CheckJNI is OFF
D/AndroidRuntime( 3598): setted country_code = Poland
D/AndroidRuntime( 3598): setted countryiso_code = PL
D/AndroidRuntime( 3598): setted sales_code = XEO
D/AndroidRuntime( 3598): readGMSProperty: start
D/AndroidRuntime( 3598): readGMSProperty: already setted!!
D/AndroidRuntime( 3598): readGMSProperty: end
D/AndroidRuntime( 3598): addProductProperty: start
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
D/dalvikvm( 3598): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3598): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3598): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3598): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3598): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 3625): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3625):  
I/SELinux ( 3625): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3625):  
I/SELinux ( 3625):  
I/SELinux ( 3625): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3625): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3625): >>>>> Normal User
E/dalvikvm( 3625): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3625): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3625): in addTimaSignatureService
D/TimaKeyStoreProvider( 3625): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3625): Added TimaKesytore provider
E/memtrack( 3598): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3598): failed to load memtrack module: -2
D/dalvikvm( 3598): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 3598): Calling main entry com.android.commands.am.Am
W/ActivityManager(  767): Permission Denial: getCurrentUser() from pid=3625, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 3598): Shutting down VM
D/dalvikvm( 3598): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 3ms
E/YouTube ( 3625): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/YouTube ( 3625): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3625): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3625): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3625): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3625): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3625): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  767): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  767): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  767): getStreamVolume 3 index 0
I/MediaRouter( 3625): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3625): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3625): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1455029352&data=screen_name%3D%3CAndroid_YT_Open_App%3E
I/System.out( 3625): Thread-358(HTTPLog):isShipBuild true
I/System.out( 3625): Thread-358(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3625): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/YouTube ( 3625): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
D/WifiDisplayAdapter(  767): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3625): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3625): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3625): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
I/SELinux ( 3686): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3686):  
D/YouTube ( 3625): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
I/ActivityManager(  767): Killing 2817:com.sec.spp.push/u0a38 (adj 15): empty #43
I/SELinux ( 3686): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3686):  
I/SELinux ( 3686):  
I/SELinux ( 3686): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3686): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3686): >>>>> Normal User
E/dalvikvm( 3686): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
E/SELinux ( 3686): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3686): in addTimaSignatureService
D/TimaKeyStoreProvider( 3686): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3686): Added TimaKesytore provider
D/YouTube ( 3625): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3625): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3625): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
W/ContextImpl( 3686): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3686): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3686): onCreate method
I/AtFwdService( 3686): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 3686): De-queing command
W/ContextImpl(  767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3711): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3711):  
I/GoogleConversionPing( 3625): Ping responded with response code 200
D/dalvikvm(  250): GC_EXPLICIT freed 44K, 49% free 9511K/18452K, paused 2ms+2ms, total 26ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9511K/18452K, paused 2ms+3ms, total 18ms
I/SELinux ( 3711): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3711):  
I/SELinux ( 3711):  
I/SELinux ( 3711): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3711): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3711): >>>>> Normal User
E/dalvikvm( 3711): >>>>> com.android.vending [ userId:0 | appId:10030 ]
E/SELinux ( 3711): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/AmoledAdjustTimer(  767): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9511K/18452K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 3711): in addTimaSignatureService
D/TimaKeyStoreProvider( 3711): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3711): Added TimaKesytore provider
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
I/dalvikvm( 3711): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3711): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x000e
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3711): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3711): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3711): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 3711): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3711): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3711): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3711): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3711): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3711): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3711): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3711): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3711): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3711): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3711): VFY: replacing opcode 0x6e at 0x0019
,D/Volley  ( 3711): [347] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3711): Skipping gmscore version check
,D/Volley  ( 3711): [354] DiskBasedCache.clear: Cache cleared.
,D/Finsky  ( 3711): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3711): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3711): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3711): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1754): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1754): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1754): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1754): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1754): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1754): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1754): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1754): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1754): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1754): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1754): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,W/InstanceID/Rpc( 1754): Found 10011
,D/FileApkUtils( 1754): Spent 59ms computing apk sha1.
,D/FileApkUtils( 1754): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1754): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1754): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1754): Reading stored module config
,D/GmsModuleFndr( 1754): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1754): Beginning module configuration check
,D/ChimeraCfgMgr( 1754): Module APKs unchanged, check complete
,E/dalvikvm( 1754): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1754): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1754): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1754): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1754): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1754): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1754): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1754): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1754): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1754): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1754): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1754): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1754): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1218): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1218): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1218): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1218): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1218): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1218): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1218): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1218): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1218): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1218): VFY: replacing opcode 0x6e at 0x0021
E/dalvikvm( 1754): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1754): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1754): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1218): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1218): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1218): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1218): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1754): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1754): Got an BootCompleted event.
,D/BootCompletedReceiver( 1754): Will NOT schedule AdAttestation signal task because it's disabled.
I/dalvikvm( 1319): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x001c
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1319): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x0053
,W/Auth    ( 1319): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/dalvikvm(  767): GC_EXPLICIT freed 1014K, 13% free 23349K/26584K, paused 6ms+9ms, total 137ms
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/dalvikvm( 1754): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1754): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1754): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1754): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1754): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1754): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1754): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1754): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1754): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,I/dalvikvm( 1319): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x001f
,I/CheckinService( 1754): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 455597616
,D/GCM     ( 1754): COMPAT: Multi user not supported
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1319): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1319): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1319): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1319): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x00bb
,I/dalvikvm( 1319): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x0041
I/GCoreUlr( 1754): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1218): DispatchingService.onCreate()
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/dalvikvm( 1319): GC_EXPLICIT freed 1242K, 43% free 10576K/18452K, paused 5ms+4ms, total 35ms
,D/GCM     ( 1319): COMPAT: Multi user not supported
,I/dalvikvm( 1319): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
,W/dalvikvm( 1319): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x000f
,I/CheckinService( 1754): Disabling old GoogleServicesFramework version
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1319): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x0010
,D/dalvikvm( 1754): GC_CONCURRENT freed 2230K, 39% free 11326K/18452K, paused 4ms+5ms, total 44ms
,D/SystemUpdateService( 1754): onCreate
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/dalvikvm( 1218): GC_CONCURRENT freed 1673K, 39% free 11430K/18452K, paused 7ms+5ms, total 60ms
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/EnterpriseDeviceManagerService(  767): Creating context as user 0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SystemUpdateService( 1754): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GCoreUlr( 1218): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/dalvikvm( 1754): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
,W/dalvikvm( 1754): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0409
I/CheckinService( 1754): Checking schedule, now: 1455029354232 next: 1455161282380
,I/CheckinService( 1754): active receiver: disabled
,V/AuthZen ( 1754): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1754): cancelUpdate (empty URL)
,I/SystemUpdateService( 1754): active receiver: disabled
,I/dalvikvm( 1754): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 1754): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x002b
,D/dalvikvm( 1319): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1319): VFY: unable to resolve instance field 161
,D/dalvikvm( 1319): VFY: replacing opcode 0x52 at 0x0006
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1319): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 1754): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4268cc70
,D/EnterpriseDeviceManagerService(  767): Creating context as user 0
,D/PersistentNotificationBroadcastReceiver( 1218): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AuthZenEventHandler( 1754): Handling event: android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1754): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4268cc70
,D/dalvikvm( 1754): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4268cc70, skipping init
,I/dalvikvm( 1319): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1319): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x0059
,D/SystemUpdateService( 1754): onDestroy
,I/dalvikvm( 1319): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1319): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x0022
,I/GCoreUlr( 1218): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1218): Unbound from all location providers
,I/GCoreUlr( 1218): Place inference reporting - stopped
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 1218): DispatchingService.onDestroy()
,I/GCoreUlr( 1218): Stopping handler for UlrDispSvcFast
I/dalvikvm( 1754): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1754): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x00bb
I/GCoreUlr( 1218): Unbound from all location providers
,I/GCoreUlr( 1218): Place inference reporting - stopped
,E/BaseAppContext( 1754): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/GCM     ( 1319): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/WearableService( 1218): callingUid 10011, callindPid: 1218
,E/MDM     ( 1218): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1754): Restart initialization of location
,I/dalvikvm( 1754): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1754): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x002f
,D/AuthorizationBluetoothService( 1319): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1319): Proximity feature is not enabled.
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1218): No location to return for getLastLocation()
,W/FusedLocationProvider( 1218): location=null
,I/AuthZen ( 1754): Fetching signing key...
,V/AlarmManager(  767): waitForAlarm result :8
,I/AuthZen ( 1754): Signing key fetched successfully!
,E/SMD     (  243): DCD ON
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,E/MDM     ( 1218): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1754): Restart initialization of location
,D/AuthorizationBluetoothService( 1319): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1319): Proximity feature is not enabled.
,D/AuthZenTransactionCache( 1754): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1754): Clearing transaction cache
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 1319): GCM config loaded
,W/GCoreFlp( 1218): No location to return for getLastLocation()
,W/FusedLocationProvider( 1218): location=null
V/AlarmManager(  767): waitForAlarm result :8
,V/AlarmManager(  767): waitForAlarm result :8
,D/SensorService(  767):   -0.1 -0.1 9.6
,I/SELinux ( 3830): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3830):  
,D/QuickConnect[1.1][2] ( 3348): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1668): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 1668): performUpdate:widgetCount=0
,D/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2396): getAllContactInfoList Start
,D/ContactProvider( 2396): getAllContactInfoList End
,I/syncContacts( 2396): thread: 164, onChange
,I/SELinux ( 3830): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3830):  
I/SELinux ( 3830):  
,I/SELinux ( 3830): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3830): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3830): >>>>> Normal User
,E/dalvikvm( 3830): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3830): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3830): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3830): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3830): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3348): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1668): sContactsObserver.onChange(),selfUpdate=false
,D/ContactProvider( 2396): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3348): CONTACT_Info.getMyMobileNumber - null 
,W/ActivityManager(  767): Permission Denial: getCurrentUser() from pid=3830, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3830): TaskCloserActivity enter()
,I/SELinux ( 3844): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3844):  
,D/ContactProvider( 2396): getAllContactInfoList End
,I/syncContacts( 2396): thread: 165, onChange
,I/SELinux ( 3844): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3844):  
I/SELinux ( 3844):  
,I/SELinux ( 3844): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3844): >>>>> Normal User
,E/dalvikvm( 3844): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3844): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3844): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3844): Added TimaKesytore provider
,D/FactoryTestApp( 3844): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3844): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3844): User mode
,I/ActivityManager(  767): Killing 2840:com.osp.app.signin/u0a43 (adj 15): empty #43
,I/knox    ( 3280): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3280): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3280): KNOXAgentService : onCreate()
,D/knox    ( 3280): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3280): KNOXAgentService. startJobThread() start
,D/knox    ( 3280): KNOXAgentService. JobThread()
,D/knox    ( 3280): KNOXAgentService. JobThread. notifyAll().
,W/ContextImpl( 3280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3280): KNOXAgentService. startJobThread() wait
,I/SELinux ( 3860): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3860):  
,D/knox    ( 3280): KNOXAgentService : onDestroy().
,D/knox    ( 3280): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 3860): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3860):  
I/SELinux ( 3860):  
,I/SELinux ( 3860): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3860): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3860): >>>>> Normal User
,E/dalvikvm( 3860): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3860): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3860): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3860): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3860): Added TimaKesytore provider
,D/ConnectivityService(  767): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,E/MTPRx   ( 3860): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3860): check value of boot_completed is1
,E/MTPRx   ( 3860): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3860): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3860): Status for mount/Unmount :removed
,E/MTPRx   ( 3860): SDcard is not available
W/MTPRx   ( 3860): value of connected istrue
W/MTPRx   ( 3860): value of configured istrue
W/MTPRx   ( 3860): value of mtpEnabled istrue
,W/MTPRx   ( 3860): value of ptpEnabled isfalse
E/MTPRx   ( 3860): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3860): mFirstTime: false
,D/        ( 3860): MTP: reading debug level property
E/MTPRx   ( 3860):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 3860): Getting CryptionKey from JAVA
,E/MTPRx   ( 3860): currentUserId is 0
,E/MTPRx   ( 3860): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3860): usbMode is 0200
,E/MTPRx   ( 3860): is_secretmode is NOT 1
,W/MTPRx   ( 3860): Phone is lockedtrue
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/MTPRx   ( 3860):  inside checkKnoxStatus
,D/MTPRx   ( 3860):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3860): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3860): noti = 17
,E/MTPRx   ( 3860): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3860): else part ... so first time!!!
,E/MTPPlaObsrvr( 3860): inside setContext()
,E/MTPPlaObsrvr( 3860):  inside createplafiles
,E/MTPPlaObsrvr( 3860): playlist count is0
,E/MTPPlaObsrvr( 3860):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3860):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 3860): Inside registerContentObserver
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,E/MtpAdbObserver( 3860): inside setContext()
E/MtpAdbObserver( 3860): Inside registerContentObserver
,W/Settings( 3860): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3860): onCreate.
,E/MtpService( 3860): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3860): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3860): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3860): onStartCommand.
E/MtpService( 3860): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3860): calling native method
,E/MTPJNIInterface( 3860): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3860): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3860): noti = 10
,E/MtpService( 3860): onStartCommand.
,W/MTPRx   ( 3860): calling native method
E/MTPRx   ( 3860): Checking the driver time out
E/MTPJNIInterface( 3860): noti = 2
,D/        ( 3860): deleting sockets before message queue initialization
D/        ( 3860): event handler thread is created, so set the flag
E/MTPRx   ( 3860): called native method
,E/MTPJNIInterface( 3860): Getting media scanner status0
E/MTPJNIInterface( 3860): setting Media scanner status0
E/MTPJNIInterface( 3860): After setting Media scanner status0
,W/MTPRx   ( 3860): notification from stack 1
E/MtpService( 3860): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3860): DeviceName is Galaxy S5-2
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455050880000
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455029355383
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,D/dalvikvm( 1463): GC_CONCURRENT freed 7447K, 45% free 10185K/18452K, paused 1ms+3ms, total 39ms
,D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3280): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3280): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 3280): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3280): KNOXAgentService : onCreate()
,D/knox    ( 3280): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3280): KNOXAgentService. startJobThread() start
,D/knox    ( 3280): KNOXAgentService. JobThread()
D/knox    ( 3280): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3280): KNOXAgentService. startJobThread() wait
D/knox    ( 3280): KNOXAgentService : onDestroy().
,D/knox    ( 3280): ModuleBase.cancelAllAlarmManageModule()
,D/knox    ( 3280): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
,W/ContextImpl( 3280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/knox    ( 3280): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3043): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3043): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3880): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3880):  
,I/SELinux ( 3880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3880):  
I/SELinux ( 3880):  
,I/SELinux ( 3880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3880): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3880): >>>>> Normal User
,E/dalvikvm( 3880): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3880): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3880): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3880): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3880): Added TimaKesytore provider
,I/System.out( 3880): Inside WakeupProvider
,I/System.out( 3880): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3880): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3880): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3880): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/Atfwd_Daemon(  291): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  291): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  291): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  291): Trying to register 8 commands:
,I/Atfwd_Daemon(  291): cmd0: +CKPD
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd1: +CTSA
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd2: +CFUN
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  291): cmd3: +CMAR
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd4: +CDIS
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd5: +CRSL
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd6: +CSS
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): cmd7: $QCPWRDN
I/Atfwd_Daemon(  291): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  291): Registered AT Commands event handler
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DialogFlow( 3880): initQueue()
,D/LocalBluetoothProfileManager( 1304): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1304): Adding local HEADSET profile
,E/BluetoothHeadset( 1304): BTStateChangeCB is registed
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1304): BluetoothHeadset service is binded
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/dalvikvm(  767): GC_EXPLICIT freed 1896K, 12% free 23496K/26584K, paused 4ms+9ms, total 116ms
,D/Bluetoothsap( 1304): bindService called to Bluetooth SAP Service
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1304): PANU : true
,D/LocalBluetoothProfileManager( 1304): Adding local MAP profile
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/BluetoothMap( 1304): Create BluetoothMap proxy object
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1304): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1304): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/dalvikvm( 1304): GC_CONCURRENT freed 7551K, 46% free 10082K/18452K, paused 3ms+6ms, total 58ms
,D/DockEventReceiver( 1304): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,D/BluetoothA2dp( 1304): Proxy object connected
,D/A2dpProfile( 1304): Bluetooth service connected
,D/BtConfig.SecureMode( 1946): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1319): Proximity feature is not enabled.
,D/HeadsetProfile( 1304): Bluetooth service connected
,D/BluetoothInputDevice( 1304): Proxy object connected
,D/HidProfile( 1304): Bluetooth service connected
,D/BluetoothPan( 1304): BluetoothPAN Proxy object connected
,D/PanProfile( 1304): Bluetooth service connected
,D/BluetoothMap( 1304): Proxy object connected
D/MapProfile( 1304): Bluetooth service connected
,D/BluetoothPbap( 1304): Proxy object connected
,D/PbapServerProfile( 1304): Bluetooth service connected
,W/BluetoothAdapter( 1946): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1946): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1946): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1946): Accept thread started.
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/dalvikvm( 1204): GC_EXPLICIT freed 3900K, 46% free 10047K/18452K, paused 2ms+5ms, total 41ms
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,E/MTPJNIInterface( 3860): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3860): SDcard is not available
,E/MTPJNIInterface( 3860): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3860): SDcard is not available
E/SQLiteLog( 3860): (21) API call with NULL database connection pointer
E/SQLiteLog( 3860): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3860): (21) API call with NULL database connection pointer
E/SQLiteLog( 3860): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3860): (21) API call with NULL database connection pointer
E/SQLiteLog( 3860): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3860): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3860): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3860): notification from stack 2
D/        ( 3860): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3860): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
,D/        ( 3860): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 3860): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed

```
