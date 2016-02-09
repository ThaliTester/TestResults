#### Test 584164489c56086_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main,
E/SMD     (  242): DCD ON
--------- beginning of /dev/log/system
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3535, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3565):  
I/ActivityManager(  769): Waited long enough for: ServiceRecord{4314fcf0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
D/NotiRemoteService( 3535): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
D/NotiRemoteService( 3535): connectToPeelService 0
W/ContextImpl( 3535): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
D/NotiRemoteService( 3535): onServiceOn() mServiceState = 1
D/NotiRemoteService( 3535): Send action to self com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3535): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3535): feature is Off. Stop service
D/NotiRemoteService( 3535): Send action to self com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3535): action com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3535): onDestroy()
D/NotiRemoteService( 3535): mOrientationChangeReceier was not registered
I/SELinux ( 3565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3565):  
I/SELinux ( 3565):  
I/SELinux ( 3565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3565): >>>>> Normal User
E/dalvikvm( 3565): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
E/SELinux ( 3565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3565): in addTimaSignatureService
D/TimaKeyStoreProvider( 3565): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3565): Added TimaKesytore provider
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3565, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
V/SmartcardService( 3565): main Received broadcast
V/SmartcardService( 3565): Starting smartcard service after boot completed
I/SELinux ( 3588): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3588):  
E/STK2    ( 1238): onReceive android.intent.action.BOOT_COMPLETED
D/AndroidRuntime( 3557): 
D/AndroidRuntime( 3557): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3557): CheckJNI is OFF
I/SELinux ( 3588): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3588):  
I/SELinux ( 3588):  
I/SELinux ( 3588): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/AndroidRuntime( 3557): setted country_code = Poland
E/SELinux ( 3588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/AndroidRuntime( 3557): setted countryiso_code = PL
E/dalvikvm( 3588): >>>>> Normal User
E/dalvikvm( 3588): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
D/AndroidRuntime( 3557): setted sales_code = XEO
D/AndroidRuntime( 3557): readGMSProperty: start
D/AndroidRuntime( 3557): readGMSProperty: already setted!!
D/AndroidRuntime( 3557): readGMSProperty: end
D/AndroidRuntime( 3557): addProductProperty: start
E/SELinux ( 3588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 3600): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3600):  
D/TimaKeyStoreProvider( 3588): in addTimaSignatureService
D/dalvikvm( 3557): Trying to load lib libjavacore.so 0x0
D/TimaKeyStoreProvider( 3588): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3588): Added TimaKesytore provider
D/dalvikvm( 3557): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3557): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3557): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3557): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 3600): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3600):  
I/SELinux ( 3600):  
I/SELinux ( 3600): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3600): >>>>> Normal User
E/dalvikvm( 3600): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
E/SELinux ( 3600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3588, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 3600): in addTimaSignatureService
D/TimaKeyStoreProvider( 3600): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3600): Added TimaKesytore provider
W/ContextImpl( 3600): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3624): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3624):  
E/memtrack( 3557): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3557): failed to load memtrack module: -2
I/SELinux ( 3624): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3624):  
I/SELinux ( 3624):  
I/SELinux ( 3624): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3624): >>>>> Normal User
E/dalvikvm( 3624): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3557): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/TimaKeyStoreProvider( 3624): in addTimaSignatureService
D/TimaKeyStoreProvider( 3624): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3624): Added TimaKesytore provider
D/AndroidRuntime( 3557): Calling main entry com.android.commands.am.Am
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3624, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3642):  
I/ActivityManager(  769): Killing 2045:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 3642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3642):  
I/SELinux ( 3642):  
I/SELinux ( 3642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/AndroidRuntime( 3557): Shutting down VM
E/SELinux ( 3642): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3642): >>>>> Normal User
E/dalvikvm( 3642): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
D/dalvikvm( 3557): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
E/SELinux ( 3642): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 3642): in addTimaSignatureService
D/TimaKeyStoreProvider( 3642): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3642): Added TimaKesytore provider
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3642, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
I/Intent to TravelDirActivity( 3642): inside TravelBroadcastReceiver
I/ActivityManager(  769): Killing 2754:com.policydm/1000 (adj 15): empty #43
D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/BackupManagerService(  769): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1455009579352
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1455031140000
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/daemonapp( 1465): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1455031140000
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1465): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1455031140000
D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/SELinux ( 3654): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3654):  
I/SELinux ( 3654): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3654):  
I/SELinux ( 3654):  
I/SELinux ( 3654): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3654): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3654): >>>>> Normal User
E/dalvikvm( 3654): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3654): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3654): in addTimaSignatureService
D/TimaKeyStoreProvider( 3654): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3654): Added TimaKesytore provider
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3654, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
E/YouTube ( 3654): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/YouTube ( 3654): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/AmoledAdjustTimer(  769): prevTemp = 291, currTemp = 293, prevStep = 4, currStep = 4
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3654): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3654): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3654): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
D/YouTube ( 3654): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3654): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  769): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  769): getStreamVolume 3 index 0
I/MediaRouter( 3654): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  769): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3654): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3654): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1455009580&data=screen_name%3D%3CAndroid_YT_Open_App%3E
I/System.out( 3654): Thread-358(HTTPLog):isShipBuild true
I/System.out( 3654): Thread-358(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 3654): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/YouTube ( 3654): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3654): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3654): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/WifiDisplayAdapter(  769): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/YouTube ( 3654): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 3654): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,I/SELinux ( 3706): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3706):  
,I/ActivityManager(  769): Killing 2773:com.sec.spp.push/u0a38 (adj 15): empty #43
,D/YouTube ( 3654): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3654): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3654): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/SELinux ( 3706): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3706):  
I/SELinux ( 3706):  
,I/SELinux ( 3706): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3706): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3706): >>>>> Normal User
,E/dalvikvm( 3706): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
,E/SELinux ( 3706): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3706): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3706): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3706): Added TimaKesytore provider
,I/GoogleConversionPing( 3654): Ping responded with response code 200
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3706): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3706): onCreate method
,I/AtFwdService( 3706): Instantiate AtCmdFwd Service
,D/AtCkpdCmdHandler( 3706): De-queing command
W/ContextImpl(  769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3731): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3731):  
,D/dalvikvm(  249): GC_EXPLICIT freed 44K, 50% free 9507K/18988K, paused 2ms+2ms, total 25ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9507K/18988K, paused 2ms+2ms, total 19ms
,I/SELinux ( 3731): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3731):  
I/SELinux ( 3731):  
,I/SELinux ( 3731): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3731): >>>>> Normal User
,E/dalvikvm( 3731): >>>>> com.android.vending [ userId:0 | appId:10030 ]
,E/SELinux ( 3731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9507K/18988K, paused 1ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 3731): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3731): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3731): Added TimaKesytore provider
,I/dalvikvm( 3731): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 3731): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3731): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3731): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 3731): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 3731): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3731): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3731): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3731): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3731): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3731): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3731): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3731): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3731): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 3731): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3731): VFY: replacing opcode 0x6e at 0x0019
,D/Volley  ( 3731): [347] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3731): Skipping gmscore version check
,D/Volley  ( 3731): [354] DiskBasedCache.clear: Cache cleared.
,D/dalvikvm(  769): GC_EXPLICIT freed 918K, 13% free 23389K/26676K, paused 4ms+10ms, total 111ms
,D/Finsky  ( 3731): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3731): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3731): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3731): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1641): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1641): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1641): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1641): VFY: replacing opcode 0x62 at 0x0021
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1641): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1641): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1641): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1641): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1641): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
,I/dalvikvm( 1641): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1641): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,D/FileApkUtils( 1641): Spent 67ms computing apk sha1.
,D/FileApkUtils( 1641): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1641): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1641): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1641): Reading stored module config
D/SSRMv2:SIOP(  769): SIOP:: AP = 320, Delta = -10
,W/InstanceID/Rpc( 1641): Found 10011
,D/GmsModuleFndr( 1641): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1641): Beginning module configuration check
,D/ChimeraCfgMgr( 1641): Module APKs unchanged, check complete
,E/dalvikvm( 1641): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1641): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1641): VFY: replacing opcode 0x22 at 0x00af
,W/dalvikvm( 1641): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1641): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1641): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1641): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/dalvikvm( 1641): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1641): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1641): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1641): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1641): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1641): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
E/dalvikvm( 1215): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1215): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 1215): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1215): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1215): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1215): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1215): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,I/dalvikvm( 1215): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm( 1215): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1215): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1215): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1215): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1641): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1641): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1641): VFY: replacing opcode 0x1f at 0x000e
,D/ChimeraCfgMgr( 1641): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1641): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1641): Got an BootCompleted event.
,D/dalvikvm( 1292): GC_EXPLICIT freed 2131K, 44% free 10695K/18988K, paused 2ms+5ms, total 34ms
,D/BootCompletedReceiver( 1641): Will NOT schedule AdAttestation signal task because it's disabled.
,E/dalvikvm( 1641): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1641): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1641): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1641): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1641): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x0004
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 1641): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1641): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1641): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1641): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/dalvikvm( 1641): GC_CONCURRENT freed 2243K, 41% free 11290K/18988K, paused 7ms+4ms, total 45ms
,D/GCM     ( 1641): COMPAT: Multi user not supported
,I/CheckinService( 1641): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 435824969
,I/CheckinService( 1641): Disabling old GoogleServicesFramework version
I/dalvikvm( 1292): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1292): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x0010
,E/SMD     (  242): DCD ON
,I/GCoreUlr( 1641): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1215): DispatchingService.onCreate()
,D/SystemUpdateService( 1641): onCreate
,D/SystemUpdateService( 1641): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1641): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1641): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x0409
I/CheckinService( 1641): Checking schedule, now: 1455009581501 next: 1455161282380
,I/CheckinService( 1641): active receiver: disabled
,V/AuthZen ( 1641): Handling intent: android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService(  769): Creating context as user 0
,I/dalvikvm( 1641): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 1641): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x002b
,D/dalvikvm( 1215): GC_CONCURRENT freed 1694K, 40% free 11438K/18988K, paused 3ms+8ms, total 50ms
D/dalvikvm( 1292): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1292): VFY: unable to resolve instance field 161
,D/dalvikvm( 1292): VFY: replacing opcode 0x52 at 0x0006
,I/SystemUpdateService( 1641): cancelUpdate (empty URL)
,I/SystemUpdateService( 1641): active receiver: disabled
,I/GCoreUlr( 1215): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1641): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425be338
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1641): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425be338
,D/dalvikvm( 1641): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x425be338, skipping init
,D/AuthZenEventHandler( 1641): Handling event: android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService(  769): Creating context as user 0
I/dalvikvm( 1292): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1292): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x0059
,D/SystemUpdateService( 1641): onDestroy
,D/dalvikvm( 1292): null clazz in OP_INSTANCE_OF, single-stepping
,I/GCoreUlr( 1215): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/dalvikvm( 1292): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1292): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x0022
I/GCoreUlr( 1215): Unbound from all location providers
,I/GCoreUlr( 1215): Place inference reporting - stopped
,I/GCoreUlr( 1215): DispatchingService.onDestroy()
,I/GCoreUlr( 1215): Stopping handler for UlrDispSvcFast
,W/BaseAppContext( 1641): Using Auth Proxy for data requests.
I/GCoreUlr( 1215): Unbound from all location providers
,I/GCoreUlr( 1215): Place inference reporting - stopped
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1641): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1641): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1641): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x00bb
,E/BaseAppContext( 1641): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/GCM     ( 1292): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1641): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1641): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1641): VFY: replacing opcode 0x6e at 0x002f
,I/dalvikvm( 1292): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1292): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x0053
,I/AuthZen ( 1641): Fetching signing key...
,W/Auth    ( 1292): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AuthZen ( 1641): Signing key fetched successfully!
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1066): isPcwEnable = null
,W/BaseAppContext( 1641): Using Auth Proxy for data requests.
,D/PersistentNotificationBroadcastReceiver( 1215): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AuthZenTransactionCache( 1641): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1641): Clearing transaction cache
,D/WearableService( 1215): callingUid 10011, callindPid: 1215
,I/GCM     ( 1292): GCM config loaded
,E/MDM     ( 1215): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1641): Restart initialization of location
,D/AuthorizationBluetoothService( 1292): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1292): Proximity feature is not enabled.
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1215): No location to return for getLastLocation()
,W/FusedLocationProvider( 1215): location=null
,V/AlarmManager(  769): waitForAlarm result :8
,E/MDM     ( 1215): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1641): Restart initialization of location
,D/AuthorizationBluetoothService( 1292): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1292): Proximity feature is not enabled.
V/AlarmManager(  769): waitForAlarm result :8
,W/GCoreFlp( 1215): No location to return for getLastLocation()
,W/FusedLocationProvider( 1215): location=null
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  769): waitForAlarm result :8
,I/SELinux ( 3848): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3848):  
,D/Mms/Contact( 1719): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 1719): performUpdate:widgetCount=0
D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - 
,D/dalvikvm( 1641): GC_CONCURRENT freed 1727K, 40% free 11488K/18988K, paused 3ms+6ms, total 33ms
,D/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - null 
I/SELinux ( 3848): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3848):  
I/SELinux ( 3848):  
I/SELinux ( 3848): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/ContactProvider( 2314): getAllContactInfoList Start
,E/SELinux ( 3848): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3848): >>>>> Normal User
,E/dalvikvm( 3848): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3848): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3848): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3848): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3848): Added TimaKesytore provider
,D/ContactProvider( 2314): getAllContactInfoList End
,I/syncContacts( 2314): thread: 152, onChange
,V/TaskCloserActivity( 3848): TaskCloserActivity enter()
W/ActivityManager(  769): Permission Denial: getCurrentUser() from pid=3848, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3862):  
,D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1719): sContactsObserver.onChange(),selfUpdate=false
,D/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2314): getAllContactInfoList Start
,I/SELinux ( 3862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3862):  
I/SELinux ( 3862):  
,I/SELinux ( 3862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3862): >>>>> Normal User
,E/dalvikvm( 3862): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/ContactProvider( 2314): getAllContactInfoList End
,I/syncContacts( 2314): thread: 153, onChange
,D/TimaKeyStoreProvider( 3862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3862): Added TimaKesytore provider
,D/FactoryTestApp( 3862): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3862): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3862): User mode
,I/SELinux ( 3876): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3876):  
I/ActivityManager(  769): Killing 2787:com.osp.app.signin/u0a43 (adj 15): empty #43
,I/SELinux ( 3876): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3876):  
I/SELinux ( 3876):  
,I/SELinux ( 3876): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3876): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3876): >>>>> Normal User
,E/dalvikvm( 3876): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3876): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3876): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3876): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3876): Added TimaKesytore provider
,E/MTPRx   ( 3876): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 3876): check value of boot_completed is1
,E/MTPRx   ( 3876): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3876): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3876): Status for mount/Unmount :removed
,E/MTPRx   ( 3876): SDcard is not available
,W/MTPRx   ( 3876): value of connected istrue
W/MTPRx   ( 3876): value of configured istrue
W/MTPRx   ( 3876): value of mtpEnabled istrue
,W/MTPRx   ( 3876): value of ptpEnabled isfalse
E/MTPRx   ( 3876): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3876): mFirstTime: false
,D/        ( 3876): MTP: reading debug level property
,E/MTPRx   ( 3876):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3876): Getting CryptionKey from JAVA
,E/MTPRx   ( 3876): currentUserId is 0
,E/MTPRx   ( 3876): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3876): usbMode is 0200
,E/MTPRx   ( 3876): is_secretmode is NOT 1
,W/MTPRx   ( 3876): Phone is lockedtrue
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/MTPRx   ( 3876):  inside checkKnoxStatus
,D/MTPRx   ( 3876):  inside checkKnoxStatus_isKnoxModeActive : false
D/ConnectivityService(  769): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/MTPRx   ( 3876): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3876): noti = 17
,E/MTPRx   ( 3876): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3876): else part ... so first time!!!
,E/MTPPlaObsrvr( 3876): inside setContext()
,E/MTPPlaObsrvr( 3876):  inside createplafiles
,E/MTPPlaObsrvr( 3876): playlist count is0
,E/MTPPlaObsrvr( 3876):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3876):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3876): Inside registerContentObserver
,E/MtpAdbObserver( 3876): inside setContext()
E/MtpAdbObserver( 3876): Inside registerContentObserver
,W/Settings( 3876): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3876): onCreate.
,E/MtpService( 3876): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3876): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3876): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3876): onStartCommand.
,E/MtpService( 3876): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3876): calling native method
,E/MTPJNIInterface( 3876): < MTP > Registering BroadCast receiver :::::
,I/knox    ( 3313): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/MTPJNIInterface( 3876): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3876): noti = 10
,I/knox    ( 3313): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/MtpService( 3876): onStartCommand.
D/knox    ( 3313): KNOXAgentService : onCreate()
D/knox    ( 3313): KNOXAgentService : set alarms for deniallog and usage data upload
W/MTPRx   ( 3876): calling native method
E/MTPRx   ( 3876): Checking the driver time out
E/MTPJNIInterface( 3876): noti = 2
D/        ( 3876): deleting sockets before message queue initialization
D/        ( 3876): event handler thread is created, so set the flag
E/MTPRx   ( 3876): called native method
E/MTPJNIInterface( 3876): Getting media scanner status0
E/MTPJNIInterface( 3876): setting Media scanner status0
E/MTPJNIInterface( 3876): After setting Media scanner status0
W/MTPRx   ( 3876): notification from stack 1
E/MtpService( 3876): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 3876): DeviceName is Galaxy S5-2
D/knox    ( 3313): KNOXAgentService. startJobThread() start
D/knox    ( 3313): KNOXAgentService. JobThread()
D/knox    ( 3313): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3313): KNOXAgentService. startJobThread() wait
,D/knox    ( 3313): KNOXAgentService : onDestroy().
,D/knox    ( 3313): ModuleBase.cancelAllAlarmManageModule()
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
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
,I/Atfwd_Daemon(  291): cmd3: +CMAR
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
,D/dalvikvm(  769): GC_EXPLICIT freed 2082K, 13% free 23511K/26996K, paused 4ms+10ms, total 119ms
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1455031140000
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1455009582694
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,D/AuthorizationBluetoothService( 1292): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3313): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3313): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 3313): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3313): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3313): KNOXAgentService : onCreate()
D/knox    ( 3313): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3313): KNOXAgentService. startJobThread() start
D/knox    ( 3313): KNOXAgentService. JobThread()
D/knox    ( 3313): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3313): KNOXAgentService. startJobThread() wait
I/knox    ( 3313): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/knox    ( 3313): KNOXAgentService : onDestroy().
D/knox    ( 3313): ModuleBase.cancelAllAlarmManageModule()
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3036): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3036): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3901): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3901):  
,W/ContextImpl(  769): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 3901): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3901):  
I/SELinux ( 3901):  
,I/SELinux ( 3901): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3901): >>>>> Normal User
,E/dalvikvm( 3901): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3901): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3901): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3901): Added TimaKesytore provider
,I/System.out( 3901): Inside WakeupProvider
,I/System.out( 3901): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3901): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3901): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3901): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3901): initQueue()
I/ActivityManager(  769): Waited long enough for: ServiceRecord{43146548 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1315):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1315): showing allowed
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  769): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=769
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1203): GC_EXPLICIT freed 3900K, 48% free 10043K/18988K, paused 2ms+6ms, total 36ms
,E/MTPJNIInterface( 3876): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3876): SDcard is not available
,E/MTPJNIInterface( 3876): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3876): SDcard is not available
E/SQLiteLog( 3876): (21) API call with NULL database connection pointer
E/SQLiteLog( 3876): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3876): (21) API call with NULL database connection pointer
E/SQLiteLog( 3876): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3876): (21) API call with NULL database connection pointer
E/SQLiteLog( 3876): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3876): (21) API call with NULL database connection pointer
E/SQLiteLog( 3876): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3876): notification from stack 2
D/        ( 3876): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 3876): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3876): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3876): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/dalvikvm( 1315): GC_CONCURRENT freed 7515K, 48% free 10062K/18988K, paused 4ms+10ms, total 66ms

```
