#### Test 58380500a584679_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
V/SmartcardService( 3562): main Received broadcast
V/SmartcardService( 3562): Starting smartcard service after boot completed
--------- beginning of /dev/log/system
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3562, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3578): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3578):  
I/ActivityManager(  787): Waited long enough for: ServiceRecord{42b41578 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,E/STK2    ( 1239): onReceive android.intent.action.BOOT_COMPLETED
I/SELinux ( 3578): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3578):  
I/SELinux ( 3578):  
I/SELinux ( 3578): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3578): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3578): >>>>> Normal User
E/dalvikvm( 3578): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
I/SELinux ( 3584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3584):  
E/SELinux ( 3578): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/TimaKeyStoreProvider( 3578): in addTimaSignatureService
D/TimaKeyStoreProvider( 3578): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3578): Added TimaKesytore provider
I/SELinux ( 3584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3584):  
I/SELinux ( 3584):  
I/SELinux ( 3584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3584): >>>>> Normal User
E/dalvikvm( 3584): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
E/SELinux ( 3584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3584): in addTimaSignatureService
D/TimaKeyStoreProvider( 3584): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3584): Added TimaKesytore provider
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3578, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 3584): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3609):  
I/SELinux ( 3609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3609):  
I/SELinux ( 3609):  
I/SELinux ( 3609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3609): >>>>> Normal User
E/dalvikvm( 3609): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3609): in addTimaSignatureService
D/TimaKeyStoreProvider( 3609): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3609): Added TimaKesytore provider
D/SSRMv2:SIOP(  787): SIOP:: AP = 330, Delta = 10
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3609, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3621): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3621):  
I/ActivityManager(  787): Killing 2049:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 3621): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3621):  
I/SELinux ( 3621):  
I/SELinux ( 3621): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3621): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3621): >>>>> Normal User
E/dalvikvm( 3621): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 3621): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/SensorService(  787):   -0.0 -0.1 9.6
D/TimaKeyStoreProvider( 3621): in addTimaSignatureService
D/TimaKeyStoreProvider( 3621): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3621): Added TimaKesytore provider
D/AndroidRuntime( 3596): 
D/AndroidRuntime( 3596): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3596): CheckJNI is OFF
D/AndroidRuntime( 3596): setted country_code = Poland
D/AndroidRuntime( 3596): setted countryiso_code = PL
D/AndroidRuntime( 3596): setted sales_code = XEO
D/AndroidRuntime( 3596): readGMSProperty: start
D/AndroidRuntime( 3596): readGMSProperty: already setted!!
D/AndroidRuntime( 3596): readGMSProperty: end
D/AndroidRuntime( 3596): addProductProperty: start
I/Intent to TravelDirActivity( 3621): inside TravelBroadcastReceiver
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3621, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 3596): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3596): Added shared lib libjavacore.so 0x0
I/ActivityManager(  787): Killing 2747:com.policydm/1000 (adj 15): empty #43
D/dalvikvm( 3596): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3596): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3596): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/daemonapp( 1464): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1464): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1464): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1464): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1464): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1464): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/BackupManagerService(  787): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/daemonapp( 1464): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1464): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
E/SMD     (  240): DCD ON
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1455067483136
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1455089040000
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/daemonapp( 1464): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1455089040000
D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1464): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1455089040000
D/comdaemonstockapp( 1464): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1464): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/SELinux ( 3640): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3640):  
I/SELinux ( 3640): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3640):  
I/SELinux ( 3640):  
I/SELinux ( 3640): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3640): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3640): >>>>> Normal User
E/dalvikvm( 3640): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/memtrack( 3596): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3596): failed to load memtrack module: -2
E/SELinux ( 3640): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3640): in addTimaSignatureService
D/TimaKeyStoreProvider( 3640): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3640): Added TimaKesytore provider
D/dalvikvm( 3596): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 3596): Calling main entry com.android.commands.am.Am
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3640, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 3596): Shutting down VM
D/dalvikvm( 3596): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
I/ActivityManager(  787): Waited long enough for: ServiceRecord{4302dfe8 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
E/YouTube ( 3640): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/YouTube ( 3640): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3640): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3640): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3640): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3640): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3640): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  787): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  787): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  787): getStreamVolume 3 index 0
I/MediaRouter( 3640): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3640): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3640): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1455067483&data=screen_name%3D%3CAndroid_YT_Open_App%3E
I/System.out( 3640): Thread-358(HTTPLog):isShipBuild true
I/System.out( 3640): Thread-358(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3640): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3640): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/YouTube ( 3640): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3640): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3640): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/WifiDisplayAdapter(  787): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3640): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
I/SELinux ( 3702): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3702):  
I/ActivityManager(  787): Killing 2764:com.sec.spp.push/u0a38 (adj 15): empty #43
D/YouTube ( 3640): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3640): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3640): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/SELinux ( 3702): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3702):  
I/SELinux ( 3702):  
I/SELinux ( 3702): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3702): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3702): >>>>> Normal User
E/dalvikvm( 3702): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
E/SELinux ( 3702): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3702): in addTimaSignatureService
D/TimaKeyStoreProvider( 3702): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3702): Added TimaKesytore provider
I/GoogleConversionPing( 3640): Ping responded with response code 200
W/ContextImpl( 3702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3702): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3702): onCreate method
I/AtFwdService( 3702): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 3702): De-queing command
W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3719): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3719):  
D/dalvikvm(  247): GC_EXPLICIT freed 44K, 51% free 9508K/19040K, paused 3ms+2ms, total 26ms
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9508K/19040K, paused 2ms+2ms, total 19ms
I/SELinux ( 3719): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3719):  
I/SELinux ( 3719):  
I/SELinux ( 3719): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3719): >>>>> Normal User
E/dalvikvm( 3719): >>>>> com.android.vending [ userId:0 | appId:10030 ]
E/SELinux ( 3719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9508K/19040K, paused 1ms+3ms, total 18ms
D/TimaKeyStoreProvider( 3719): in addTimaSignatureService
D/TimaKeyStoreProvider( 3719): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3719): Added TimaKesytore provider
I/dalvikvm( 3719): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3719): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 3719): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3719): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3719): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x000a
,D/AmoledAdjustTimer(  787): prevTemp = 285, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3719): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3719): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3719): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3719): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3719): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3719): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 3719): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0019
,D/Volley  ( 3719): [347] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3719): Skipping gmscore version check
,D/Finsky  ( 3719): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Volley  ( 3719): [354] DiskBasedCache.clear: Cache cleared.
,D/Finsky  ( 3719): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3719): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3719): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
,D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1759): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1759): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1759): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1759): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1759): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1759): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1759): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1759): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1759): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1759): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1759): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,W/InstanceID/Rpc( 1759): Found 10011
,D/FileApkUtils( 1759): Spent 78ms computing apk sha1.
,D/FileApkUtils( 1759): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1759): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1759): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1759): Reading stored module config
,D/GmsModuleFndr( 1759): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1759): Beginning module configuration check
,D/ChimeraCfgMgr( 1759): Module APKs unchanged, check complete
,E/dalvikvm( 1759): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1759): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1759): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1759): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1759): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1759): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1759): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1759): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1219): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1219): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1219): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1219): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1759): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1759): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1759): VFY: replacing opcode 0x1f at 0x000e
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/dalvikvm(  787): GC_EXPLICIT freed 966K, 14% free 23325K/26960K, paused 5ms+9ms, total 117ms
,E/dalvikvm( 1759): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1759): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1759): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1759): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1759): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1759): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1759): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1759): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
I/dalvikvm( 1320): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x001c
,D/GCM     ( 1759): COMPAT: Multi user not supported
,I/CheckinService( 1759): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 493728735
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1320): GC_EXPLICIT freed 795K, 46% free 10378K/19040K, paused 5ms+4ms, total 34ms
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1759): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1219): DispatchingService.onCreate()
,I/CheckinService( 1759): Disabling old GoogleServicesFramework version
,D/GCM     ( 1320): COMPAT: Multi user not supported
,I/dalvikvm( 1320): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1320): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 1759): GC_CONCURRENT freed 1654K, 41% free 11304K/19040K, paused 3ms+9ms, total 61ms
D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1759): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/EnterpriseDeviceManagerService(  787): Creating context as user 0
I/dalvikvm( 1320): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x0010
,I/CheckinService( 1759): Checking schedule, now: 1455067485340 next: 1455161282380
,I/CheckinService( 1759): active receiver: disabled
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1759): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,I/GCoreUlr( 1219): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/BootCompletedReceiver( 1759): Got an BootCompleted event.
,D/BootCompletedReceiver( 1759): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1759): onCreate
,D/SystemUpdateService( 1759): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1759): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0409
,W/dalvikvm( 1320): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1320): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1219): GC_CONCURRENT freed 1676K, 41% free 11422K/19040K, paused 6ms+4ms, total 53ms
,W/dalvikvm( 1320): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1320): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x00bb
,V/AuthZen ( 1759): Handling intent: android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService(  787): Creating context as user 0
I/dalvikvm( 1759): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x002b
D/dalvikvm( 1320): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1320): VFY: unable to resolve instance field 161
,D/dalvikvm( 1320): VFY: replacing opcode 0x52 at 0x0006
,I/SystemUpdateService( 1759): cancelUpdate (empty URL)
,I/SystemUpdateService( 1759): active receiver: disabled
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1219): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 1759): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42658e50
,D/SystemUpdateService( 1759): onDestroy
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,D/AuthZenEventHandler( 1759): Handling event: android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1320): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1320): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x0059
I/GCoreUlr( 1219): DispatchingService.onDestroy()
,I/GCoreUlr( 1219): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,I/EventLogService( 1759): Aggregate from 1455065677077 (log), 1455065677077 (data)
D/dalvikvm( 1759): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42658e50
,D/dalvikvm( 1759): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42658e50, skipping init
,I/dalvikvm( 1320): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1320): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x0022
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1759): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x00bb
I/dalvikvm( 1320): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x0053
,D/GCM     ( 1320): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/BaseAppContext( 1759): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/dalvikvm( 1759): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x002f
,I/dalvikvm( 1320): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x001f
,I/AuthZen ( 1759): Fetching signing key...
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1320): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x0041
,W/Auth    ( 1320): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1067): isPcwEnable = null
,I/AuthZen ( 1759): Signing key fetched successfully!
,D/PersistentNotificationBroadcastReceiver( 1219): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,I/GCM     ( 1320): GCM config loaded
,D/WearableService( 1219): callingUid 10011, callindPid: 1219
,E/MDM     ( 1219): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1759): Restart initialization of location
,D/AuthZenTransactionCache( 1759): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1759): Clearing transaction cache
D/AuthorizationBluetoothService( 1320): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1320): Proximity feature is not enabled.
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,V/AlarmManager(  787): waitForAlarm result :8
,E/MDM     ( 1219): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1759): Restart initialization of location
,D/AuthorizationBluetoothService( 1320): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1320): Proximity feature is not enabled.
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,V/AlarmManager(  787): waitForAlarm result :8
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  787): waitForAlarm result :8
,D/dalvikvm( 1759): GC_CONCURRENT freed 1661K, 39% free 11625K/19040K, paused 4ms+5ms, total 41ms
,I/SELinux ( 3840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3840):  
,D/QuickConnect[1.1][2] ( 3355): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1672): performUpdate:widgetCount=0
,D/Mms/Contact( 1672): sContactsObserver.onChange(),selfUpdate=false
,E/SMD     (  240): DCD ON
,D/ContactProvider( 2405): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2405): getAllContactInfoList End
,I/syncContacts( 2405): thread: 164, onChange
,I/SELinux ( 3840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3840):  
I/SELinux ( 3840):  
,I/SELinux ( 3840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3840): >>>>> Normal User
,E/dalvikvm( 3840): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Mms/Contact( 1672): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3355): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getMyMobileNumber - 
,D/TimaKeyStoreProvider( 3840): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3840): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3840): Added TimaKesytore provider
,D/ContactProvider( 2405): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3355): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2405): getAllContactInfoList End
,I/syncContacts( 2405): thread: 165, onChange
,V/TaskCloserActivity( 3840): TaskCloserActivity enter()
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=3840, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3857): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3857):  
,D/SensorService(  787):   -0.1 -0.1 9.6
,I/SELinux ( 3857): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3857):  
I/SELinux ( 3857):  
,I/SELinux ( 3857): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3857): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3857): >>>>> Normal User
,E/dalvikvm( 3857): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3857): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3857): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3857): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3857): Added TimaKesytore provider
,D/FactoryTestApp( 3857): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3857): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3857): User mode
,I/SELinux ( 3869): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3869):  
I/ActivityManager(  787): Killing 2791:com.osp.app.signin/u0a43 (adj 15): empty #43
,D/ConnectivityService(  787): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 3869): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3869):  
I/SELinux ( 3869):  
,I/SELinux ( 3869): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3869): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3869): >>>>> Normal User
,E/dalvikvm( 3869): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3869): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3869): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3869): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3869): Added TimaKesytore provider
,E/MTPRx   ( 3869): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3869): check value of boot_completed is1
,E/MTPRx   ( 3869): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3869): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3869): Status for mount/Unmount :removed
,E/MTPRx   ( 3869): SDcard is not available
,W/MTPRx   ( 3869): value of connected istrue
W/MTPRx   ( 3869): value of configured istrue
W/MTPRx   ( 3869): value of mtpEnabled istrue
,W/MTPRx   ( 3869): value of ptpEnabled isfalse
,E/MTPRx   ( 3869): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3869): mFirstTime: false
,D/        ( 3869): MTP: reading debug level property
,E/MTPRx   ( 3869):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3869): Getting CryptionKey from JAVA
,E/MTPRx   ( 3869): currentUserId is 0
,E/MTPRx   ( 3869): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3869): usbMode is 0200
,E/MTPRx   ( 3869): is_secretmode is NOT 1
,W/MTPRx   ( 3869): Phone is lockedtrue
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/MTPRx   ( 3869):  inside checkKnoxStatus
,D/MTPRx   ( 3869):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3869): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3869): noti = 17
,E/MTPRx   ( 3869): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3869): else part ... so first time!!!
,E/MTPPlaObsrvr( 3869): inside setContext()
,E/MTPPlaObsrvr( 3869):  inside createplafiles
,E/MTPPlaObsrvr( 3869): playlist count is0
,E/MTPPlaObsrvr( 3869):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3869):  inside deleteing plas createplafiles
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,E/MTPPlaObsrvr( 3869): Inside registerContentObserver
,E/MtpAdbObserver( 3869): inside setContext()
E/MtpAdbObserver( 3869): Inside registerContentObserver
,W/Settings( 3869): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3869): onCreate.
,E/MtpService( 3869): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3869): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3869): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3869): onStartCommand.
W/MTPRx   ( 3869): calling native method
,E/MtpService( 3869): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3869): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3869): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3869): noti = 10
,I/knox    ( 3276): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/MtpService( 3869): onStartCommand.
W/MTPRx   ( 3869): calling native method
E/MTPRx   ( 3869): Checking the driver time out
E/MTPJNIInterface( 3869): noti = 2
,D/        ( 3869): deleting sockets before message queue initialization
,D/        ( 3869): event handler thread is created, so set the flag
,E/MTPRx   ( 3869): called native method
E/MTPJNIInterface( 3869): setting Media scanner status0
,E/MTPJNIInterface( 3869): After setting Media scanner status0
,W/ContextImpl( 3276): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/MtpService( 3869): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3869): Getting media scanner status0
W/MTPRx   ( 3869): notification from stack 1
E/MTPJNIInterface( 3869): DeviceName is Galaxy S5-2
I/knox    ( 3276): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3276): KNOXAgentService : onCreate()
D/knox    ( 3276): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3276): KNOXAgentService. startJobThread() start
D/knox    ( 3276): KNOXAgentService. JobThread()
D/knox    ( 3276): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3276): KNOXAgentService. startJobThread() wait
D/knox    ( 3276): KNOXAgentService : onDestroy().
D/knox    ( 3276): ModuleBase.cancelAllAlarmManageModule()
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1464): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1464): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1464): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1464): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455089040000
,D/daemonapp( 1464): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455067486769
,D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1464): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1464): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/AuthorizationBluetoothService( 1320): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3276): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3276): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3276): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/knox    ( 3276): KNOXAgentService : onCreate()
,D/knox    ( 3276): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3276): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/dalvikvm( 1464): GC_CONCURRENT freed 7303K, 46% free 10354K/19040K, paused 3ms+12ms, total 89ms
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/FileShare-Server( 3024): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 3024): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/knox    ( 3276): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3276): KNOXAgentService. startJobThread() start
,D/knox    ( 3276): KNOXAgentService. JobThread()
D/knox    ( 3276): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3276): KNOXAgentService. startJobThread() wait
,I/knox    ( 3276): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
,I/SELinux ( 3905): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3905):  
,D/knox    ( 3276): KNOXAgentService : onDestroy().
,D/knox    ( 3276): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 3905): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3905):  
I/SELinux ( 3905):  
,I/SELinux ( 3905): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3905): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3905): >>>>> Normal User
,E/dalvikvm( 3905): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3905): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3905): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3905): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3905): Added TimaKesytore provider
,I/System.out( 3905): Inside WakeupProvider
,I/System.out( 3905): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3905): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3905): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3905): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/dalvikvm(  787): GC_EXPLICIT freed 1919K, 13% free 23480K/26960K, paused 4ms+10ms, total 121ms
,I/Atfwd_Daemon(  288): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  288): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  288): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  288): Trying to register 8 commands:
,I/Atfwd_Daemon(  288): cmd0: +CKPD
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd1: +CTSA
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd2: +CFUN
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd3: +CMAR
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd4: +CDIS
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd5: +CRSL
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd6: +CSS
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): cmd7: $QCPWRDN
I/Atfwd_Daemon(  288): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  288): Registered AT Commands event handler
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3905): initQueue()
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1306): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1306): Adding local HEADSET profile
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1306): BTStateChangeCB is registed
,E/BluetoothHeadset( 1306): BluetoothHeadset service is binded
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 1306): PANU : true
D/LocalBluetoothProfileManager( 1306): Adding local MAP profile
,D/BluetoothMap( 1306): Create BluetoothMap proxy object
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,D/dalvikvm( 1207): GC_EXPLICIT freed 3900K, 48% free 10044K/19040K, paused 2ms+5ms, total 38ms
,D/dalvikvm( 1306): GC_CONCURRENT freed 7551K, 48% free 10058K/19040K, paused 3ms+2ms, total 54ms
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
E/MTPJNIInterface( 3869): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3869): SDcard is not available
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 1306): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 1306): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
D/BluetoothA2dp( 1306): Proxy object connected
D/A2dpProfile( 1306): Bluetooth service connected
D/BtConfig.SecureMode( 1945): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1320): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1320): Proximity feature is not enabled.
,D/HeadsetProfile( 1306): Bluetooth service connected
,D/BluetoothInputDevice( 1306): Proxy object connected
D/HidProfile( 1306): Bluetooth service connected
E/MTPJNIInterface( 3869): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3869): SDcard is not available
E/SQLiteLog( 3869): (21) API call with NULL database connection pointer
E/SQLiteLog( 3869): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3869): (21) API call with NULL database connection pointer
E/SQLiteLog( 3869): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3869): (21) API call with NULL database connection pointer
E/SQLiteLog( 3869): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3869): (21) API call with NULL database connection pointer
E/SQLiteLog( 3869): (21) misuse at line 96833 of [00bb9c9ce4]
W/MTPRx   ( 3869): notification from stack 2
D/        ( 3869): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3869): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3869): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3869): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
