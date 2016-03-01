#### Test 61248225a3bd1fe_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/YouTube ( 3297): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
--------- beginning of /dev/log/system
D/PMS     (  903): releaseWL(428f80d0): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
D/YouTube ( 3297): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/MediaRouterService(  903): Client com.google.android.youtube (pid 3297): Registered
I/MediaRouter( 3297): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/YouTube ( 3297): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.youtube (3297/10168)
I/GoogleConversionPing( 3297): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1456842803&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3297): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3297): [NET] getaddrinfo-,err=8
D/libc    ( 3297): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3297): [NET] getaddrinfo-, 1
D/libc    ( 3297): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cb74 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3297): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3297): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/YouTube ( 3297): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/MediaRouter( 3297): getSelectedRoute
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3297/10168)
D/YouTube ( 3297): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3297): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3297): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3297/10168)
W/BroadcastQueue(  903): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3297/10168)
D/AutoSetting( 1397): receiver - intent: android.intent.action.USER_PRESENT
D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3253): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3253): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3253): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3253): Cust_ConnectToPC   : spcsc>false
D/        ( 3253): Cust_ConnectToPC   : IPT>true
D/        ( 3253): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3253): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3253): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3253): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3253): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3253): onReceive:android.intent.action.USER_PRESENT
D/YouTube ( 3297): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3297): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
I/SmartNS_PSService( 3253): onReceive:android.intent.action.USER_PRESENT
D/YouTube ( 3297): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
W/Settings( 3253): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3253):  defaultType:0
W/ContextImpl( 3253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=128
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3297): [NET] getaddrinfo_proxy-, success
D/YouTube ( 3297): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3297): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
D/Process (  903): killProcessQuiet, pid=3059
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3059:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3059
D/YouTube ( 3297): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
I/ActivityManager(  903): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3355 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
E/dalvikvm( 3297): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3297): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
D/browser ( 3355): Browser versionCode = 760001523 versionName = 7.0.2512153020
E/dalvikvm( 3297): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3297): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3297): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/YouTube ( 3297): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
D/YouTube ( 3297): apps.youtube.datalib.offline.b.run:86 Dispatching stored offline request immediately.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (3297/10168)
W/SWE_UI  ( 3355): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3355): Loading: swewebviewchromium
I/LibraryLoader( 3355): Time to load native libraries: 35 ms (timestamps 3785-3820)
I/LibraryLoader( 3355): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3355): Initializing chromium process, renderers=9
I/LibraryLoader( 3355): Expected native library version number "",actual native library version number ""
I/chromium( 3355): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
I/ProviderInstaller( 3297): Installed default security provider GmsCore_OpenSSL
D/libc    ( 3297): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 4
D/libc    ( 3297): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 4
D/libc    ( 3297): [NET] getaddrinfo-,err=8
D/libc    ( 3297): [NET] getaddrinfo-,err=8
D/libc    ( 3297): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    ( 3297): [NET] getaddrinfo-, 1
D/libc    ( 3297): [NET] getaddrinfo_proxy+
D/libc    ( 3297): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    ( 3297): [NET] getaddrinfo-, 1
D/libc    ( 3297): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cd5b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e918 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/cutils-trace( 3344): Error opening trace file: No such file or directory (2)
I/GoogleConversionPing( 3297): Ping responded with response code 200
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 35
D/libc    (  365): [NET]res_nsend:resplen=83
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3297): [NET] getaddrinfo_proxy-, success
I/global  ( 3297): call createSocket() return a new socket.
D/libc    ( 3297): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 3297): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=12
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3297): [NET] getaddrinfo_proxy-, success
I/global  ( 3297): call createSocket() return a new socket.
D/libc    ( 3297): [NET] getaddrinfo+,hn 15(0x3137332e313934),sn(),family 0,flags 4
D/libc    ( 3297): [NET] getaddrinfo-, SUCCESS
D/CustomizationManager( 3344): ====startRecUseTime====
D/htc.customization.log.level( 3344):  is 
W/CustomizationLogLevel( 3344): Level value is invalid, use default level 2
I/Adreno-EGL( 3355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3355): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3355): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3355): Local Branch: 
I/Adreno-EGL( 3355): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3355): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3355):                  aa63bbd948f41d15fc72f585e
D/Process (  903): killProcessQuiet, pid=3071
I/ActivityManager(  903): Killing 3071:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1294): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  903): Recipient 3071
I/SIMStateChangeReceiver( 1521): SIM state: ABSENT
I/SIMStateChangeReceiver( 1521): phoneType = 0
I/SIMStateChangeReceiver( 1521): remove notification
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3344):  Read ACC file spent 0.066 (s)
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3404 uid=10031 gids={50031, 3003, 5012}
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3344): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3344): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3344): Parsing tag category name = system
I/CustomizationCIDLoader( 3344): Parsing tag category name = application
I/CustomizationCIDLoader( 3344): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3344): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3344): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3344): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3344): Parsing tag category name = Settings
D/CustomizationManager( 3344):  Read CID file spent 0.119 (s)
D/CustomizationManager( 3344):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 3344): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3344): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3344): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3344): Fail to get flag for type 'language', use default value: -1
D/Process (  903): killProcessQuiet, pid=2476
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3417 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 2476:com.android.defcontainer/u0a19 (adj 15): empty #17
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3344
W/asset   (  903): Copying FileAsset 0x657082e8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1117056008
D/PMS     (  903): acquireHCC(41b52958): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(423d78c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
D/PMS     (  903): acquireWL(426ac538): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.htc.aurora
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d8f8d8
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3430 uid=10190 gids={50190, 3003, 5012, 3001, 3002}
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  903): Recipient 2476
I/TrimMemoryManager( 1268): [trimMemory] 20
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   ( 3430): Copying FileAsset 0x5c8e7c88 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1326): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
W/SystemReader( 2828): Cannot find message_ambs_application_id, use default value instead
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
D/SmsReceiver( 2828): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
V/WebViewChromiumFactoryProvider( 3430): Binding Chromium to main looper Looper (main, tid 1) {41b5b370}
I/LibraryLoader( 3430): Expected native library version number "",actual native library version number ""
I/chromium( 3430): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3430): Initializing chromium process, renderers=0
D/ExchangePolicystatus( 2828): onReceive()
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
D/ExchangePolicystatus( 2828): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2828): onReceive(): else
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/Process (  903): killProcessQuiet, pid=3103
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1240): onReceive: android.intent.action.SIM_STATE_CHANGED
D/PMS     (  903): acquireWL(41b52108): PARTIAL_WAKE_LOCK  AudioMix 0x1 377 1013 null
I/ActivityManager(  903): Killing 3103:com.google.android.gm/u0a107 (adj 15): empty #17
D/PMS     (  903): acquireWL(425f8a38): PARTIAL_WAKE_LOCK  AudioMix 0x1 377 1013 null
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41ffcd88:true
D/BluetoothAdapter( 3430): 1102516328: getState(). Returning 12
D/PMS     (  903): releaseWL(425f8a38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3103
,I/Adreno-EGL( 3430): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3430): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3430): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3430): Local Branch: 
I/Adreno-EGL( 3430): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3430): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3430):                  aa63bbd948f41d15fc72f585e
W/AccTypeManager( 3417): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3417): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/chromium( 3430): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/AccTypeManager( 3417): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/dalvikvm( 3430): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3430): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3430): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3430): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3430): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3430): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3430): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3430): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3430): CordovaWebView is running on device made by: HTC
E/ExternalAccountType( 3417): Unsupported attribute readOnly
W/AccTypeManager( 3417): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3417): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 3417): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 3417): Unsupported attribute readOnly
W/AwContents( 3430): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  903): Disable input method client, pid=1268
W/ResourceType( 3430): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3430): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba2668, mServedView=org.apache.cordova.engine.SystemWebView{41b68188 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=3430
D/PMS     (  903): releaseWL(426ac538): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +398ms
W/PackageManager(  903): Unable to load service info ResolveInfo{428e06a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidProtocolHandler( 3430): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3430): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3430): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3430): JniHelper::setJavaVM(0x4162b048), pthread_self() = 1658310760
D/JX-Cordova( 3430): jxcore cordova android initializing
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/WeatherUtility( 1115): can't get weather sync account
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3482 uid=10038 gids={50038}
W/jxcore-log( 3430): Initializing JXcore engine
W/jxcore-log( 3430): JXcore engine is ready
W/jxcore-log( 3430): Starting JXcore engine
D/Process (  903): killProcessQuiet, pid=3130
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3496 uid=10077 gids={50077}
I/ActivityManager(  903): Killing 3130:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3130
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3496): Got a database change event
D/Process (  903): killProcessQuiet, pid=3086
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3086:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/WeatherRequest( 1115): request cur loc, but there is no sys cur
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3509 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/CalendarApplication( 3509): onCreate
D/ProviderChangeReceiver( 3509): ---------------------------------------------------
D/ProviderChangeReceiver( 3509): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3509): start to updateAlertNotification!
W/ContextImpl( 3228): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3086
I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3524 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/AlertService( 3509): No fired or scheduled alerts
D/HtcAlertUtils( 3509): -- cancelReminderNotification --
W/jxcore-log( 3430): Platform android
W/jxcore-log( 3430): 
W/jxcore-log( 3430): Process ARCH arm
W/jxcore-log( 3430): 
D/HtcAlertUtils( 3509): broadcastExistReminder!
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/Process (  903): killProcessQuiet, pid=3156
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3156:com.google.android.talk/u0a111 (adj 15): empty #17
I/jxcore-log( 3430): JXcore Cordova bridge is ready!
I/jxcore-log( 3430): 
W/jxcore-log( 3430): JXcore engine is started
I/ActivityManager(  903): Recipient 3156
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/jxcore-log( 3430): >> HTC-HTC Desire 820
E/jxcore-log( 3430): 
I/jxcore-log( 3430): Total memory 1964650496
I/jxcore-log( 3430): 
I/jxcore-log( 3430): Free memory 653352960
I/jxcore-log( 3430): 
I/jxcore-log( 3430): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3430): 
I/jxcore-log( 3430): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3430): 
I/jxcore-log( 3430): userPath [ 'www' ]
I/jxcore-log( 3430): 
I/jxcore-log( 3430): Size 720 1184
I/jxcore-log( 3430): 
I/jxcore-log( 3430): Screen Brightness 10
I/jxcore-log( 3430): 
E/jxcore-log( 3430): Dummy Error Log.
E/jxcore-log( 3430): 
I/MusicStore( 3524): Database version: 95
W/ContextImpl( 3524): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3524): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3524, uid=10154, userID:0
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/MediaRouterService(  903): Client com.google.android.music (pid 3524): Registered
I/MediaRouter( 3524): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3524/10154)
I/NetworkMonitor( 3524): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1994/10021)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=3 [29][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3547 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/MediaRouter( 3524): getSelectedRoute
I/NetworkMonitor( 3524): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3524/10154)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3524, uid=10154, userID:0
D/Process (  903): killProcessQuiet, pid=3182
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Killing 3182:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3182
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -33 abnormalRssiCnt = 0 newLinkSpeed = 72
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/ACRA    ( 3547): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 3547): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 3547): Looking for error files in /data/data/com.facebook.katana/app_minidumps
W/SystemClassLoaderAdder( 3547): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 3547): Preparing secondary program dexes.
V/DexLibLoader( 3547): Loaded 4 raw lines of metadata.
V/DexLibLoader( 3547): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3547): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3547): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 3547): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3547): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3547): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3547): Dex already copied
D/OdexVerifier( 3547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 3547): Creating class loader
V/DexLibLoader( 3547): Finished creating class loader
V/DexLibLoader( 3547): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3547): Dex already copied
D/OdexVerifier( 3547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 3547): Creating class loader
V/DexLibLoader( 3547): Finished creating class loader
V/DexLibLoader( 3547): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3547): Dex already copied
D/OdexVerifier( 3547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 3547): Creating class loader
V/DexLibLoader( 3547): Finished creating class loader
V/DexLibLoader( 3547): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3547): Dex already copied
D/OdexVerifier( 3547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 3547): Creating class loader
V/DexLibLoader( 3547): Finished creating class loader
V/DexLibLoader( 3547): Verifying classes from secondary dexes.
D/DexLibLoader( 3547): DexLibLoader.ensureDexLoaded took 81 ms
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41be6dd0 +
I/Prism.WidgetManager( 1268): onLoadItems() +
I/jxcore-log( 3430): getBuffer is called!!!!
I/jxcore-log( 3430): 
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/Prism.WidgetManager( 1268): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1268): onLoadItems() -
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41be6dd0 -
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(41b52958): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(423d78c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/dalvikvm( 3547): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3547): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3547): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3547): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3547): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3547): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3547): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1240): -- N1 =0
D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3561 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  903): sending alarm PendingIntent{41be77b0: PendingIntentRecord{42302670 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54028, Int=0
,I/SensorManager(  903): mEventCount = 300
,I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3575 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3561): [858.1.] 30@-153257 -> 40@-153326
,D/Process (  903): killProcessQuiet, pid=3199
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  903): killProcessQuiet, pid=3214
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3199:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  903): Killing 3214:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3214
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1521): handler message = 4011
,E/HtcModeClient( 1521): Check connection and retry 5 times.
,W/dalvikvm( 3547): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3547): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/ActivityManager(  903): Recipient 3199
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/FbInjectorInitializer( 3547): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3547): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3547/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3241
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3241:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  903): acquireWL(426a4468): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1221 10028 null
I/ActivityManager(  903): Recipient 3241
D/PMS     (  903): acquireWL(423dd830): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1221 10028 null
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): releaseWL(426a4468): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): releaseWL(423dd830): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/AutoSetting( 1397): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3596 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1397): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1397): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1397): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
D/AutoSetting( 1397): service - handleMessage() setting current location null
,W/fb4a(:<default>):UserScope( 3547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3547): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 3547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 3596): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3596): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3596): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3596): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3611 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3271
,I/ActivityManager(  903): Killing 3271:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3596/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3596/10078)
D/PMS     (  903): acquireWL(42647eb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1221 10028 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3596/10078)
I/ActivityManager(  903): Recipient 3271
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  903): acquireWL(425fd0a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1221 10028 null
,W/ContextImpl( 3547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/CheckinService( 1221): Preparing to send checkin request
,I/EventLogService( 1221): Accumulating logs since 1456842257948
D/PMS     (  903): releaseWL(42647eb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,D/PMS     (  903): releaseWL(41b52108): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/EventLogAggregator( 1221): Unknown tag: install_package_attempt
W/EventLogAggregator( 1221): Unknown tag: snet
,W/EventLogAggregator( 1221): Unknown tag: snet_gcore
,D/Process (  903): killProcessQuiet, pid=3285
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3629 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 3285:com.android.smith/u0a163 (adj 15): empty #17
,I/GoogleHttpClient( 1221): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1221): Using GMS GoogleHttpClient
,D/WifiService(  903): New client listening to asynchronous messages
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1221/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1221/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 3629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 9.973MB for 28144-byte allocation
E/dalvikvm( 3547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3547): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3547): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 3547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3547): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/GAV2    ( 3629): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3285
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 3547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3547): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3547): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3547): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/ContextImpl( 3629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 3547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 3547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3547): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3547): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 3629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 10.041MB for 39954-byte allocation
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1115): com.google.android.gms (false,0),
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 4 12
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 10.118MB for 79892-byte allocation
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1221): awaiting user notification for token
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3629/10151)
,V/WebViewChromiumFactoryProvider( 3629): Binding Chromium to main looper Looper (main, tid 1) {41b59c70}
,I/LibraryLoader( 3629): Expected native library version number "",actual native library version number ""
,I/chromium( 3629): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3629): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(427faff8): PARTIAL_WAKE_LOCK  AudioMix 0x1 377 1013 null
,D/PMS     (  903): acquireWL(42884490): PARTIAL_WAKE_LOCK  AudioMix 0x1 377 1013 null
,D/PMS     (  903): releaseWL(427faff8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 3629): BLUETOOTH permission is missing!
I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3653 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Adreno-EGL( 3629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3629): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3629): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3629): Local Branch: 
I/Adreno-EGL( 3629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3629): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3629):                  aa63bbd948f41d15fc72f585e
,I/MultiDex( 3653): install
,I/MultiDex( 3653): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 3653): loading existing secondary dex files
,I/MultiDex( 3653): load found 1 secondary dex files
,I/MultiDex( 3653): install done
,I/dalvikvm-heap( 3547): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I/NSApplication( 3629): Starting up...
,I/ProviderInstaller( 3653): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3547/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3629/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3629/10151)
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4291b9a0 u0 ReceiverList{426b1ec0 3547 com.facebook.katana/10026/u0 remote:428812a0}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4291b9a0 u0 ReceiverList{426b1ec0 3547 com.facebook.katana/10026/u0 remote:428812a0}}
,D/Process (  903): killProcessQuiet, pid=3297
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3681 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  903): Killing 3297:com.google.android.youtube/u0a168 (adj 15): empty #17
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4276e018 u0 ReceiverList{4276dfb8 3547 com.facebook.katana/10026/u0 remote:42391508}}
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3547/10026)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3547/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3547/10026)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/GoogleHttpClient( 3653): Falling back to old SSLCertificateSocketFactory
D/PMS     (  903): acquireWL(4294ca00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
D/PMS     (  903): releaseWL(4294ca00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  903): Recipient 3297
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.youtube (pid 3297): Died!
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/GCoreFlp( 1422): Unknown pending intent to remove.
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
D/PMS     (  903): acquireWL(42929300): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
D/PMS     (  903): releaseWL(42929300): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    ( 3653): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3653): [NET] getaddrinfo-,err=8
D/libc    ( 3653): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3653): [NET] getaddrinfo-, 1
D/libc    ( 3653): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a218 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 273
D/libc    (  365): [NET]res_nsend:resplen=86
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3653): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3681/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3681/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3681/10160)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/Process (  903): killProcessQuiet, pid=3253
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3681/10160)
D/PMS     (  903): acquireWL(427a3df0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3681 10160 null
I/ActivityManager(  903): Killing 3253:com.android.settings/1000 (adj 15): empty #17
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
I/ActivityManager(  903): Recipient 3253
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AdsMeasurementBroadcastReceiver( 1221): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1221): Unauthorized to start the main service
,D/AlertReceiver( 3509): beginStartingService
D/PMS     (  903): acquireWL(422d2fe0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3681 10160 null
D/PMS     (  903): releaseWL(427a3df0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/PMS     (  903): acquireWL(420d16a8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3509 10013 null
,D/PMS     (  903): acquireWL(41e17a98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1221 10028 null
,D/PMS     (  903): releaseWL(41e17a98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 3509): start to updateAlertNotification!
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3715 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/AlertService( 3509): No fired or scheduled alerts
D/HtcAlertUtils( 3509): -- cancelReminderNotification --
,D/HtcAlertUtils( 3509): broadcastExistReminder!
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3509): stopSelfResult true
D/PMS     (  903): releaseWL(420d16a8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/PMS     (  903): releaseWL(422d2fe0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3730 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3715): can't get weather sync account
,W/WeatherRequest( 3715): request cur loc, but there is no sys cur
,W/Settings( 3715): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1268): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  903): acquireWL(42591370): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3730 10070 null
,I/dalvikvm-heap( 3681): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
,I/RemoteViews.Performance( 1268): com.htc.widget.weatherclock 1 11 17
D/PMS     (  903): acquireWL(4254d788): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3730 10070 null
D/PMS     (  903): releaseWL(42591370): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3745 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3730): update TASK shortcut>
,I/TodoTaskNotifyService( 3730): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 3730): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3730): stopSelfResult true
,D/Process (  903): killProcessQuiet, pid=3355
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(4254d788): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Killing 3355:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/WorldClock.Global( 3745): isHtcDevice = true
D/libc    ( 3653): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3653): [NET] getaddrinfo-,err=8
,I/WorldClock.Global( 3745): isHtcDevice = true
W/ContextImpl( 3228): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3745): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3745): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3745): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1115): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  903): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3760 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Recipient 3355
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3404
,I/ActivityManager(  903): Killing 3404:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 3760): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456842808476
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3404
,D/Process (  903): killProcessQuiet, pid=3417
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3417:com.htc.contacts/u0a41 (adj 15): empty #17
,W/WeatherUtility( 3715): can't get weather sync account
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3776 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/PMS     (  903): acquireWL(423822f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(423822f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/WeatherRequest( 3715): request cur loc, but there is no sys cur
,W/Settings( 3715): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3776): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3776): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1268): com.htc.widget.weatherclock (true,33751552)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [13][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -34 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/RestoreService( 3776): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(4258fdc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3730 10070 null
,D/PMS     (  903): acquireWL(420d1ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3730 10070 null
,I/RemoteViews.Performance( 1268): com.htc.widget.weatherclock 3 15 17
,D/TodoTaskshortcut( 3730): update TASK shortcut>
I/ActivityManager(  903): Recipient 3417
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): releaseWL(4258fdc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3730): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(420d1ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,W/NotifyReceiver( 3730): stopSelfResult true
,D/Process (  903): killProcessQuiet, pid=3482
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3794 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  903): Killing 3482:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3482
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3806 uid=10081 gids={50081, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3524
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  903): killProcessQuiet, pid=3496
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1221): Reporting settings might have changed, alerting AdsMeasurementService
I/ActivityManager(  903): Killing 3524:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  903): Killing 3496:com.htc.mms.backupagent/u0a77 (adj 15): empty #18
,D/AdsMeasurementBroadcastReceiver( 1221): Unauthorized to start the main service
I/ActivityManager(  903): Recipient 3496
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3524
D/MediaRouterService(  903): Client com.google.android.music (pid 3524): Died!
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3818 uid=10038 gids={50038}
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3831 uid=10077 gids={50077}
,D/Process (  903): killProcessQuiet, pid=3547
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3547:com.facebook.katana/u0a26 (adj 15): empty #17
,D/SMSBackup( 3831): Got a database change event
,D/Process (  903): killProcessQuiet, pid=3561
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3843 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  903): Killing 3561:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3561
,I/ActivityManager(  903): Recipient 3547
,D/WifiService(  903): Client connection lost with reason: 4
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(428f6b70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  903): acquireWL(423e5938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  903): releaseWL(428f6b70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(423e5938): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ImageRamCache( 3843): create image Cache, size: 31457280.
I/ImageRamCache( 3843): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3843): create image Cache, size: 12582912.
,I/FeedSettings( 3843): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3843): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3843): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3843): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3843): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3843): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3843): [custom highlight] onReceive
,D/CustomHighlightService( 3843): [custom highlight] onHandleIntent
,D/NewsDB  ( 3843): set custom highlight []
I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3843): [custom highlight] set tags 
,D/Process (  903): killProcessQuiet, pid=3575
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 3575:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/MessagingShortcutReceiver( 2828): keep hiding shortcut bubble
,D/MessagingShortcut( 2828): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2828): After query: 0
D/MessagingShortcut( 2828): mPresentUnreadCount: -1
,D/MessagingShortcut( 2828): setMsgShortcutDrawable> 0
I/ActivityManager(  903): Recipient 3575
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Resuming delayed broadcast
D/MessagingShortcut( 2828): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderNotification, total:0
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3730): update TASK shortcut>
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1240): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3861 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,D/MessagingNotification( 2828): New incoming message, can't cancel notification now
,D/MessagingNotification( 2828): newMsgCnt: 0, false
,I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3875 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3861): [908.1.] 40@-153326
,D/Process (  903): killProcessQuiet, pid=3596
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  903): killProcessQuiet, pid=3611
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3596:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  903): Killing 3611:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3611
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3596
,W/Settings( 3653): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/SMSBackup( 3831): Got a database change event
,D/MtpReceiver( 1994): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 1994): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 1994): [MTP][handleMessage][startService]
,D/MtpReceiver( 1994): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 1994): [MTP][handleMessage]-
,D/MtpService( 1994): [MTP] startForeground
I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3889 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1115): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1115): com.android.providers.media 3 1 10
,I/RemoteViews( 1115): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1115): com.android.providers.media 1 0 15
,D/MtpService( 1994): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 1994): TotalSize=1918604,MediaCacheLimit=6000
,D/MtpService( 1994): [isMtpConnected] connected: true
D/PMS     (  903): acquireWL(425f38c0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3681 10160 null
,D/SyncApplication( 3889): Loading default preferences
D/PMS     (  903): releaseWL(425f38c0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,W/Resources( 3889): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 3889): Overriding preferences with custom values
,D/SyncApplication( 3889): Updating preferences succeeded
,E/SyncApplication( 3889): Application created.
D/VolumeInfo( 3889): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3889): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3889): Found 0 mount point(s)
,V/VolumeInfo( 3889): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3889): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3889): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3889): Can not create volume ID for unmounted volume null
,I/Adreno-EGL( 3653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3653): Local Branch: 
I/Adreno-EGL( 3653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3653):                  aa63bbd948f41d15fc72f585e
,I/CalendarDefines( 3889): getNewCalendarAuthority()...
,D/SyncApplication( 3889): enableAppOperation()+
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3889, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3889, uid=10008, userID:0
,W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3889): enableAppOperation()-
,D/HTCUtilities( 3889): isNeorSinged() + 
,D/HTCUtilities( 3889): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3889): isNeorSinged() return false
D/CDMountReceiver( 3889): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3889): USB connected to PC
,D/FOTAReceiver( 3889): onReceive() enter 
,D/FOTAReceiver( 3889): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  903): killProcessQuiet, pid=3629
I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3914 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Killing 3629:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  903): Recipient 3629
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3509
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3509:com.htc.calendar/u0a13 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (3653/10028)
,I/ActivityManager(  903): Recipient 3509
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3914): -onCreate()
,V/Settings:HtcSettingsApplication( 3914): [3914/3914] onCreate()
,D/TetherSettings( 3914): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3914): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3914): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3914): Cust_ConnectToPC   : spcsc>false
D/        ( 3914): Cust_ConnectToPC   : IPT>true
,D/        ( 3914): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3914): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3914): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3914): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3914): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3914): Cust_ConnectToPC   : spcsc>false
D/        ( 3914): Cust_ConnectToPC   : IPT>true
D/        ( 3914): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3914): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3914): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3914): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3914): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3914): usb_cable_connect = 1
,D/SmartNS_Utility( 3914): usb_denied = 0
I/SmartNS_NSReceiver( 3914): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3914): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3914): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3914): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3914): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3914):  defaultType:0
I/SmartNS_PSService( 3914): fail notificaiton:false
D/SmartNS_Utility( 3914): usb_cable_connect = 1
D/SmartNS_Utility( 3914): usb_denied = 0
I/SmartNS_PSService( 3914): usb notificaiton:true
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3914/1000)
,I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews( 1115): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1115): com.android.settings 2 1 10
D/SmartNS_Utility( 3914): usb_cable_connect = 1
D/SmartNS_Utility( 3914): usb_denied = 0
I/SmartNS_PSService( 3914): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3914/1000)
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3914): usb_cable_connect = 1
D/SmartNS_Utility( 3914): usb_denied = 0
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1115): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1115): com.android.settings 0 1 10
I/SmartNS_PSService( 3914): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3914): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  903): Resuming delayed broadcast
,W/WeatherUtility( 3715): can't get weather sync account
,D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1268): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1268): com.google.android.googlequicksearchbox 0 0 5
,W/WeatherRequest( 3715): request cur loc, but there is no sys cur
,W/Settings( 3715): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  903): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
D/CustomHighlightReceiver( 3843): [custom highlight] onReceive
,I/RemoteViews( 1268): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1268): pl.k2.droidoaudioteka 1 1 8
,D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/CustomHighlightService( 3843): [custom highlight] onHandleIntent
,D/NewsDB  ( 3843): set custom highlight []
,I/RemoteViews( 1268): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/RemoteViews.Performance( 1268): com.htc.widget.weatherclock 2 5 17
,D/CustomHighlightService( 3843): [custom highlight] set tags 
,D/CustomHighlightReceiver( 3843): [custom highlight] onReceive
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3843): [custom highlight] onHandleIntent
D/NewsDB  ( 3843): set custom highlight []
,D/CustomHighlightService( 3843): [custom highlight] set tags 
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(4204e828): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/PMS     (  903): releaseWL(4204e828): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  903): acquireWL(421c3b10): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1521 10014 null
,I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  903): releaseWL(421c3b10): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=139 rxSum=125} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=20114 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20115 delay=15s
I/ActivityManager(  903): Resuming delayed broadcast
,D/PackageBroadcastService( 1221): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  903): acquireWL(42416360): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,D/PMS     (  903): releaseWL(42416360): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1221): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1221, uid=10028, userID:0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Adreno-EGL( 3653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3653): Local Branch: 
I/Adreno-EGL( 3653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3653):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 3653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3653): Local Branch: 
I/Adreno-EGL( 3653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3653):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  903): Resuming delayed broadcast
,I/CheckinTask( 1221): Sending checkin request (9043 bytes)
W/ActivityThread( 1221): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3946 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,D/libc    ( 1221): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cee4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3745
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1397): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1397): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Killing 3745:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Recipient 3745
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3964 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  365): [NET]res_nsend:resplen=244
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=12
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  903): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@41c72ca0 mBinding = false
,W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
,W/Settings:Agent(  903): Process.myTid(): 1350
W/Settings:Agent(  903): Process.myUid(): 1000
,W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
,W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 9(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  903): Sending off request.
D/BluetoothAdapterState( 1618): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1618): Setting state to 13
I/BluetoothAdapterState( 1618): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1618): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  903): +onBluetoothStateChange prev=12 new=13
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 1618): onBluetoothDisable()
I/bt-btm  ( 1618): BTM_SetDiscoverability
I/bt-btm  ( 1618): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1618): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1618): br_edr_supported=0x0
I/bt-btm  ( 1618): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1618): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1618): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1618): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1618): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1618): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1618): BTM_SetConnectability
I/bt-btm  ( 1618): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1618): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 1618): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterState( 1618): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1618): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 1618): adapterPropertyChangedCallback with type:7 len:4
I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1811): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b7b5e0
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1811): onDeInitialized
V/BluetoothPbapReceiver( 1618): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1618): ***********state = 13
D/WifiManager( 3430): setWifiEnabled: Base Package Name=com.example.hello, uid=10190
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3964, uid=10073, userID:0
D/WifiService(  903): New client listening to asynchronous messages
D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 914
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
D/BluetoothMasReceiver( 1618): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1618): SapReceiver onReceive 
V/BluetoothSapReceiver( 1618): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1618):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1618): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1618): Pbap Service closeService in
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-btm  ( 1618): BTM_FreeSCN 
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTM_SEC_CLR[13]: id 52
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1811): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1811): getNotificationManager
D/BluetoothAdapterProperties( 1618): Scan Mode:20
E/BTIF_CORE( 1618): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1618): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothAdapterState( 1618): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/WifiService(  903): setWifiEnabled: false pid=3430, uid=10190
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/PMS     (  903): acquireWL(4267ec00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3914 1000 null
W/ContextImpl( 3914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  903): acquireWL(423dcc48): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1618 1002 null
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-btm  ( 1618): BTM_FreeSCN 
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-sdp  ( 1618): BTM_FreeSCN 
D/bt-btm  ( 1618): BTM_FreeSCN 
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTM_SEC_CLR[15]: id 54
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-btm  ( 1618): BTM_FreeSCN 
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-btm  ( 1618): BTM_FreeSCN 
I/bt-btif ( 1618): BTA_JvDeleteRecord
I/bt-btif ( 1618): BTA_JvRfcommStopServer
D/bt-btm  ( 1618): BTM_FreeSCN 
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1618): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1618): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1618): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1618): Write Extended Inquiry Response to controller
I/bt-btm  ( 1618): Write Extended Inquiry Response to controller
I/bt-btm  ( 1618): Write Extended Inquiry Response to controller
I/bt-btm  ( 1618): Write Extended Inquiry Response to controller
I/bt-btm  ( 1618): BTM_SetDiscoverability
I/bt-btm  ( 1618): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1618): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1618): br_edr_supported=0x0
I/bt-btm  ( 1618): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1618): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1618): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1618): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1618): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1618): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1618): BTM_SetConnectability
I/bt-btm  ( 1618): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1618): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1618): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1618): BTM_IsInquiryActive
I/bt-btm  ( 1618): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1618): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1618): BTM_FreeSCN 
I/bt-btm  ( 1618): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1618): BTM_FreeSCN 
I/bt-btm  ( 1618): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1618): AVRC_Close handle:0
V/BluetoothSapService( 1618): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1618): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1618): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1618): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1618): GATT_Deregister gatt_if=3
I/bt-att  ( 1618): GATT_Deregister gatt_if=4
E/BtOppRfcommListener( 1618): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothRemoteDevices( 1618): Wake lock Aquired
D/PMS     (  903): releaseWL(4267ec00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426de738:true
I/jxcore-log( 3430): ****TEST TOOK:  5108  ms ****
I/jxcore-log( 3430): 
I/jxcore-log( 3430): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3430): 
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  903): acquireWL(4251e7a8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3914 1000 null
D/WirelessDisplayService(  903): getMirrorDisplayStatus:falsecurState:1
D/WifiPerfLock(  903): release()
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
I/LocationAgent( 3914): new LocationAgent instance!!
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/HtcTagManager( 3914): HtcTagManager construction complete
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(42642528): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1115): removeIcon slot=bluetooth index=12 viewIndex=0
D/BluetoothAdapter( 3914): 1102933040: getState(). Returning 13
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/BluetoothInputDevice( 3914): BluetoothInputDevice()
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3984 uid=10037 gids={50037, 3002, 3001}
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20115 mDataStallAlarmIntent=PendingIntent{424d2a00: PendingIntentRecord{425c6870 android broadcastIntent}}
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothManagerService(  903): Registered receivers: 7
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  903):    returned null
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BluetoothAdapter( 3914): 1102933040: getState(). Returning 13
D/BluetoothInputDevice( 3914): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3914): Bluetooth service connected
W/BluetoothInputDevice( 3914): Proxy not attached to service
D/BluetoothPan( 3914): BluetoothPan()
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  903): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapter( 3914): 1102933040: getState(). Returning 13
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothPan( 3914): BluetoothPan(): Fake return onServiceConnected
D/BluetoothManagerService(  903): Registered receivers: 8
D/PanProfile( 3914): Bluetooth service connected
V/BluetoothPbapService( 1618): successfully stopped pbap service
V/BluetoothPbapService( 1618): Pbap Service closeService out
D/BluetoothMap( 3914): Create BluetoothMap proxy object
I/BtOppRfcommListener( 1618): stopping Accept Thread
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 9
,I/BtOppRfcommListener( 1618): BluetoothSocket listen thread finished,
,D/WifiStateMachine(  903): Call handleNetworkDisconnect() in SupplicantStoppingState
,E/BluetoothMap( 3914): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/WifiP2pService(  903): P2pDisablingState
D/WifiP2pService(  903): P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): p2p socket connection lost
D/WifiP2pService(  903): P2pDisabledState
D/WifiDisplayController(  903): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  903): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  903): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  903): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  903): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0,
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  903):  WFD CtrlPort: 0
D/WifiP2pService(  903):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  903): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  903): updateConnection
I/WifiDisplayController(  903): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  903): updateConnection enter step 4
D/WifiDisplayController(  903): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
,D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3914): BluetoothSap() call bindService
D/BluetoothManagerService(  903): Registered receivers: 10
D/Finsky  ( 3964): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,V/BluetoothSapService( 1618): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1618): state: 13
D/BluetoothAdapter( 1618): 1102526832: getState(). Returning 13
,V/BluetoothSapService( 1618): Stopping SAP server process
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1811): init: null, null
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1811):  + initPendingRequestAlarm: false, mContext = null, null
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1811): writeLinkLossAlertLevelAll: 0, false
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1811): deinitLeServices_platform
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1811): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1811):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1811): deinit: 0
,V/AudioService(  903): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  903):     Client/Owner: Client
V/AudioService(  903):     GroupId: 
V/AudioService(  903):     Passphrase: 
V/AudioService(  903):     SessionId: 0
V/AudioService(  903):     IP Address: }
D/HtcEffectManagerBase(  903): onEventChanged id=5 status=false
D/HtcEffectManager(  903): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  903): convertEffect before=902
,D/HtcEffectManager(  903): convertEffect after=902
D/BluetoothPbap( 3914): BluetoothPbap()
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 11
,D/BluetoothManagerService(  903): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1811): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1811): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1811): init: null
D/BluetoothManagerService(  903): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42796c40:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/ContextImpl( 3914): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  903): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1811): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1811): Exit IdleState
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/BluetoothSapService( 1618): Sap Service closeSapService in
D/BluetoothAdapter( 3914): 1102933040: getState(). Returning 13
D/BluetoothPbap( 3914): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3914): Bluetooth service connected
,D/LocalBluetoothProfileManager( 3914): LocalBluetoothProfileManager construction complete
V/BluetoothSapService( 1618): Close listen Socket : 
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
V/BluetoothSapService( 1618): Close rfcomm Socket : 
V/BluetoothSapService( 1618): Close sapd  Socket : 
V/BluetoothSapReceiver( 1618): BluetoothSapReceiver deinit
,D/WifiNative-wlan0(  903):    returned true
,V/BluetoothSapService( 1618): successfully stopped Sap service
V/BluetoothSapService( 1618): Sap Service closeSapService out
V/BluetoothPbapService( 1618): Pbap Service onDestroy
V/BluetoothPbapService( 1618): Pbap Service closeService in
,V/BluetoothPbapService( 1618): Pbap Service closeService out
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,V/BluetoothSapService( 1618): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41babe90
V/BluetoothSapService( 1618): Sap Service closeSapService in
V/BluetoothSapService( 1618): Close listen Socket : 
V/BluetoothSapService( 1618): Close rfcomm Socket : 
,V/BluetoothSapService( 1618): Close sapd  Socket : 
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3964/10073)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DockEventReceiver( 3914): finishStartingService: stopping service
V/BluetoothSapService( 1618): Sap Service closeSapService out
V/BluetoothSapService( 1618): ***onDestroyed***
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/HtcBtWidget_BTWidgetProvider( 3984): onBTStateChanged() for widget: 
,D/SapServerProfile( 3914): Bluetooth service connected
D/WifiNative-p2p0(  903): doBoolean: TERMINATE
D/HtcBtWidget_BTWidgetProvider( 3984): updateWidget(context) for widget: 
D/SapServerProfile( 3914): Bluetooth service disconnected
,W/WifiHW  (  903): QCOM Debug wifi_send_command "TERMINATE"
,E/wpa_supplicant( 1159): Supplicant Terminat @ wpa_supplicant_deinit function
D/WISPrService( 3914): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1159): TDLS: Tear down peers
I/wpa_supplicant( 1159): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3964/10073)
D/PMS     (  903): acquireWL(425625b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/PMS     (  903): releaseWL(4251e7a8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  365): [NET] entry_id:8   entry:0xb7ba2c20  removed 
D/libc    (  365): [NET] entry_id:11   entry:0xb7ba4778  removed 
D/libc    (  365): [NET] entry_id:10   entry:0xb7ba45d8  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7ba3708  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb7ba3a30  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb7ba3bf0  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7ba2f70  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb7ba3948  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7ba7428  removed 
D/libc    (  365): [NET] entry_id:12   entry:0xb7ba3430  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7ba2e68  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7ba3670  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-p2p0(  903):    returned true
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(4256e248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/WifiService(  903): New client listening to asynchronous messages
,D/WISPrService( 3914): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=-5ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1362/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WISPrService( 3914): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  903): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3914): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1618): Shutdown
D/PMS     (  903): acquireWL(4292ace8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/PMS     (  903): releaseWL(425625b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): releaseWL(4256e248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/BluetoothMasReceiver( 1618): Bluetooth STATE CHANGED to 13
,D/Process (  903): killProcessQuiet, pid=3228
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1811): Received state change = 13
,E/CheckinTask( 1221): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.ConnectException: failed to connect to android.clients.google.com/173.194.116.97 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
,W/GoogleHttpClient( 1221): Unable to close GMS GoogleHttpClient
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1159): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
I/wpa_supplicant( 1159): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,I/ActivityManager(  903): Killing 3228:com.android.settings:remote/1000 (adj 15): empty #17
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1811): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b7b5e0
D/wpa_supplicant( 1159): TDLS: Remove peers on disassociation
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): deinitLeServices: null
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb74b5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1159):    addr=f4:f2:6d:22:99:3e
E/wpa_supplicant( 1159): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1159): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDf4:f2:6d:22:99:3e
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1159): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0-,>0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2437
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2437
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
I/ActivityManager(  903): Recipient 3228
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/BroadcastQueue(  903): Schedule to resend BroadcastRecord{425efcb8 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=903 callingUid=1000} for ResolveInfo{425b69c8 com.android.settings/.widget.SettingsAppWidgetProvider m=0x108000} of com.android.settings:remote
,D/Process (  903): killProcessQuiet, pid=3760
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  903): Killing 3760:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  903): Recipient 3760
,I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4017 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,D/PMS     (  903): releaseWL(4292ace8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
,W/bt-btif ( 1618): ag scb idx 1 not allocated
,W/bt-btif ( 1618): ag scb idx 2 not allocated
E/bt-btif ( 1618): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1618): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1618): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1618): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1618): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1618): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1618): L2CAP - PSM: 0x0017 not found for deregistration
,D/Finsky  ( 3964): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/Settings:HtcSettingsApplication( 4017): [4017/4017] onCreate()
D/PMS     (  903): releaseWL(425fd0a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1221): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b92970 that was originally bound here
E/ActivityThread( 1221): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b92970 that was originally bound here
E/ActivityThread( 1221): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1221): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1221): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1221): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1221): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1221): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1221): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1221): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1221): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1221): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1221): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1221): 	at bks.a(SourceFile:298)
E/ActivityThread( 1221): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1221): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1221): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1221): 	at java.lang.Thread.run(Thread.java:864)
W/Settings( 3964): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3964): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiService(  903): New client listening to asynchronous messages
,E/bt_userial_mct( 1618): userial_close userial_thread_created userial_running is 1 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3964, uid=10073, userID:0
,D/PMS     (  903): releaseWL(42884490): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Process (  903): killProcessQuiet, pid=3776
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3776:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3776
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3794
,I/ActivityManager(  903): Killing 3794:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_ADDED
D/Finsky  ( 3964): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3964): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2947): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
E/cutils-trace( 4002): Error opening trace file: No such file or directory (2)
,D/Finsky  ( 3964): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  903): Delaying start of: ServiceRecord{4266ed20 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,W/asset   ( 2947): Copying FileAsset 0x5c7e0808 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,E/wpa_supplicant( 1159): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1159): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1159): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/Finsky  ( 3964): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  903): killProcessQuiet, pid=3806
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3806:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3806
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4046 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  903): Recipient 3794
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(428e99e8): PARTIAL_WAKE_LOCK  Icing 0x1 1221 10028 null
,I/IcingCorporaProvider( 2947): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
,I/DeviceManagement( 4046): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4046 dbg=false s=true
,I/DeviceManagement( 4046): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4060 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=0, operstate=6
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/Process (  903): killProcessQuiet, pid=2828
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/wpa_supplicant( 1159): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1159): nl80211: Unsubscribe mgmt frames handle 0xb74b6718 (mode change)
I/wpa_supplicant( 1159): htc_wext_command_deinit +
I/wpa_supplicant( 1159): htc_wext_command_deinit -
E/wpa_supplicant( 1159): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1159): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1159): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1159): TDLS: Tear down peers
I/wpa_supplicant( 1159): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
,E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
I/ActivityManager(  903): Killing 2828:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/CustomizationManager( 4002): ====startRecUseTime====
,D/htc.customization.log.level( 4002):  is 
,W/CustomizationLogLevel( 4002): Level value is invalid, use default level 2
,I/bt-btif ( 1618): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1618): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1618): Received stop request...Stopping profile...
D/BluetoothHeadset( 1240): Proxy object disconnected
D/BluetoothHeadset( 1115): Proxy object disconnected
D/BluetoothPhoneService( 1240): BluetoothHeadset onServiceDisconnected
I/QuickSettingMiniLite( 1115): btListener.disconnect:HEADSET
,D/BluetoothHeadset( 1240): Proxy object disconnected
,D/BluetoothHeadset(  903): Proxy object disconnected
D/A2dpService( 1618): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1618): doQuit
,D/A2dpStateMachine( 1618): Exit Disconnected: -1
D/BluetoothA2dp(  903): Proxy object disconnected
,D/BluetoothAdapterState( 1618): Stopping profile services that were post enabled
,D/HidService( 1618): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1618): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1618): Received stop request...Stopping profile...
W/BluetoothHeadsetServiceJni( 1618): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1618): Cleaning up Bluetooth Handsfree callback object
D/PanService( 1618): Received stop request...Stopping profile...
D/PanService( 1618): stop
,D/PanService( 1618): stop: mTetherAc send disconnect
,D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECT
,D/BluetoothTethering(  903): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  903): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  903): BluetoothPAN Proxy object disconnected
,D/BluetoothAdapterService( 1618): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 1618): handleDebugAction() action=null
,D/BtGatt.GattService( 1618): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1618): stop()
,D/A2dpStateMachine( 1618): cleanup
,D/Avrcp   ( 1618): Unregistering previous receiver
D/BluetoothAdapterService( 1618): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1618): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1618): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1618): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1618): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1618): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1618): Cleaning up Bluetooth Health object
D/PanService( 1618): CMD_CHANNEL_DISCONNECTED
D/PanService( 1618): CMD_CHANNEL_DISCONNECTED call disconnected
,D/BluetoothAdapterService( 1618): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1618): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1618): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1618): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 1618): Setting state to 10
I/BluetoothAdapterState( 1618): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1618): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  903): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  903): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  903): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  903): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 1618): Entering OffState
,E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
D/CustomizationManager( 4002):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4002): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__Y13
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x627f2d28
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__J15
I/wpa_ctrl(  903): [wpa_ctrl_close] ctrl=0x627f2008
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__016
W/WifiHW  (  903): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  903): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4002): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4002): Parsing tag item name = HTC__031
D/WifiStateMachine(  903): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  903): doBoolean: SET_WIFI_ON 0
,V/CustomizationCIDLoader( 4002): full path : /system/customize/CID/HTC__032.xml
D/WifiNative-wlan0(  903):    returned false
I/CustomizationCIDLoader( 4002): Parsing tag category name = system
,D/BluetoothSap( 3914): onBluetoothStateChange on: false
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
,I/CustomizationCIDLoader( 4002): Parsing tag category name = application
I/CustomizationCIDLoader( 4002): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4002): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4002): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4002): Parsing tag category name = ACC
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/CustomizationCIDLoader( 4002): Parsing tag category name = Settings
D/CustomizationManager( 4002):  Read CID file spent 0.096 (s)
,D/CustomizationManager( 4002):  All configurations done spent 0.096 (s)
,D/BluetoothHeadset( 1115): onBluetoothStateChange: up=false
D/WirelessDisplayService(  903): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  903): WIFI Trun OFF
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/HtcNativeFlag( 4002): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4002): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4002): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4002): Fail to get flag for type 'language', use default value: -1
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
,E/WifiStateMachine(  903): [MLHD] Error! unhandled message 6 { when=-114ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/PMS     (  903): acquireWL(42608050): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/BluetoothInputDevice( 3914): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3914): 
E/BluetoothInputDevice( 3914): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41be31c8
E/BluetoothInputDevice( 3914): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3914): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3914): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3914): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3914): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3914): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothPbap( 3914): onBluetoothStateChange: up=false
E/BluetoothPbap( 3914): 
E/BluetoothPbap( 3914): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41bec6e0
E/BluetoothPbap( 3914): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3914): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3914): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3914): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3914): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3914): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothMap( 3914): onBluetoothStateChange: up=false
,E/BluetoothMap( 3914): 
E/BluetoothMap( 3914): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41be5ae0
E/BluetoothMap( 3914): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3914): 	,at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3914): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3914): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3914): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3914): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3914): 	,at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset(  903): onBluetoothStateChange: up=false
D/WISPrService( 3914): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3914): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/ActivityManager(  903): Recipient 2828
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothA2dp(  903): onBluetoothStateChange: up=false
E/BluetoothPan( 3914): 
E/BluetoothPan( 3914): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41be4760
E/BluetoothPan( 3914): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3914): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3914): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3914): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3914): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3914): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  903): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1618): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b71de0
D/BluetoothDevice( 1618): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1618): onBluetoothServiceDown: done
D/BluetoothAdapter( 1422): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cb5260
D/BluetoothAdapter( 1422): onBluetoothServiceDown: done
D/BluetoothAdapter( 1115): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41f5ace0
D/BluetoothAdapter( 1115): onBluetoothServiceDown: done
D/BluetoothAdapter( 1838): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c617b8
D/BluetoothAdapter( 1838): onBluetoothServiceDown: done
D/BluetoothAdapter(  903): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c72ca0
D/BluetoothAdapter(  903): onBluetoothServiceDown: done
D/BluetoothAdapter( 1240): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e01d20
D/BluetoothAdapter( 1240): onBluetoothServiceDown: done
D/BluetoothAdapter( 1251): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c2bf88
D/BluetoothAdapter( 1251): onBluetoothServiceDown: done
D/BluetoothAdapter( 1811): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b7beb0
D/BluetoothAdapter( 1811): onBluetoothServiceDown: done
D/BluetoothAdapter( 3430): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b71ad0
D/BluetoothAdapter( 3430): onBluetoothServiceDown: done
D/BluetoothAdapter( 3914): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bd7698
D/BluetoothAdapter( 3914): onBluetoothServiceDown: done
D/BluetoothManagerService(  903): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@41c72ca0 mBinding = false
D/BluetoothManagerService(  903): Sending unbind request.
D/BluetoothManagerService(  903): Bluetooth State Change Intent: 13 -> 10
I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NfcHandover( 1251): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 3914): setBluetoothStateOff
D/HtcTagManager( 3914): stopProxy
W/BluetoothEventManager( 3914): unregister mProfileBroadcastReceiver fail
,D/TetherPref( 3914): persistRestoreBluetoothState false
,I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,W/BluetoothHeadset( 1115): Proxy not attached to service
,I/QuickSettingMiniLite( 1115): updateLiteState:no connect device!
,D/BluetoothAdapter( 1115): 1105204304: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/PMS     (  903): releaseWL(423dcc48): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=4002, uid=2000 user=0
,D/BluetoothAdapterService( 1618): Cleaning up adapter native....
I/bt-btif ( 1618): HAL bt_hal_cbacks->thread_evt_cb
,D/BluetoothAdapterService( 1618): Done cleaning up adapter native....
,D/BluetoothAdapterService(1102508656)( 1618): ****onDestroy()********
,D/BtGatt.GattService( 1618): cleanup()
W/bt-btif ( 1618): GATTC Module not enabled/already disabled
W/bt-btif ( 1618): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 1618): Bluetooth STATE CHANGED to 10
D/PMS     (  903): acquireWL(4294ec48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3914 1000 null
W/ContextImpl( 3914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothMasService( 1618): onDestroy: mIsEmailEnabled: true
,D/HtcBtWidget_BTWidgetProvider( 3984): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3984): updateWidget(context) for widget: 
D/PMS     (  903): releaseWL(4294ec48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  903): acquireWL(425796e8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3914 1000 null
,D/Process (  903): killProcessQuiet, pid=3430
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  903): Copying FileAsset 0x6312afb8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  903): Force stopping com.example.hello appid=10190 user=-1: uninstall pkg
I/ActivityManager(  903): Killing 3430:com.example.hello/u0a190 (adj 0): stop com.example.hello
W/ActivityManager(  903): Force removing ActivityRecord{424de448 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  903): Skipping PackageSetting{422af460 com.test.thalitest/10189} due to missing metadata
,D/WifiService(  903): Client connection lost with reason: 4
,I/WindowState(  903): WIN DEATH: Window{426188c0 u0 com.example.hello/com.example.hello.MainActivity}
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DockEventReceiver( 3914): finishStartingService: stopping service
I/ActivityManager(  903): Force stopping com.example.hello appid=10190 user=0: pkg removed
D/PMS     (  903): releaseWL(425796e8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,I/FeedHostManager( 1268): [onResume]
,I/FeedProviderManager( 1268): onResume
I/SocialFeedProvider( 1268): +onResume
I/SocialFeedProvider( 1268): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1268): -onResume
,I/ConnectivityHelper( 1268): [getCurrentConnectionType] no network connection
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1268/10075)
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,V/AlarmManager(  903): sending alarm PendingIntent{41dac5d8: PendingIntentRecord{424fa4a8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58763, Int=0
I/acms    ( 1876): Unregistering com.example.hello
,E/acms    ( 1876): Could not unregister removed application com.example.hello
I/Prism.ItemManager( 3843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3843): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
D/PMS     (  903): acquireWL(42875260): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
,D/BluetoothMasReceiver( 1618): Bluetooth STATE CHANGED to 10
D/PMS     (  903): releaseWL(42875260): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1811): Received state change = 10
,W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41c8fd78:true
,W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4017): new LocationAgent instance!!
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/HtcTagManager( 4017): HtcTagManager construction complete
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4017): BluetoothInputDevice()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4017): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4017): Bluetooth service connected
W/BluetoothInputDevice( 4017): Proxy not attached to service
D/BluetoothPan( 4017): BluetoothPan()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Registered receivers: 12
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4017): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 4017): Bluetooth service connected
D/BluetoothManagerService(  903): Registered receivers: 13
D/BluetoothMap( 4017): Create BluetoothMap proxy object
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 14
E/BluetoothMap( 4017): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothSap( 4017): BluetoothSap() call bindService
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  903): Registered receivers: 15
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/ActivityManager(  903): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4060/10100)
W/ContextImpl( 4017): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
D/BluetoothPbap( 4017): BluetoothPbap()
D/BluetoothManagerService(  903): registerStateChangeCallback+
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothPbap( 4017): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4017): Bluetooth service connected
D/LocalBluetoothProfileManager( 4017): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  903): Registered receivers: 16
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4017): 1102490384: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4017): setBluetoothStateOff
D/HtcTagManager( 4017): stopProxy
,W/BluetoothEventManager( 4017): unregister mProfileBroadcastReceiver fail
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4060/10100)
W/GAV2    ( 4060): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
D/Process (  903): killProcessQuiet, pid=3730
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  903): Killing 3730:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3730
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1326): Unsupported attribute readOnly
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT",
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1422/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4060/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4060/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1876/1000)
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,V/AlarmManager(  903): sending alarm PendingIntent{4243b1c8: PendingIntentRecord{42867588 com.android.vending startService}}, i=null, t=0, cnt=1, w=1456842811601, Int=0
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3430 uid 10190
,W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
I/InputMethodManagerService(  903): Enable input method client, pid=1268
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
,I/HtcModeClient( 1521): handler message = 4011
,E/HtcModeClient( 1521): Check connection and retry 6 times.
,I/ActivityManager(  903): Resuming delayed broadcast
,W/GAV2    ( 4060): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  903): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4094 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/PackageManager(  903): Unable to load service info ResolveInfo{41c90038 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,I/Icing   ( 1221): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,W/Netd    (  365): No subsystem found in netlink event
V/Tethering(  903): remove iface:wlan0
D/Tethering(  903): interfaceRemoved wlan0
,E/Tethering(  903): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,I/SocialFeedProvider( 1268): +disConnect socialManager
,I/SocialFeedProvider( 1268): disconnect socialManager
,I/SocialFeedProvider( 1268): -disConnect socialManager
,I/htcbackup-core( 4094): ModelRegistry: Loading model meta data from resources...
,E/Icing   ( 1221): Bad write: Bad file number
,E/Icing   ( 1221): Error writing document: Write error to document store(6)
,E/Icing   ( 1221): Skipped indexing "com.example.hello/.MainActivity" because it was not added to the document store
,W/ContextImpl( 4094): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4094): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 4046): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4046): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.providers.settings, com.htc.guide, com.htc.cirmodule, com.android.CSDFunctionG, com.android.inputdevices, com.android.settings, com.htc.android.htcsetupwizard, com.htc.smartdim, com.htc.feedback, com.android.location.fused, com.qualcomm.timeservice, com.htc.lockscreen, com.htc.htcpowermanager, com.htc.backup, com.android.keychain, com.htc.drive.activator, com.htc.backupreset, com.htc.android.htcloglevel, com.htc.checkinprovider, android, com.htc.mirrorlinkserver, com.qualcomm.privinit, com.htc.autobot.cargps.provider, com.htc.usage, com.htc.home.personalize]
,I/DeviceManagement( 4046): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4112 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=3861
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/DeviceManagement( 4046): WorkflowService: Starting workflow service
I/DeviceManagement( 4046): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b909c8] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4046): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/ActivityManager(  903): Killing 3861:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/DeviceManagement( 4046): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  903): Recipient 3861
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4046): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4046): SessionStateController: Checking invariants...
,I/Icing   ( 1221): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
D/PMS     (  903): releaseWL(428e99e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/HtcCupdReceiver(Provider)( 4112):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  903): NoActiveNetworkState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/Tethering(  903): interfaceLinkStateChanged p2p0, false
,D/Tethering(  903): interfaceStatusChanged p2p0, false
,D/PMS     (  903): acquireWL(42641150): PARTIAL_WAKE_LOCK  AsyncService 0x1 3681 10160 null
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/PMS     (  903): releaseWL(42641150): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/PMS     (  903): acquireWL(42714d40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  903): releaseWL(42714d40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Netd    (  365): No subsystem found in netlink event
V/Tethering(  903): remove iface:p2p0
D/Tethering(  903): interfaceRemoved p2p0
,E/Tethering(  903): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,E/PlayEventLogger( 3964): Could not write string (event_code: 0
E/PlayEventLogger( 3964): event_flow_id: 0
E/PlayEventLogger( 3964): event_time_ms: 1456842812107
E/PlayEventLogger( 3964): exp <
E/PlayEventLogger( 3964):   client_altering_experiment: "cl:billing.prompt_for_auth_choice_once"
E/PlayEventLogger( 3964):   client_altering_experiment: "cl:billing.prompt_for_fop"
E/PlayEventLogger( 3964):   client_altering_experiment: "cl:billing.prompt_for_fop_ui_mode_radio_button"
E/PlayEventLogger( 3964):   client_altering_experiment: "cl:details.double_fetch_social_data"
E/PlayEventLogger( 3964):   client_altering_experiment: "cl:details.hide_download_count_in_title"
E/PlayEventLogger( 3964):   other_experiment: "nocache:dfe:dc:1"
E/PlayEventLogger( 3964):   other_experiment: "nocache:dfe:uc:PL"
E/PlayEventLogger( 3964):   other_experiment: "cl:auth.use_reauth_api"
E/PlayEventLogger( 3964):   other_experiment: "cl:details.album_all_access_alternate_enabled"
E/PlayEventLogger( 3964):   other_experiment: "cl:details.details_page_v2_enabled"
E/PlayEventLogger( 3964):   other_experiment: "cl:enable_rapid_auto_update"
E/PlayEventLogger( 3964):   other_experiment: "cl:search.cap_local_suggestions_2"
E/PlayEventLogger( 3964):   other_experiment: "cl:search.hide_ordinals_from_search_results"
E/PlayEventLogger( 3964):   other_experiment: "targets:CBIIEwgUCBUIGAgjCCQImQEI3gEIgwIIqAII2QMIwgQIxAQI4wUI5QUI6AUI7AUImQYI1wYIhAcIjgcIuwcIkJWBBgiRlYEGCJKVgQYIk5WBBgiVlYEGCJeVgQYImJWBBgialYEGCJuVgQYIpJWBBgillYEGCKyVgQYIrZWBBgizlYEGCLSVgQYItZWBBgi2[...]"
E/PlayEventLogger( 3964): >
E/PlayEventLogger( 3964): is_user_initiated: false
E/PlayEventLogger( 3964): source_extension: "\"/\010w\022\023com.android.vending*\020AuthFailureErrorZ\004\020\000\030\001"
E/PlayEventLogger( 3964): source_extension_js: ""
E/PlayEventLogger( 3964): tag: "4"
E/PlayEventLogger( 3964): ) to file: write failed: EBADF (Bad file number)
E/PlayEventLogger( 3964): java.io.IOException: write failed: EBADF (Bad file number)
E/PlayEventLogger( 3964): 	at libcore.io.IoBridge.write(IoBridge.java:455)
E/PlayEventLogger( 3964): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
E/PlayEventLogger( 3964): 	at java.io.FileOutputStream.write(FileOutputStream.java:192)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.writeRawVarint32(EventLogger.java:415)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.onWrite(EventLogger.java:401)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.onWrite(EventLogger.java:63)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.RollingFileStream.write(RollingFileStream.java:240)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.addEventImpl(EventLogger.java:368)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.dispatchMessage(EventLogger.java:339)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger.access$000(EventLogger.java:63)
E/PlayEventLogger( 3964): 	at com.google.android.play.analytics.EventLogger$1.dispatchMessage(EventLogger.java:202)
E/PlayEventLogger( 3964): 	at android.os.Looper.loop(Looper.java:157)
E/PlayEventLogger( 3964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PlayEventLogger( 3964): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
E/PlayEventLogger( 3964): 	at libcore.io.Posix.writeBytes(Native Method)
E/PlayEventLogger( 3964): 	at libcore.io.Posix.write(Posix.java:202)
E/PlayEventLogger( 3964): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
E/PlayEventLogger( 3964): 	at libcore.io.IoBridge.write(IoBridge.java:450)
E/PlayEventLogger( 3964): 	... 12 more
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,D/LocationManagerService(  903): getAllProviders()=[passive, gps, network]
W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/AlarmManager(  903): sending alarm PendingIntent{420e0768: PendingIntentRecord{426762f8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1456842812163, Int=0
,I/SocialManager[SocialBiLogHelper]( 3843): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3843): last commit ulog time 1456725249074
,I/SocialManager[SocialBiLogHelper]( 3843): do commit ulog
,E/SQLiteDatabase( 4046): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4046): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4046): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4046): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4046): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4046): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4046): ,	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4046): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4046): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4046): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4046): 	at java.lang.Thread.run(Thread.java:864)
W/Finsky  ( 3964): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
E/SharedPreferencesImpl( 3843): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
E/SharedPreferencesImpl( 3843): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
,E/SharedPreferencesImpl( 3843): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
,V/AlarmManager(  903): sending alarm PendingIntent{42042310: PendingIntentRecord{424e6d88 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1456842812172, Int=0
I/DeviceManagement( 4046): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4046): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4046): SessionStateController: Checking invariants...
E/SharedPreferencesImpl( 1221): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml.bak
D/Finsky  ( 3964): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/DirectoryFileManager( 1221): Could not ensure directory exists.
,E/SQLiteDatabase( 3964): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 3964): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3964): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 3964): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/SQLiteDatabase( 3964): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3964): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3964): threadid=25: thread exiting with uncaught exception (group=0x41723e30)
I/ActivityManager(  903): Resuming delayed broadcast
E/LogStore( 1221): Could not write string (a: 1456842812162
E/LogStore( 1221): b: "system_health"
E/LogStore( 1221): c: 0
E/LogStore( 1221): d: 0
E/LogStore( 1221): e: false
E/LogStore( 1221): h: "\012\37777777606\001\012\0245.0.89 (1307510-038)\020\37777777766\37777777746O\030\005 \003(\0102d\012\0051.6.0\022\023The Android Project\032\006Dalvik\"\0030.9*\023The Android Project2$Dalvik Virtual Machine Specification\022\012\010\001\020\001\032\004@\001H\003"
E/LogStore( 1221): i: ""
E/LogStore( 1221): j: ""
E/LogStore( 1221): l: ""
E/LogStore( 1221): ) to file: Directory doesn't exist.
E/LogStore( 1221): java.io.IOException: Directory doesn't exist.
E/LogStore( 1221): 	at hrv.a(SourceFile:372)
E/LogStore( 1221): 	at hsa.a(SourceFile:322)
E/LogStore( 1221): 	at hsa.a(SourceFile:345)
E/LogStore( 1221): 	at hrt.a(SourceFile:138)
E/LogStore( 1221): 	at hrt.a(SourceFile:148)
E/LogStore( 1221): 	at hrs.k(SourceFile:247)
E/LogStore( 1221): 	at hrs.a(SourceFile:126)
E/LogStore( 1221): 	at hrq.a_(SourceFile:40)
E/LogStore( 1221): 	at bur.b(SourceFile:296)
E/LogStore( 1221): 	at bux.a(SourceFile:188)
E/LogStore( 1221): 	at buw.a(SourceFile:561)
E/LogStore( 1221): 	at buq.d(SourceFile:192)
E/LogStore( 1221): 	at bup.handleMessage(SourceFile:128)
E/LogStore( 1221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LogStore( 1221): 	at android.os.Looper.loop(Looper.java:157)
E/LogStore( 1221): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/LogStore( 1221): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LogStore( 1221): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LogStore( 1221): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/LogStore( 1221): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/LogStore( 1221): 	at dalvik.system.NativeStart.main(Native Method)
,E/PlayLogBrokerService( 1221): --> failed to write
E/AndroidRuntime( 3964): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 3964): Process: com.android.vending, PID: 3964
E/AndroidRuntime( 3964): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3964): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 3964): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/AndroidRuntime( 3964): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3964): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  903): App crashed! Process: com.android.vending
I/ActivityManager(  903): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4141 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
E/SQLiteDatabase( 4046): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4046): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4046): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4046): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4046): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4046): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/S,QLiteDatabase( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/SQLiteDatabase( 4046): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4046): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4046): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4046): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4046): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4046): ServiceWorkflow: Uncaught throwable
E/DeviceManagement( 4046): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/DeviceManagement( 4046): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/DeviceManagement( 4046): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DeviceManagement( 4046): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/DeviceManagement( 4046): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DeviceManagement( 4046): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DeviceManagement( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/DeviceManagement( 4046): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.c,ontent.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/DeviceManagement( 4046): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/DeviceManagement( 4046): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/DeviceManagement( 4046): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/DeviceManagement( 4046): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/DeviceManagement( 4046): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DeviceManagement( 4046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DeviceManagement( 4046): 	at android.os.Looper.loop(Looper.java:157)
E/DeviceManagement( 4046): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4046): ServiceWorkflow: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
I/DeviceManagement( 4046): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b909c8]
I/DeviceManagement( 4046): WorkflowService: Stopping workflow service
I/htcbackup-core( 4094): ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
E/SharedPreferencesImpl( 1221): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
I/ActivityManager(  903): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
E/SharedPreferencesImpl( 1221): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  903): sending alarm PendingIntent{425d5760: PendingIntentRecord{426a9c38 com.google.android.gms startService}}, i=null, t=0, cnt=17155, w=84918423, Int=84918423
I/ActivityManager(  903): Resuming delayed broadcast
,I/ImageRamCache( 4141): create image Cache, size: 31457280.
I/ImageRamCache( 4141): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4141): create image Cache, size: 12582912.
,I/FeedSettings( 4141): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4141): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4141): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4141): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4141): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4141): loadGridSize() with Alternative
,V/SocialManagerService( 1397): getDataSources
I/SocialManagerService( 1397): plugin added: com.facebook.auth.login
E/SQLiteDatabase( 4141): Failed to open database '/data/data/com.htc.launcher/databases/BiLogClient'.
E/SQLiteDatabase( 4141): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4141): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4141): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4141): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4141): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:145)
E/SQLiteDatabase( 4141): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4141): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4141): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4141): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SocialManagerService( 1397): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1397): plugin added: com.htc.linkedin
I/SocialManagerService( 1397): plugin added: com.htc.venuesrecommend
W/dalvikvm( 4141): threadid=10: thread exiting with uncaught exception (group=0x41723e30)
I/SocialManagerService( 1397): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1397): plugin added: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1397): plugin added: com.htc.drive.activator
I/SocialManagerService( 1397): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1397): plugin added: com.htc.opensense.htcnews
,I/SocialManagerService( 1397): plugin added: com.google
,I/SocialManagerService( 1397): device total memory: 1873M
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1221/10028)
E/AndroidRuntime( 4141): FATAL EXCEPTION: IntentService[BiLogUploadService]
E/AndroidRuntime( 4141): Process: com.htc.launcher:biclient, PID: 4141
E/AndroidRuntime( 4141): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4141): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4141): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4141): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4141): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:145)
E/AndroidRuntime( 4141): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4141): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4141): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4141): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  903): Can't write: snet_gcore
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at com.android.internal.os.IDropBoxManagerService$Stub.onTransact(IDropBoxManagerService.java:62)
E/DropBoxManagerService(  903): 	at android.os.Binder.execTransact(Binder.java:412)
E/DropBoxManagerService(  903): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 6 more
I/SocialManagerService( 1397): groupAccounts
,E/ActivityManager(  903): App crashed! Process: com.htc.launcher:biclient
,I/AdsMeasurementBroadcastReceiver( 1221): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1221): Unauthorized to start the main service
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1456842812340.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
,D/Settings:HtcWirelessFeatureFlags( 3914): id/is att sku: 99/false
,E/SocialManagerService( 1397): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1397): error when get process name! process name is null!
,E/SocialManagerService( 1397): skip binding the plugin without process namecom.htc.drive.activator,
,I/SocialManagerService( 1397): add com.facebook.auth.login to pending queue!
,I/SocialManagerService( 1397): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1397): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1397): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1397): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to pending queue!
,W/SystemReader( 3914): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/SocialManagerService( 1397): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1397): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1397): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1397): add com.google to pending queue!
,I/SocialManagerService( 1397): consume pending plugin session
I/SocialManagerService( 1397): add com.facebook.auth.login to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.facebook.auth.login
,I/SocialManagerService( 1397): com.facebook.auth.login connecting, adding msg, has message?true
,W/SystemReader( 3914): Cannot find support_harman, use default value instead
,W/SystemReader( 3914): Cannot find effect_manager_id, use default value instead
,D/SnetService( 1221): snet destroyed
,E/Settings:HtcWrapHeaderInfo( 3914): no such activity!
,I/SocialManagerService( 1397): add com.htc.linkedin to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.htc.linkedin
,I/SocialManagerService( 1397): com.htc.linkedin connecting, adding msg, has message?true
I/ActivityManager(  903): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=4168 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4180 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3914): The wrap header doesn't exist in header list.
I/SocialManagerService( 1397): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.twitter.android.auth.login
,I/SocialManagerService( 1397): com.twitter.android.auth.login connecting, adding msg, has message?true
,I/SocialManagerService( 1397): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.htc.venuesrecommend
,I/SocialManagerService( 1397): com.htc.venuesrecommend connecting, adding msg, has message?true
,I/SocialManagerService( 1397): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to process map!
,D/LocationSocialPlugin( 3843): onBind
V/SocialManagerService( 1397): initiating bind to plugin type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1397): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connecting, adding msg, has message?true
,I/SocialManagerService( 1397): com.htc.venuesrecommend connected, removed msg, has message?false
I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1397): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
,I/SocialManagerService( 1397): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
,D/LocationIdentityProvider( 3843): is_approved false
,D/LocationSocialPlugin( 3843): account null
,D/LocationSocialPlugin( 3843): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
,E/Settings:HtcWrapHeaderInfo( 3914): updateDevelopment, bPrefShow = true
,D/SocialManagerService( 1397): handling plugin: com.htc.venuesrecommend set result in bg
,I/SocialManagerService( 1397): remove account type: com.htc.venuesrecommend from process map!
,I/SocialManagerService( 1397): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1397): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1397): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
D/StreamPluginService( 3843): getDataSources start
V/SocialManagerService( 1397): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1397): com.htc.opensense.htcnews connecting, adding msg, has message?true
,I/SocialManagerService( 1397): skip to add com.google, plugin per process full!
I/SocialManagerService( 1397): consume pending plugin session
I/SocialManagerService( 1397): skip to add com.google, plugin per process full!
I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1397): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
,I/SocialManagerService( 1397): remove account type: com.htc.socialnetwork.rss.octopus from process map!
,I/SocialManagerService( 1397): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connected, removed msg, has message?false,
V/SocialManagerService( 1397): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1397): consume pending plugin session,
I/SocialManagerService( 1397): skip to add com.google, plugin per process full!
,I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,D/BlinkFeedPluginService( 1838): Set icon to :2130837679
D/BlinkFeedPluginService( 1838): class com.htc.blinkfeed.provider.DummyIdentityProvider
,D/BlinkFeedPluginService( 1838): Not filterable
,E/Settings:HtcUmcWidgetEnabler( 3914): isSupportMusicChannel(): false
,D/SocialManagerService( 1397): handling plugin: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin set result in bg
,W/System  ( 3843): DiskLruCache /data/data/com.htc.launcher/cache/http is corrupt: /data/data/com.htc.launcher/cache/http/journal: open failed: EROFS (Read-only file system), removing
,I/SocialManagerService( 1397): remove account type: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin from process map!
,I/SocialManagerService( 1397): remove process: pl.k2.droidoaudioteka from process map!
V/SocialManagerService( 1397): on plugin completed! plugin session type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
,I/SocialManagerService( 1397): consume pending plugin session
,I/SocialManagerService( 1397): skip to add com.google, plugin per process full!
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]support         :false
,I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{426d9ea0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]support         :false
,I/SocialManagerService( 1397): com.htc.opensense.htcnews connected, removed msg, has message?false
,W/ContextImpl( 4180): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/SocialManagerService( 1397): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1397): remove account type: com.htc.opensense.htcnews from process map!
I/SocialManagerService( 1397): remove process: com.htc.sense.news from process map!
V/SocialManagerService( 1397): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1397): consume pending plugin session
D/PowerUsageService( 4180): call getInstance()
I/SocialManagerService( 1397): skip to add com.google, plugin per process full!
I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,D/PowerUsageList:PowerUsageHelper( 4180): MY_DEBUG = false
,W/FingerprintManager( 3914): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/PMS     (  903): acquireWL(428f3c40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4180 1000 null
W/WeatherUtility( 1115): can't get weather sync account
,E/Settings:HtcVoWifiWidgetEnabler( 3914): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3914): Failed to find provider info for com.htc.vowifi
,D/WeatherUtility( 1397): Weather sync is On
,D/WSP     ( 1397): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/LinkedIn( 4168): contentprovider oncreate getReadableDatabase
W/BatSI   (  903): Couldn't get kernel wake lock stats
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,E/SQLiteDatabase( 4168): Failed to open database '/data/data/com.htc.sense.linkedin/databases/linkedin.db'.
E/SQLiteDatabase( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4168): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.sense.linkedin.provider.a.doInBackground(Unknown Source)
E/SQLiteDatabase( 4168): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4168): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4168): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4168): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4168): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4168): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 4168): Couldn't open linkedin.db for writing (will try read-only):
E/SQLiteOpenHelper( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4168): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.sense.linkedin.provider.a.doInBackground(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 4168):, 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4168): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4168): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4168): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4168): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4180): Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
E/SQLiteDatabase( 4180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.query(SmartSyncProvider.java:161)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4180): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4180): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2019)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4180): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4180): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4180): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4180): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4180): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4180): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4180): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  903): releaseWL(428f3c40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/SQLiteOpenHelper( 4168): Opened linkedin.db in read-only mode
I/SocialManagerService( 1397): com.facebook.auth.login connected, removed msg, has message?false
W/WeatherUtility( 3715): can't get weather sync account
D/LinkedIn( 4168): service onBind
I/SocialManagerService( 1397): com.htc.linkedin connected, removed msg, has message?false
D/g       ( 4168): get htcisdemo: false
D/FacebookSocialPluginService( 4168): get htcisdemo: false
D/Facebook_Session( 4168): MSG_QUERY_ACCOUNT
D/Facebook_Session( 4168): queryAccount
D/Facebook_Session( 4168): queryAccount enter lock
D/Facebook_Session( 4168): Facebook Session created
D/Facebook_Session( 4168): queryAccount
D/SocialManagerService( 1397): handling plugin: com.htc.linkedin set result in bg
E/SQLiteDatabase( 4168): Failed to open database '/data/data/com.htc.sense.socialnetwork.facebook/databases/facebook.db'.
E/SQLiteDatabase( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4168): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteDatabase( 4168): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4168): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4168): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4168): Couldn't open facebook.db for writing (will try read-only):
E/SQLiteOpenHelper( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4168): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4168): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4168): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4168): Opened facebook.db in read-only mode
I/SocialManagerService( 1397): com.twitter.android.auth.login connected, removed msg, has message?false
I/SocialManagerService( 1397): remove account type: com.htc.linkedin from process map!
V/SocialManagerService( 1397): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1397): consume pending plugin session
I/SocialManagerService( 1397): add com.google to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.google
I/SocialManagerService( 1397): com.google connecting, adding msg, has message?true
D/Facebook_Session( 4168): Query Facebook account complete
D/Facebook_Session( 4168): queryAccount enter lock
I/SocialManagerService( 1397): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/Facebook_Session( 4168): Query Facebook account complete
D/SocialManagerService( 1397): handling plugin: com.facebook.auth.login set result in bg
W/WeatherRequest( 3715): request cur loc, but there is no sys cur
W/Settings( 3715): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/SQLiteDatabase( 4168): Failed to open database '/data/data/com.htc.sense.socialnetwork.twitter/databases/htcchirp.db'.
E/SQLiteDatabase( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4168): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4168): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 4168): 	at java.lang.Thread.run(Thread.java:864)
I/SocialManagerService( 1397): remove account type: com.facebook.auth.login from process map!
E/SQLiteOpenHelper( 4168): Couldn't open htcchirp.db for writing (will try read-only):
E/SQLiteOpenHelper( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4168): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4168): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4168): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at java.lang.Thread.run(Thread.java:864)
V/SocialManagerService( 1397): on plugin completed! plugin session type com.facebook.auth.login
I/SocialManagerService( 1397): consume pending plugin session
I/SocialManagerService( 1397): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1397): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1397): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
W/SQLiteOpenHelper( 4168): Opened htcchirp.db in read-only mode
D/GooglePlusSocialPluginService( 4168): Bind
D/AppWidgetHostView( 1268): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1268): com.htc.widget.weatherclock (true,33751552)
D/SocialManagerService( 1397): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1397): remove account type: com.twitter.android.auth.login from process map!
V/SocialManagerService( 1397): on plugin completed! plugin session type com.twitter.android.auth.login
,I/SocialManagerService( 1397): com.google connected, removed msg, has message?false
,I/SocialManagerService( 1397): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
,I/GooglePlusSocialPluginService( 4168): getDataSources start
,D/SocialManagerService( 1397): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
,I/SocialManagerService( 1397): remove account type: com.htc.sense.socialnetwork.instagram from process map!
,I/RemoteViews.Performance( 1268): com.htc.widget.weatherclock 1 10 17
,V/SocialManagerService( 1397): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
,E/SQLiteDatabase( 4168): Failed to open database '/data/data/com.htc.sense.socialnetwork.googleplus/databases/googleplus.db'.
E/SQLiteDatabase( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 4168): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 4168): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 4168): Couldn't open googleplus.db for writing (will try read-only):
E/SQLiteOpenHelper( 4168): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4168): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4168): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4168): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 4168): 	at java.lang.Thread.run(Thread.java:864)
,W/SQLiteOpenHelper( 4168): Opened googleplus.db in read-only mode
,I/GooglePlusSocialPluginService( 4168): getDataSources end
,D/SocialManagerService( 1397): handling plugin: com.google set result in bg
I/SocialManagerService( 1397): remove account type: com.google from process map!
,I/SocialManagerService( 1397): remove process: com.htc.sense.socialplugins from process map!
,D/GooglePlusSocialPluginService( 4168): Unbind
,V/SocialManagerService( 1397): on plugin completed! plugin session type com.google
,I/SocialManagerService( 1397): onSessionCompleted
,I/SocialManager[SocialBiLogHelper]( 3843): social manager disconnect
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3914): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3914): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3914): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3914): [supportHomeButton]support         :false
,W/FingerprintManager( 3914): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3914): isSupportVoWifi: null
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3914): Failed to find provider info for com.htc.vowifi

```
