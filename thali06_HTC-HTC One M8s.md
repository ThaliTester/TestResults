#### Test 61703351a2a4153_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  944): acquireWL(38d1515f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
--------- beginning of main
I/GCoreUlr( 1782): Unbound from all location providers
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 269us total 14.486ms
D/PMS     (  944): releaseWL(38d1515f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(31d4bcfa): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
I/GLSActivity( 1917): [ac] getting account id
W/BaseAppContext( 4251): Using Auth Proxy for data requests.
W/ResourcesManager( 4350): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GCoreUlr( 1782): DispatchingService.onDestroy()
I/GCoreUlr( 1782): Unbound from all location providers
I/GLSUser ( 1917): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1917): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
D/PMS     (  944): acquireWL(2de3a47b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(2de3a47b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1917): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/AuthZen ( 4251): Starting Enrollment...
D/AuthZen ( 4251): getting auth token. Attempt 0
I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AuthZen ( 4251): Error getting auth token
E/AuthZen ( 4251): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4251): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4251): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4251): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4251): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4251): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4251): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4251): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4251): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4251): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4251): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  944): acquireWL(38ea7a62): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 944 1000 null
D/PMS     (  944): releaseWL(38ea7a62): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/a       ( 4251): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 4251): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4251): Clearing transaction cache
I/Babel_SMS( 4350): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4350): MmsConfig.loadMmsSettings
D/MmsCustomizationProvider( 3724): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 3724): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel_SMS( 4350): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 4350): MmsConfig.loadFromDatabase
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4350, uid=10112, userID:0
E/Babel_SMS( 4350): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4350): MmsConfig.loadFromResources
E/Babel_SMS( 4350): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4350): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
W/Settings( 4350): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4350): startup - clean
I/Babel   ( 4350): deleted: false for 0
W/art     ( 4350): Suspending all threads took: 5.663ms
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4350, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4350, uid=10112, userID:0
W/VideoCapabilities( 4350): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4350): Unsupported mime video/x-ms-wmv
W/Utils   ( 4350): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 4350): Unsupported mime audio/qcelp
W/AudioCapabilities( 4350): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4350): Unsupported mime audio/qcelp
W/VideoCapabilities( 4350): Unsupported mime video/x-ms-wmv
I/VideoCapabilities( 4350): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4350): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4350): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4350): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4350): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4350): onServiceConnected
W/Babel   ( 4350): Attempted to change video mute state without an active call.
I/ActivityManager(  944): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4387 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/ResourcesManager( 4387): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4387): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/cutils-trace( 4410): Error opening trace file: Permission denied (13)
V/JNIHelp ( 4387): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System  ( 4387): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4387): Installed default security provider GmsCore_OpenSSL
D/CustomizationManager( 4410): ====startRecUseTime====
D/htc.customization.log.level( 4410):  is 
W/CustomizationLogLevel( 4410): Level value is invalid, use default level 2
D/CustomizationManager( 4410):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4410): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4410): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4410): Parsing tag category name = system
I/CustomizationCIDLoader( 4410): Parsing tag category name = application
I/CustomizationCIDLoader( 4410): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4410): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4410): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4410): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4410): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4410): add string-array item, value = 42507
I/CustomizationCIDLoader( 4410): add string-array item, value = 21902
I/CustomizationCIDLoader( 4410): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4410): add string-array item, value = 23420
I/CustomizationCIDLoader( 4410): add string-array item, value = 22299
I/CustomizationCIDLoader( 4410): add string-array item, value = 24002
I/CustomizationCIDLoader( 4410): add string-array item, value = 23210
I/CustomizationCIDLoader( 4410): add string-array item, value = 23205
I/CustomizationCIDLoader( 4410): add string-array item, value = 23806
I/CustomizationCIDLoader( 4410): add string-array item, value = 23430
I/CustomizationCIDLoader( 4410): add string-array item, value = 23408
I/CustomizationCIDLoader( 4410): add string-array item, value = 27205
I/CustomizationCIDLoader( 4410): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4410): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4410):  Read CID file spent 0.079 (s)
D/CustomizationManager( 4410):  All configurations done spent 0.079 (s)
W/ResourcesManager( 4387): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4387): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4410 on display 0
W/asset   (  944): Copying FileAsset 0x55abdb9060 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  944): acquireHCC(41f31e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(18684b5e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
D/PMS     (  944): acquireWL(1412eb3f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
I/AnimationUtil(  944): isHTCRecent(HelloWorld/Recent screens.)/4
I/FeedHostManager( 1569): [onPause]
I/FeedProviderManager( 1569): onPause
I/FeedHostManager( 1569): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2a9f1704
I/SocialFeedProvider( 1569): +onPause
I/SocialFeedProvider( 1569): -onPause
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  944): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4439 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/cutils-trace( 4438): Error opening trace file: Permission denied (13)
I/dex2oat ( 4438): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1528662733.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads1528662733.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4438): dex2oat: override thread count:4
W/asset   ( 4439): Copying FileAsset 0xaaffd068 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  944): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
I/TrimMemoryManager( 1569): [trimMemory] 20
E/YouTube MDX( 4387): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 4387): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    ( 4387): [NET] android_getaddrinfofornet-, SUCCESS
I/dex2oat ( 4438): dex2oat took 113.939ms (threads: 4)
I/ActivityManager(  944): Waited long enough for: ServiceRecord{15633a6c u0 com.htc.autobot/.htcmodeclient.HtcModeService}
I/WebViewFactory( 4439): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/VoldConnector(  944): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
W/ContextImpl( 4387): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
I/LibraryLoader( 4439): Time to load native libraries: 25 ms (timestamps 5965-5990)
I/LibraryLoader( 4439): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4439): Binding Chromium to main looper Looper (main, tid 1) {3508097}
I/LibraryLoader( 4439): Expected native library version number "",actual native library version number ""
I/chromium( 4439): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4439): Initializing chromium process, singleProcess=true
W/art     ( 4439): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4439): ApplicationContext is null in ApplicationStatus
W/chromium( 4439): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/VoldConnector(  944): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
W/chromium( 4439): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4387): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/VoldConnector(  944): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4387): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
D/VoldConnector(  944): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4387): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
E/libEGL  ( 4439): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4439): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4439): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4439): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4439): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4439): Local Branch: 
I/Adreno-EGL( 4439): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4439): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4439):                  d74aa161a12b9c6fc6332151
W/InstanceID/Rpc( 4387): Found 10024
D/VoldConnector(  944): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4387): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/System.err(  944): java.lang.Throwable: stack dump
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c37f104:true
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4439): 605196083: getState() :  mService = null. Returning STATE_OFF
I/HtcModeClient( 3160): handler message = 4011
E/HtcModeClient( 3160): Check connection and retry 3 times.
W/art     ( 4439): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4439): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4439): CordovaWebView is running on device made by: HTC
W/art     ( 4439): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4439): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  944): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4527 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  944): Killing 3861:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3861
W/chromium( 4439): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  944): Recipient 3861
D/FindExtension( 4439): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 4439): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@f58b820, mServedView=org.apache.cordova.engine.SystemWebView{19a055d9 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@242db9e
I/InputMethodManagerService(  944): Disable input method client, pid=1569
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=4439
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  944): Displayed com.example.hello/.MainActivity: +959ms
D/PMS     (  944): releaseWL(1412eb3f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 4439): Cannot call determinedVisibility() - never saw a connection for the pid: 4439
W/XT9_C   ( 1374): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1374): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1374): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1374): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/chromium( 4439): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/Gmail   ( 4527): getAccountsCursor
D/JsMessageQueue( 4439): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4439): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/art     (  944): Explicit concurrent mark sweep GC freed 16875(943KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 1.882ms total 132.389ms
V/AlarmManager(  944): sending alarm PendingIntent{fa2db85: PendingIntentRecord{15182dda com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=55076, Int=259200000
V/AlarmManager(  944): sending alarm PendingIntent{3e5008e8: PendingIntentRecord{363aab01 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457094147332, Int=0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4527, uid=10106, userID:0
W/ActivityManager(  944): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4527, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4527, uid=10106, userID:0
I/Gmail   ( 4527): Observing account changes for notifications
W/GAV2    ( 4527): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/jxcore_app_log( 4439): JniHelper::setJavaVM(0xaaf798f8), pthread_self() = -1406377168
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 4527): Error finding the version of the Email provider.....
E/Gmail   ( 4527): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4527): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4527): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4527): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4527): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4527): 	at android.os.Looper.loop(Looper.java:155)
,E/Gmail   ( 4527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4527): We do not support migrating this version of the Email provider.,
W/jxcore-log( 4439): Initializing JXcore engine,
W/jxcore-log( 4439): JXcore engine is ready
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4527, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4527, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4527, uid=10106, userID:0
,I/Gmail   ( 4527): getAccountsCursor
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4527, uid=10106, userID:0
,I/iu.UploadsManager( 4251): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4583 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4527, uid=10106, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4527, uid=10106, userID:0
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4527): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@112b684e that was originally bound here
E/ActivityThread( 4527): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@112b684e that was originally bound here
E/ActivityThread( 4527): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4527): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4527): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4527): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4527): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4527): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4527): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4527): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4527): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4527): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4527): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4527): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4527): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4527): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  944): Unbind failed: could not find connection for android.os.BinderProxy@1fd37cf
,W/jxcore-log( 4439): Starting JXcore engine
,I/iu.UploadsManager( 4251): End new media; added: 0, uploading: 0, time: 77 ms,
,E/SQLiteLog( 4527): (283) recovered 1463 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,W/jxcore-log( 4439): Platform android,
W/jxcore-log( 4439): 
W/jxcore-log( 4439): Process ARCH arm
W/jxcore-log( 4439): 
,E/AndroidHttpClient( 4188): Leak found
E/AndroidHttpClient( 4188): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4188): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4188): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4188): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4188): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4188): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4188): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4188): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4188): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4188): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4188): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/jxcore-log( 4439): JXcore Cordova bridge is ready!,
I/jxcore-log( 4439): 
,W/jxcore-log( 4439): JXcore engine is started
,E/jxcore  ( 4439): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 4439): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/Gmail   ( 4527): notifyAccountChanged
,I/Gmail   ( 4527): getAccountsCursor
,I/Gmail   ( 4527): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Gmail   ( 4527): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  944): acquireWL(77f571d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4527 10106 null
,I/Gmail   ( 4527): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  944): acquireWL(77f571d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4527 10106 null
,I/Gmail   ( 4527): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  944): acquireWL(77f571d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4527 10106 null
,I/Gmail   ( 4527): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4527, uid=10106, userID:0
I/Gmail   ( 4527): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  944): Killing 3886:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=3886
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/FindExtension( 4439): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/Gmail   ( 4527): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  944): Recipient 3886
,D/LocationManagerService(  944): getProviders()=[passive],
,I/Gmail   ( 4527): master sync=false, engine sync=true,
,I/ActivityManager(  944): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4615 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4583, uid=10085, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4583, uid=10085, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4583, uid=10085, userID:0
,I/Gmail   ( 4527): getAccountsCursor,
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4527): master sync=false, engine sync=true,
,D/PMS     (  944): releaseHCC(41f31e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  944): releaseHCC(18684b5e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiTrafficPoller(  944): ADD_CLIENT: 6
D/WifiService(  944): New client listening to asynchronous messages
,W/BroadcastQueue(  944): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/VelvetNetworkClient( 4583): Network connection not availble
,I/ActivityManager(  944): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4652 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=3934
I/ActivityManager(  944): Killing 3934:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  944): Recipient 3934
,D/Process (  944): killProcessQuiet, pid=3973,
I/ActivityManager(  944): Killing 3973:com.htc.cs.dm/u0a99 (adj 15): empty #17,
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3973
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  944): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4676 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0,
,W/ResourcesManager( 4676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49,
D/AccFlag ( 1525): sku_id=118
I/MultiDex( 4676): VM with version 2.1.0 has multidex support
I/MultiDex( 4676): install
I/MultiDex( 4676): VM has multidex support, MultiDex support library is disabled.,
,I/ActivityManager(  944): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4702 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/LocationInitializer( 4251): Restart initialization of location,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1525): sku_id=118
,V/JNIHelp ( 4676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 78,
,D/AccFlag ( 1525): sku_id=118,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92,
D/AccFlag ( 1525): sku_id=118
,W/ActivityThread( 4676): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@402c680: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4676): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4676): callingUid 10024, callindPid: 4676,
,E/MDM     ( 1782): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ImageRamCache( 4702): create image Cache, size: 31457280.
I/ImageRamCache( 4702): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4702): create image Cache, size: 31457280.
,I/FeedSettings( 4702): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 4702): GroupBudget 0.500000 0.380000
I/FeedSettings( 4702): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4702): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4702): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4702): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 4702): [custom highlight] onReceive
,D/CustomHighlightService( 4702): [custom highlight] onHandleIntent,
D/NewsDB  ( 4702): set custom highlight []
,I/ActivityManager(  944): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4731 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/CustomHighlightService( 4702): [custom highlight] set tags 
,D/Process (  944): killProcessQuiet, pid=3998
I/ActivityManager(  944): Killing 3998:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3998,
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4754 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=4029,
I/ActivityManager(  944): Killing 4029:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 4029
,I/art     (  944): Explicit concurrent mark sweep GC freed 10094(520KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.384ms total 160.062ms
,D/SMSBackup( 4754): Got a database change event,
,I/ActivityManager(  944): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4775 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=4097,
I/ActivityManager(  944): Killing 4097:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  407): Explicit concurrent mark sweep GC freed 8642(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 147us total 19.642ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 17.736ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 21.918ms
,I/ActivityManager(  944): Recipient 4097,
,D/MessagingShortcutReceiver( 3724): keep hiding shortcut bubble,
D/MessagingShortcut( 3724): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3724): After query: 0,
D/MessagingShortcut( 3724): mPresentUnreadCount: -1
,D/MessageUtils( 3724): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 3724): setMsgShortcutDrawable> 0, false,
,D/MessagingShortcut( 3724): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1308): [EventService] reorderNotification, total:0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  944): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4798 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 4798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4819 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/TodoTaskshortcut( 4798): update TASK shortcut>,
D/PMS     (  944): acquireWL(f0d5f16): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4798 10069 null
,D/PMS     (  944): acquireWL(1cae6097): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4798 10069 null
,D/PMS     (  944): releaseWL(f0d5f16): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4798): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4798): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4798): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4798): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 4798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4798): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4798): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  944): releaseWL(1cae6097): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4798): stopSelfResult true
,D/PMS     (  944): releaseWL(77f571d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
,I/ActivityManager(  944): Killing 4119:com.android.settings:remote/1000 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=4119
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdScBootUi( 4775): [84a.1.2.] boot 118
,D/MdScBoot( 4775): [84a.1.] 30@-122200 -> 40
D/PMS     (  944): acquireWL(b0a8a6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms},
D/MdScSimSt( 4775): [84a.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  944): Recipient 4119
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,D/MtpReceiver( 3665): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3665): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3665): [MTP][handleUsbState]+
,I/ActivityManager(  944): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4848 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager(  944): Killing 4144:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4144,
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/PMS     (  944): releaseWL(b0a8a6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Recipient 4144
,D/MtpReceiver( 3665): [MTP][scanExternalVolumeIfNeed] scan external volume,
,D/MtpService( 3665): updating state; isCurrentUser=true, mMtpLocked=false
I/ActivityManager(  944): Killing 4167:com.android.smith/1000 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=4167
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  944): Recipient 4167,
,D/MtpReceiver( 3665): [MTP][handleUsbState]-
D/MtpReceiver( 3665): [MTP][handleMessage]-
,D/MtpDatabase( 3665): TotalSize=1886532,MediaCacheLimit=6000,
D/SyncApplication( 4848): Loading default preferences
,D/MtpService( 3665): [isMtpConnected] connected: true
,W/Resources( 4848): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7,
D/WifiService(  944): New client listening to asynchronous messages
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/SyncApplication( 4848): Overriding preferences with custom values,
,D/SyncApplication( 4848): Updating preferences succeeded
,E/SyncApplication( 4848): Application created.,
,W/VolumeInfo( 4848): Unable to read mount points
W/VolumeInfo( 4848): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4848): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4848): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4848): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4848): ,	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4848): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4848): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4848): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4848): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4848): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4848): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4848): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4848): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4848): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4848): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4848): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4848): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4848): 	... 13 more
I/CalendarDefines( 4848): getNewCalendarAuthority()...
,V/VolumeInfo( 4848): Found 0 mount point(s)
V/VolumeInfo( 4848): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4848, uid=10005, userID:0
,W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync,
,D/VolumeInfo( 4848): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4848, uid=10005, userID:0
D/SyncApplication( 4848): enableAppOperation()+
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 4848): enableAppOperation()-,
,E/MediaScannerService( 3665): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3665): [handleMessage] --- Should not be here, ignore request. ----
,D/HTCUtilities( 4848): isNeorSinged() + 
,D/VolumeInfo( 4848): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 4848): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 4848): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4848): isNeorSinged() return false,
,D/CDMountReceiver( 4848): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4848): USB connected to PC
,D/FOTAReceiver( 4848): onReceive() enter ,
D/FOTAReceiver( 4848): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 4077): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 4077): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4077): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4077): Cust_ConnectToPC   : spcsc>false
D/        ( 4077): Cust_ConnectToPC   : IPT>true
,D/        ( 4077): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4077): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4077): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4077): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4077): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false,
D/SmartNS_Utility( 4077): usb_cable_connect = 1
D/SmartNS_Utility( 4077): usb_denied = 0
,I/SmartNS_NSReceiver( 4077): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4077): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4077): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 4077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 4077): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 4077): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4077):  defaultType:0
I/SmartNS_PSService( 4077): fail notificaiton:false
D/SmartNS_Utility( 4077): usb_cable_connect = 1,
D/SmartNS_Utility( 4077): usb_denied = 0
I/SmartNS_PSService( 4077): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
I/ActivityManager(  944): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4878 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/SmartNS_Utility( 4077): usb_cable_connect = 1
D/SmartNS_Utility( 4077): usb_denied = 0
I/SmartNS_PSService( 4077): usb notificaiton:true
,E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false,
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/SmartNS_Utility( 4077): usb_cable_connect = 1
D/SmartNS_Utility( 4077): usb_denied = 0
E/MediaScannerServiceEx( 3665): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3665): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/MediaScannerServiceEx( 3665): [handleExternalVolume] ext storage,
D/MediaProviderUtils( 3665): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3665): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3665): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3665): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3665): [AliveExtStorageRows]+65537, 11223344
I/SmartNS_PSService( 4077): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4077): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  944): Killing 3259:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3259
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/MediaProvider( 3665): [update][8]#0#
,D/MediaProvider( 3665): [update][3]#0#
,D/MediaProvider( 3665): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 3665): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3665): [update][9]#1#,
D/MediaScannerServiceEx( 3665): [AliveExtStorageRows]-0, 0
D/PMS     (  944): acquireWL(23485008): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3665 10017 null
,I/ActivityManager(  944): Recipient 3259,
,D/MediaScanner( 3665): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,W/ContextImpl( 4878): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4900 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=4225,
I/ActivityManager(  944): Killing 4225:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4225
,W/ResourcesManager( 4900): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/CalendarProvider2( 4900): Created com.android.providers.calendar.CalendarAlarmManager@63ff16(com.htc.providers.calendar.HtcCalendarProvider@3508097)
,D/CalendarProvider2( 4900): wait start:true,
,D/FlexNetS( 4900): updateSvcAllowedInSettings:false
,D/CalendarProvider2( 4900): wait end:false,
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{1c50d67 u0 com.htc.HTCSpeaker/.NGFService}
,D/Prism.PackageStateRece_( 1569): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1499): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1499): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  944): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4929 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 4929): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4929 dbg=false s=true,
,I/DeviceManagement( 4929): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  944): killProcessQuiet, pid=4188
I/ActivityManager(  944): Killing 4188:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  944): Recipient 4188,
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 4 times.
,I/ActivityManager(  944): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4951 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/HtcCupdReceiver(Provider)( 4951):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  944): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4973 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  944): killProcessQuiet, pid=4387,
I/ActivityManager(  944): Killing 4387:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 4077): id/is att sku: 118/false
,D/MediaProvider( 3665): [update][27]#1#
,D/MediaScanner( 3665):  prescan time: 416ms,
D/MediaScanner( 3665):     scan time: 652ms
,D/MediaScanner( 3665): postscan time: 3ms
,E/Settings:HtcWrapHeaderInfo( 4077): no such activity!
D/MediaScanner( 3665):    total time: 1071ms
D/MediaScanner( 3665): -----------------------------------------------------------------
D/MediaScanner( 3665): firstscan(media) time: 317ms
D/MediaScanner( 3665): secondscan(non-media) time: 335ms
D/MediaScanner( 3665):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3665):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3665):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3665):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,I/ActivityManager(  944): Recipient 4387
,D/MediaProvider( 3665): [delete][15]
D/MediaProvider( 3665): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3665): [recoverParentNodes] - 0
D/MediaProvider( 3665): [update][5]
D/MediaScannerServiceEx( 3665): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3665): [updateImage]+
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4077): The wrap header doesn't exist in header list.,
,D/MediaScannerServiceEx( 3665): [updateImage]-0,
,E/Settings:HtcWrapHeaderInfo( 4077): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 4077): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]support         :false
D/PMS     (  944): releaseWL(23485008): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3665): [1] scan finished
D/MediaProviderUtils( 3665): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3665): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3665): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3665): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3665): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3665): [disAliveExtStorageRows]+131073
D/MediaProvider( 3665): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3665): [update][7]#1#
I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 4077): isSupportVoWifi: null
E/ActivityThread( 4077): Failed to find provider info for com.htc.vowifi
D/MediaProvider( 3665): [update][22]#0#
D/MediaScannerServiceEx( 3665): [disAliveExtStorageRows]--1, 0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4077): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4077): updateDevelopment, bPrefShow = true
D/MediaProviderUtils( 3665): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3665): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3665): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3665): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3665): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3665): [disAliveExtStorageRows]+196609,
,E/Settings:HtcUmcWidgetEnabler( 4077): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4077): [supportHomeButton]support         :false
,D/MediaProvider( 3665): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3665): [update][8]#1#
,E/Settings:HtcVoWifiWidgetEnabler( 4077): isSupportVoWifi: null,
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4077): Failed to find provider info for com.htc.vowifi
,D/MediaProvider( 3665): [update][21]#0#
,D/MediaScannerServiceEx( 3665): [disAliveExtStorageRows]--1, 0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4973, uid=10072, userID:0,
,W/global  ( 4973): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 4973): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 4973): [apache-http] Connection GC has been deprecated!,
,W/global  ( 4973): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 4973): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  944): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5014 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/CalendarProvider2( 4900): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4900): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  944): Killing 4527:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4527
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Settings( 4973): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4973): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4973, uid=10072, userID:0
,I/ActivityManager(  944): Recipient 4527
,W/ResourcesManager( 5014): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5014): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5014): VM with version 2.1.0 has multidex support,
I/MultiDex( 5014): install
I/MultiDex( 5014): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 1917): Explicit concurrent mark sweep GC freed 9861(528KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.224ms total 59.651ms
,V/JNIHelp ( 5014): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Process (  944): killProcessQuiet, pid=4583
I/ActivityManager(  944): Killing 4583:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/ActivityThread( 5014): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5014): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@402c680: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5014): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  944): Recipient 4583
,D/WifiService(  944): Client connection lost with reason: 4
,D/Finsky  ( 4973): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4973): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4973): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,D/PackageBroadcastService( 4251): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4251): Loading module APK com.google.android.play.games
D/Finsky  ( 4973): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PMS     (  944): acquireWL(2c592a7c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4251 10024 null,
,I/ConfigFetchService( 4251): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  944): acquireWL(3bbbbb2): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4251 10024 WorkSource{10374 com.example.hello},
I/ConfigFetchService( 4251): launchTask
,D/PMS     (  944): releaseWL(2c592a7c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  944): acquireWL(27cb5703): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  944): killProcessQuiet, pid=4702
I/ActivityManager(  944): Killing 4702:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4251): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4251): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
,D/Vision  ( 4251): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) },
D/Vision  ( 4251): Failed to find package metadata for com.example.hello
D/Vision  ( 4251): No vision deps
,I/GoogleURLConnFactory( 4251): Using platform SSLCertificateSocketFactory,
,I/ActivityManager(  944): Recipient 4702
,I/ActivityManager(  944): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5056 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/PeopleContactsSync( 4251): CP2 sync disabled
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4251, uid=10024, userID:0
,V/Finsky  ( 4973): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager(  944): sending alarm PendingIntent{337a2aac: PendingIntentRecord{110cc375 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094153258, Int=0,
D/Finsky  ( 4973): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
D/libc    ( 4251): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4251): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4251): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4251): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4251): [NET] android_getaddrinfo_proxy+
D/libc    ( 4251): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4251): [NET] android_getaddrinfo_proxy-, NODATA
W/ConfigFetchTask( 4251): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 4251): fetch service done; releasing wakelock
,D/PMS     (  944): releaseWL(3bbbbb2): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
I/ConfigFetchService( 4251): stopping self
,I/Icing   ( 4251): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
W/Icing   ( 4251): Received bad json for section weights override -- ignoring.
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.,
I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Icing   ( 4251): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4251): Received bad json for section weights override -- ignoring.
W/Icing   ( 4251): Received bad json for corpus context scoring override -- ignoring.
,W/BaseAppContext( 4251): Using Auth Proxy for data requests.
,W/Finsky  ( 4973): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,E/Icing   ( 4251): Loading extension by file descriptor -1 failed,
,I/art     (  944): Explicit concurrent mark sweep GC freed 14246(677KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.446ms total 180.258ms,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4973): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Icing   ( 4251): updateResources: need to parse f{com.google.android.gms}
,E/AndroidHttpClient( 4973): Leak found
E/AndroidHttpClient( 4973): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4973): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4973): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4973): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
,E/AndroidHttpClient( 4973): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4973): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4973): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4973): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4973): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4973): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4973): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4973): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Icing   ( 4251): Internal init done: storage state 0
,I/Icing   ( 4251): Post-init done
,D/PMS     (  944): releaseWL(27cb5703): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/SocialFeedProvider( 1569): +disConnect socialManager,
I/SocialFeedProvider( 1569): disconnect socialManager
I/SocialFeedProvider( 1569): -disConnect socialManager
,I/GAv4    ( 5056): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5056):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5056):   adb logcat -s GAv4
,W/GAv4    ( 5056): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5056): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4251): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  944): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5097 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  944): sending alarm PendingIntent{632050d: PendingIntentRecord{15e44cc2 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457094153927, Int=0
,W/GAv4    ( 5056): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5056): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,I/art     (  407): Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 178us total 20.670ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 197us total 17.317ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 17.325ms
,I/ImageRamCache( 5097): create image Cache, size: 31457280.
I/ImageRamCache( 5097): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5097): create image Cache, size: 31457280.
,I/FeedSettings( 5097): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5097): GroupBudget 0.500000 0.380000,
I/FeedSettings( 5097): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5097): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5097): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5097): loadGridSize() with Alternative
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/SocialManager[SocialBiLogHelper]( 5097): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5097): last commit ulog time 1457013518977
I/SocialManager[SocialBiLogHelper]( 5097): skip commit this time
,D/VoldConnector(  944): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5056): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  944): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5132 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  944): Killing 4731:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=4731
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5056): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5056): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Recipient 4731,
,W/ResourcesManager( 5132): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 5056): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Finsky  ( 4973): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 4973): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 4973): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4973): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,W/System  ( 5056): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5056): Installed default security provider GmsCore_OpenSSL
,W/art     ( 5056): Suspending all threads took: 5.958ms,
I/ActivityManager(  944): Killing 4775:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4775
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/DeviceConnectionService( 1782): client connected with version: 7571000
,I/ActivityManager(  944): Recipient 4775
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4251, uid=10024, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4251, uid=10024, userID:0
,D/Process (  944): killProcessQuiet, pid=4754
I/ActivityManager(  944): Killing 4754:com.htc.mms.backupagent/u0a76 (adj 15): empty #18
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4754
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  944): Killing 3724:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=3724
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3724
,D/AccTypeManager( 1698): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1698): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader(  944): Cannot find grip_rejection_width, use default value instead
,W/ResourcesManager(  944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1569): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1569): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1569): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1569): Deferring update until onResume
D/Launcher( 1569): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1698): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 5097): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5097): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PhoneApp( 1525): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1698): Unsupported attribute readOnly
,D/PMS     (  944): acquireWL(fe17b1b): PARTIAL_WAKE_LOCK  AsyncService 0x1 5132 10167 null,
,D/PMS     (  944): acquireWL(187bd291): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5132 10167 null,
,D/PMS     (  944): releaseWL(fe17b1b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  944): releaseWL(187bd291): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/PackageManager(  944): Unable to load service info ResolveInfo{bbe4285 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  944): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  944): 	,at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950),
W/PackageManager(  944): ,	,at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  944): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  944): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5164 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=4819
I/ActivityManager(  944): Killing 4819:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/BackupManagerService(  944): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  944): Recipient 4819
,V/GmsNetworkLocationProvi( 1782): DISABLE,
,I/GCoreNlp( 1782): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/LocationProviderProxy(  944): applying state to connected service
,D/PMS     (  944): acquireWL(3e4bd769): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): releaseWL(3e4bd769): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  944): applying state to connected service
,D/PMS     (  944): acquireWL(2622e5ee): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): acquireWL(22fe9a8f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(2622e5ee): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(22fe9a8f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(3c18125): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3c18125): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5187 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/ContextImpl( 5187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5187): MY_DEBUG = false
,D/PMS     (  944): acquireWL(95450ab): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5187 1000 null
,I/ActivityManager(  944): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5216 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/PowerUsageService( 5187): repeat time = 1457095055541
,D/WeatherUtility( 1499): Weather sync is On,
,D/LocationManagerService(  944): getProviders()=[passive]
D/WSP     ( 1499): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PMS     (  944): acquireWL(255acb20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1917): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1917): [NET] android_getaddrinfo_proxy+
D/libc    ( 1917): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1917): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(255acb20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5244 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,D/WeatherUtility( 5216): Weather sync is On
,W/ResourcesManager( 5244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5268 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/PowerUsageList:PowerUsageHelper( 5187): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/UpdateIcingCorporaServi( 5164): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PMS     (  944): acquireWL(1ef1794c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(1ef1794c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
,D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: E msg.what=155652
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: ApStaDisabledState
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: X
D/WifiController(  944): battery changed pluggedType: 2
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,D/PowerUsageList:BatterySipperExt( 5187): gen(), null == sipper.uidObj, userId = 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,W/asset   ( 5164): Copying FileAsset 0x55ab9827e0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,I/art     (  944): Explicit concurrent mark sweep GC freed 23495(1238KB) AllocSpace objects, 2(312KB) LOS objects, 33% free, 16MB/24MB, paused 1.518ms total 174.455ms,
,W/WeatherRequest( 5216): request cur loc, but there is no sys cur,
W/Settings( 5216): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5216): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1569): reapply : com.htc.widget.weatherclock 5 17,
,I/EASAppSvc( 5268): [ NA ]onCreate
,I/VersionUtil( 5268): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5268): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5268): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5268): Set CursorWindow size to: 4194304 KB, Tid: 5292
,D/ORMLib  ( 4798): put()
,I/ActivityManager(  944): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5297 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/SQLiteLog( 5244): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7,
D/WifiService(  944): New client listening to asynchronous messages
,W/EAS_NetworkUtil( 5268): [ NA ]getNetworkInfo: NetworkInfo is null,
,D/PowerUsageService( 5187): calcPower(), no data,
,D/Process (  944): killProcessQuiet, pid=4350
I/ActivityManager(  944): Killing 4350:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/MusicStore( 5297): Database version: 120,
,I/ActivityManager(  944): Recipient 4350
,I/EASAppSvc( 5268): [ NA ]onDestroy,
I/EASAppSvc( 5268): [ NA ]> uninitEASService
,I/EASAppSvc( 5268): [ NA ]onCreate,
D/PMS     (  944): acquireWL(2a216d81): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms},
,I/EASRequestController( 5268): [ NA ]release
,D/PMS     (  944): releaseWL(2a216d81): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/VersionUtil( 5268): [ NA ]setIsFOTAing: true
,D/PMS     (  944): acquireWL(6b57603): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
,I/VersionUtil( 5268): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5268): [ NA ]setIsFOTAing: false
,W/EAS_NetworkUtil( 5268): [ NA ]getNetworkInfo: NetworkInfo is null
,D/ORMLib  ( 4798): put()
D/EASPublicBinder( 5268): [ NA ]release
D/TaskBinder( 5268): [ NA ]release
D/TaskBinder( 5268): [ NA ]release
I/EASAppSvc( 5268): [ NA ]< uninitEASService
,I/EASAppSvc( 5268): [ NA ]onDestroy
I/EASAppSvc( 5268): [ NA ]> uninitEASService,
,I/ActivityManager(  944): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5341 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/EASRequestController( 5268): [ NA ]release
,D/EASPublicBinder( 5268): [ NA ]release,
D/TaskBinder( 5268): [ NA ]release
D/TaskBinder( 5268): [ NA ]release
I/EASAppSvc( 5268): [ NA ]< uninitEASService
,I/art     ( 1917): Explicit concurrent mark sweep GC freed 13548(756KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 611us total 42.268ms,
,I/Prism.ItemManager( 1569): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1569): loadItems() com.htc.launcher.pageview.WidgetManager@145c23a8 +
I/Prism.WidgetManager( 1569): onLoadItems() +
,D/VoldConnector(  944): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5297): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/Prism.ItemManager( 5097): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5097): loadItems() com.htc.launcher.pageview.WidgetManager@35dceb8f +
I/Prism.WidgetManager( 5097): onLoadItems() +
,I/UpdateIcingCorporaServi( 5164): UpdateCorporaTask done [took 800 ms] updated apps [took 800 ms] 
,D/Process (  944): killProcessQuiet, pid=4848
,I/ActivityManager(  944): Killing 4848:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 1569): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 5097): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Recipient 4848
D/WifiService(  944): Client connection lost with reason: 4
,I/ActivityManager(  944): Killing 4878:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4878
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,D/ORMLib  ( 4798): put()
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 5 times.
,W/ResourcesManager( 1569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5097): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  944): Recipient 4878,
,W/asset   ( 1569): Copying FileAsset 0x55abddfd80 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 5097): Copying FileAsset 0x55abad6960 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,V/AlarmManager(  944): sending alarm PendingIntent{2f65f32d: PendingIntentRecord{4e7062 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457094156591, Int=0
,D/Process (  944): killProcessQuiet, pid=4900,
,I/ActivityManager(  944): Killing 4900:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Prism.WidgetManager( 1569): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1569): onLoadItems() -
I/Prism.ItemManager( 1569): loadItems() com.htc.launcher.pageview.WidgetManager@145c23a8 -
,D/VoldConnector(  944): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
I/Prism.WidgetManager( 5097): onLoadItems() -
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
I/Prism.ItemManager( 5097): loadItems() com.htc.launcher.pageview.WidgetManager@35dceb8f -
W/ContextImpl( 5297): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  944): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5297): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/ActivityManager(  944): Recipient 4900
,D/PhoneApp( 1525): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1525): -- N1 =0,
,D/PhoneApp( 1525): -- N2 =0
,D/PhoneApp( 1525): -- N3 =0,
,D/Process (  944): killProcessQuiet, pid=4615,
I/ActivityManager(  944): Killing 4615:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  944): Recipient 4615,
,W/ResourcesManager( 5297): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5297): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5297): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5297): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5297): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33c37a6a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5297): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5297): GMSCore installation verified
,I/ConfigStore( 5297): Config Database version: 1,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5297, uid=10159, userID:0
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
,I/Icing   ( 4251): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,D/MediaRouterService(  944): Client com.google.android.music (pid 5297): Registered,
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
,I/MediaRouter( 5297): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5375 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/PMS     (  944): releaseWL(95450ab): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ResourcesManager( 5375): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5297, uid=10159, userID:0
,I/Icing   ( 4251): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376
,I/GHttpClientFactory( 5297): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5297): Using platform SSLCertificateSocketFactory,
,D/PMS     (  944): releaseWL(6b57603): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/CalendarProvider2( 5375): Created com.android.providers.calendar.CalendarAlarmManager@63ff16(com.htc.providers.calendar.HtcCalendarProvider@3508097),
,D/CalendarProvider2( 5375): wait start:true
,D/Process (  944): killProcessQuiet, pid=4929
,I/ActivityManager(  944): Killing 4929:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4929,
,D/PMS     (  944): acquireWL(6758640): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5375 10011 null,
,D/CalendarProvider2( 5375): wait end:false,
,D/TelephonyReceiver( 1525): bind: true,
,E/SQLiteLog( 5375): (284) automatic index on view_events(_id)
,I/ActivityManager(  944): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5406 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  944): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5425 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/PMS     (  944): releaseWL(6758640): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/DFPI.ApkInstallService( 5406): onHandleIntent
,I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,W/HtcWrapAdjustableCursorFactory( 5425): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
,D/MessageFrequencyProvider( 5425): onCreate
,I/ActivityManager(  944): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5452 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/GetPrviateResource( 5425): GetPrviateResource,
V/GetPrviateResource( 5425): GetPrviateResource
,D/MessageCustFlag( 5425): sense_version=6.0,
,D/BTAccessoryUtil( 5425): createReceiver,
D/GenericMessagesProvider( 5425): query uri: content://htc-messages/wappush/count
,D/BTAccessoryUtil( 5425): registerReceiver return intent = null
,E/SQLiteLog( 5425): (14) cannot open file at line 30058 of [9491ba7d73]
,E/SQLiteLog( 5425): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5425): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5425): DB info: errno = 2, errno message = No such file or directory,
D/MessageCustFlag( 5425): sku_id=118
,D/HtcBuildUtils( 5425): getRATByHtcTelephonyCapability:1,
E/SQLiteDatabase( 5425): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5425): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5425): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5425): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5425): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5425): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5425): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5425): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5425): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 5425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,W/System.err( 5425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
,W/System.err( 5425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5425): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
I/ActivityManager(  944): Killing 4951:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
W/System.err( 5425): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5425): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5425): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5425): 	at android.os.Binder.execTransact(Binder.java:454)
W/SystemReader( 5425): Cannot find qct_8960_interface, use default value instead
D/Process (  944): killProcessQuiet, pid=4951
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  944): Recipient 4951
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null
,I/ActivityManager(  944): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5477 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  944): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/ContextImpl( 5452): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm),
,I/ActivityManager(  944): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5503 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4),
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96,
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5406): onHandleIntent
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
D/Process (  944): killProcessQuiet, pid=4077
I/ActivityManager(  944): Killing 4077:com.android.settings/1000 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4077
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
I/ConfigService( 1917): onDestroy
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/art     (  944): Explicit concurrent mark sweep GC freed 25145(1231KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.897ms total 154.145ms
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/DFPI.ApkInstallService( 5406): onHandleIntent
,I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  944): Resuming delayed broadcast
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/DFPI.ApkInstallService( 5406): onHandleIntent
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Resuming delayed broadcast
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/TelephonyReceiver( 1525): bind: false
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
V/AlarmManager(  944): sending alarm PendingIntent{175ac4d2: PendingIntentRecord{2609f9a3 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457094158492, Int=0
,I/DFPI.ApkInstallService( 5406): onHandleIntent
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5406): check CID = HTC__102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Resuming delayed broadcast
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5406): onHandleIntent
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Resuming delayed broadcast
I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/DFPI.ApkInstallService( 5406): onHandleIntent
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Resuming delayed broadcast
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActionCombine( 5503): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false,
D/WearableService( 4676): callingUid 10024, callindPid: 4676
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/LocationInitializer( 4251): Restart initialization of location
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/MDM     ( 1782): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/RemoteViews( 1221): apply : com.htc.updater 1 12 2 36
,V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
,E/MDM     ( 1782): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/LocationInitializer( 4251): Restart initialization of location
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/FindExtension( 1221): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/ThreadedRenderer( 1221): Defer allocateBuffers to drawing time
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96,
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/CalendarProvider2( 5375): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 5375): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/PMS     (  944): acquireWL(23dd1cf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  944): releaseWL(23dd1cf7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/PMS     (  944): acquireWL(202c764): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  944): releaseWL(202c764): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102,
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122,
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/art     (  944): Explicit concurrent mark sweep GC freed 9018(442KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.171ms total 170.914ms,
,D/PMS     (  944): acquireWL(314b3ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  944): releaseWL(314b3ef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/ActivityManager(  944): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5551 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/Process (  944): killProcessQuiet, pid=5014
I/ActivityManager(  944): Killing 5014:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PhoneMonitor( 5551): Register our PhoneStateListener
,I/ActivityManager(  944): Recipient 5014
,I/ActivityManager(  944): Killing 4973:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=4973
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5551): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5551): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,I/ActivityManager(  944): Recipient 4973
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4251): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4251): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  944): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5575 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/art     (  407): Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 217us total 26.010ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 186us total 23.478ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 22.224ms
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/Gmail   ( 5575): getAccountsCursor,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/GAV2    ( 5575): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5575, uid=10106, userID:0
,W/ActivityManager(  944): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5575): Observing account changes for notifications
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5575, uid=10106, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5575, uid=10106, userID:0
,W/ActivityManager(  944): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,D/Messaging( 5425): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5425): networkCode: 
D/MessageCustFlag( 5425): sku_id=118
D/MmsConfig( 5425): SIE smsPri: null
D/MmsConfig( 5425): networkCode: ,
,D/MmsConfig( 5425): packageName: com.htc.vvm.att does not exist
,D/Messaging( 5425): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5425): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 5425): ,
D/MmsAsyncWorkHandler( 5425): HM tk = 20001
D/ReportIndicatorCache( 5425): MSG_QUERY_REPORTS >>
D/SettingsManager( 5425): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3c3ef284
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1525): sku_id=118
,D/DraftCache( 5425): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5425): [DraftCache/1] refresh
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/DraftCache( 5425): [DraftCache/121] rebuildCache
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
E/Gmail   ( 5575): Error finding the version of the Email provider.....
E/Gmail   ( 5575): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5575): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5575): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5575): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5575): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5575): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5575): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5575): We do not support migrating this version of the Email provider.
I/Messaging( 5425): mccmnc> 
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1525):  slotId = -1000
,D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MmsConfig( 5425): networkCode: 
I/Gmail   ( 5575): getAccountsCursor
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5425): mNeedToUpdateDate2: false
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1525):  slotId = -1000
D/MmsSmsV2Provider( 1525): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5620 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Messaging( 5425): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Messaging( 5425): ViewCache CreatePreloadOnlyConversationList,
V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  944): Killing 5056:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5056
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
D/Jerry   ( 1525): URI_DRAFT
,D/DraftCache( 5425): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5425): [DraftCache/121] rebuildCache time: 13
,D/MmsAsyncWorkHandler( 5425): 
D/MmsAsyncWorkHandler( 5425): HM tk = 20002
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1525): sku_id=118
,D/MessageCustFlag( 5425): sense_version=6.0,
D/Jerry   ( 5425): start to preload cursor >>>>>>>
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94,
D/MmsSmsV2Provider( 1525):  slotId = -1000
,D/Messaging( 5425): ViewCache CreatePreload,
D/Messaging( 5425): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 5425): _has_set_default_values_2=true
,D/PhoneStorageUtil( 5425): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 5425): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/MsgPreferenceUtils( 5425): def_index: 0,
,I/ActivityManager(  944): Recipient 5056,
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1525): sku_id=118
,D/PhoneStorageUtil( 5425): createReceiver
,D/MsgPreferenceUtils( 5425): globalIndex = 1
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MsgPreferenceUtils( 5425): phone state: true
D/MsgPreferenceUtils( 5425): sd state: false
,D/MsgPreferenceUtils( 5425): vIndex = 0
,W/ResourcesManager( 5620): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TelephUtils( 1525): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,V/MmsProvider( 1525): Update uri=content://mms, match=0
V/MmsProvider( 1525): selection=st=129 AND m_type!=134
D/Messaging( 5425): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5425): TransactionService is going to be woken up.
,V/TransactionService( 5425): 1-Creating TransactionService
,V/TransactionService( 5425): onStartCommand: 1,
D/MmsSystemEventReceiver( 5425): unRegisterForConnectionStateChanges
V/TransactionService( 5425): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
V/TransactionService( 5425): Loading previous transactions.
,D/TelephUtils( 1525): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
,D/AccFlag ( 1525): device_type: 1
E/SQLiteLog( 5575): (283) recovered 1464 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/TransactionService( 5425): Force clearing mTransactionList
,D/TransactionService( 5425): Force set service start id to 1
,V/TransactionService( 5425): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5425): unRegisterForConnectionStateChanges
,D/TransactionService( 5425): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5425): Destroying TransactionService,
,V/TransactionService( 5425): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/Gmail   ( 5575): notifyAccountChanged
,I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5575): getAccountsCursor
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel_SMS( 5620): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5620): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 5425): query uri: content://htc-mms-customization/mms-ua/ua_string,
,D/MmsCustomizationProvider( 5425): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Gmail   ( 5575): master sync=false, engine sync=true
,I/Babel_SMS( 5620): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 5620): MmsConfig.loadFromDatabase
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5620, uid=10112, userID:0,
,E/Babel_SMS( 5620): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5620): MmsConfig.loadFromResources
,E/Babel_SMS( 5620): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5620): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Gmail   ( 5575): getAccountsCursor
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5575): master sync=false, engine sync=true
,W/Settings( 5620): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5620): startup - clean,
,I/Babel   ( 5620): deleted: false for 0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5620, uid=10112, userID:0
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5620, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5620, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5620, uid=10112, userID:0,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5620, uid=10112, userID:0
,D/PMS     (  944): acquireWL(c443e4a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5620 10112 null,
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
,E/MDM     ( 1782): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4251): Restart initialization of location
,W/VideoCapabilities( 5620): Unsupported mime video/x-ms-wmv
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,W/Utils   ( 5620): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5620): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5620): Unsupported mime audio/x-ms-wma
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/AudioCapabilities( 5620): Unsupported mime audio/qcelp
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
W/VideoCapabilities( 5620): Unsupported mime video/x-ms-wmv
I/NotifUtils( 5575): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
I/DFPI.ApkInstallService( 5406): onHandleIntent
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage,
,I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5406): onHandleIntent
,I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  944): Resuming delayed broadcast,
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  944): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5406): onHandleIntent,
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5406): check CID = HTC__102
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  944): Resuming delayed broadcast
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5477): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  944): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5693 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/VideoCapabilities( 5620): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 5693): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,D/CalendarApplication( 5693): onCreate
,I/art     (  944): Explicit concurrent mark sweep GC freed 9623(451KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.441ms total 136.719ms
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/NotifUtils( 5575): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/ProviderChangeReceiver( 5693): ---------------------------------------------------
D/ProviderChangeReceiver( 5693): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/HtcAlertService( 5693): start to updateAlertNotification!
I/vclib   ( 5620): onServiceConnected
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/Babel   ( 5620): Attempted to change video mute state without an active call.
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/HtcAlertService( 5693): No fired or scheduled alerts
,D/HtcAlertUtils( 5693): -- cancelReminderNotification --
,D/HtcAlertUtils( 5693): broadcastExistReminder!
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0
E/MDM     ( 1782): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ResourcesManager( 5620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LocationInitializer( 4251): Restart initialization of location
,I/art     ( 5477): Explicit concurrent mark sweep GC freed 15850(945KB) AllocSpace objects, 2(40KB) LOS objects, 86% free, 306KB/2MB, paused 295us total 28.636ms
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5477): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5477): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5477): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5477): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5477): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5477): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5477): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/MediaStoreImporter( 5297): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  944): killProcessQuiet, pid=5097,
I/ActivityManager(  944): Killing 5097:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/JNIHelp ( 5620): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5620): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ActivityManager(  944): Recipient 5097
I/ProviderInstaller( 5620): Installed default security provider GmsCore_OpenSSL
,I/[PluginManager]RegisterService( 1499): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1499): handle notify Blinkfeed plugin client changed
,E/PhoneInterfaceManager( 1525): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  944): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5727 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 5620): connection state changed from UNKNOWN to DISCONNECTED
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5620): Unrecognized profile 2130706433 for video/avc,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5727): -onCreate(),
,D/PMS     (  944): releaseWL(c443e4a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,V/Settings:HtcSettingsApplication( 5727): [5727/5727] onCreate(),
,I/ActivityManager(  944): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5753 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=5132,
I/ActivityManager(  944): Killing 5132:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 5727): id/is att sku: 118/false
,E/Settings:HtcWrapHeaderInfo( 5727): no such activity!,
,I/HtcModeClient( 3160): handler message = 4011
E/HtcModeClient( 3160): Check connection and retry 6 times.
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5727): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5727): updateDevelopment, bPrefShow = true,
,I/ActivityManager(  944): Recipient 5132,
,E/Settings:HtcUmcWidgetEnabler( 5727): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5727): Failed to find provider info for com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5727): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5727): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5727): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5727): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5727): [supportHomeButton]support         :false
,I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 5727): isSupportVoWifi: null
E/ActivityThread( 5727): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5753, uid=10072, userID:0,
,W/global  ( 5753): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5753): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5753): [apache-http] Connection GC has been deprecated!
,W/global  ( 5753): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5753): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  944): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5792 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5753): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
W/Settings( 5753): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5753, uid=10072, userID:0,
,W/ResourcesManager( 5792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 5753): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5753): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5753): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,I/MultiDex( 5792): VM with version 2.1.0 has multidex support
,I/MultiDex( 5792): install
I/MultiDex( 5792): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 5753): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 4251): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  944): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5820 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/PackageBroadcastService( 4251): Null package name or gms related package.  Ignoreing.
,D/Process (  944): killProcessQuiet, pid=5187
I/ActivityManager(  944): Killing 5187:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5187
,D/PMS     (  944): acquireWL(2acfb676): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4251): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 5792): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 5820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  944): releaseWL(2acfb676): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/ActivityThread( 5792): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5792): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@402c680: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5792): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  944): acquireWL(c91af50): PARTIAL_WAKE_LOCK  AsyncService 0x1 5820 10167 null,
,D/PMS     (  944): releaseWL(c91af50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  944): acquireWL(2fb31e4e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5820 10167 null
,I/UpdateIcingCorporaServi( 5164): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=5855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/art     ( 1917): Explicit concurrent mark sweep GC freed 11145(559KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 810us total 36.578ms
,D/PMS     (  944): releaseWL(2fb31e4e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/Process (  944): killProcessQuiet, pid=5216,
I/ActivityManager(  944): Killing 5216:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/UpdateIcingCorporaServi( 5164): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] ,
,I/ActivityManager(  944): Recipient 5216,
,I/ActivityManager(  944): Killing 4798:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=4798
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 4798,
,V/AlarmManager(  944): sending alarm PendingIntent{1bac1868: PendingIntentRecord{110cc375 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094162979, Int=0
W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,V/Finsky  ( 5753): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,D/Finsky  ( 5753): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/TetherSettings( 5727): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5727): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5727): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5727): Cust_ConnectToPC   : spcsc>false
D/        ( 5727): Cust_ConnectToPC   : IPT>true
D/        ( 5727): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5727): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false,
D/SmartNS_NSReceiver( 5727): Index of the first 1 = -1,
,W/ContextImpl( 5727): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5727): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Settings( 5727): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5727): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5727): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5727): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/art     (  944): Explicit concurrent mark sweep GC freed 10188(525KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.407ms total 154.595ms,
,D/SmartNS_Utility( 5727): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5727): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WSP     ( 1499): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1499): Weather sync is On
,I/ActivityManager(  944): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5886 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/WSP     ( 1499): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 14:22:43 CET 2016
,W/WSP     ( 1499): [Receiver] can't get active network info
,W/Finsky  ( 5753): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/WSP     ( 1499): [SyncService] no data connection, stop sync service
,W/ResourcesManager( 5886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  944): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5908 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Task_Calendar( 5886): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,D/TodoTaskshortcut( 5886): update TASK shortcut>
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncApplication( 5908): Loading default preferences
,W/Finsky  ( 5753): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Resources( 5908): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  944): New client listening to asynchronous messages
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7
,D/SyncApplication( 5908): Overriding preferences with custom values
,D/SyncApplication( 5908): Updating preferences succeeded
,E/SyncApplication( 5908): Application created.
,I/CalendarDefines( 5908): getNewCalendarAuthority()...,
,W/VolumeInfo( 5908): Unable to read mount points
W/VolumeInfo( 5908): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5908): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5908): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5908): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5908): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5908): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5908): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5908): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5908): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5908): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5908): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5908): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5908): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5908): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5908): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5908): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5908): 	... 13 more
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5908, uid=10005, userID:0
V/VolumeInfo( 5908): Found 0 mount point(s)
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 5908): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5908, uid=10005, userID:0
D/SyncApplication( 5908): enableAppOperation()+
W/PackageManager(  944): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/VolumeInfo( 5908): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/ActivityManager(  944): Waited long enough for: ServiceRecord{1952c9af u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,D/SyncApplication( 5908): enableAppOperation()-
,D/HTCUtilities( 5908): isNeorSinged() + 
,D/VolumeInfo( 5908): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5908): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 5908): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5908): isNeorSinged() return false
,E/AndroidHttpClient( 5753): Leak found
E/AndroidHttpClient( 5753): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5753): 	,at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5753): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5753): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5753): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5753): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5753): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5753): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5753): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5753): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5753): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5753): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5753): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/CDMountReceiver( 5908): whether to enable CD Auto-mount: true
D/CDMountReceiver( 5908): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 5908): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true,
D/CDMountReceiver( 5908): enable CD Auto-mount: true
,D/PMS     (  944): releaseWL(1b0c04ca): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
D/ProviderChangeReceiver( 5693): ---------------------------------------------------
D/ProviderChangeReceiver( 5693): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
D/HTCUtilities( 5908): enable auto-mount
,D/HtcAlertService( 5693): start to updateAlertNotification!
,D/HTCUtilities( 5908): enable auto-mount
,I/HtcMountManagerAdapter( 5908): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5908): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5908): mStorageManager is  not null
,I/HtcMountManagerAdapter( 5908): mStorageManager is  not null
D/VoldConnector(  944): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/VoldConnector(  944): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/MountService(  944): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  944): mountISO: /system/etc/PCTOOL.ISO
,D/HtcAlertService( 5693): No fired or scheduled alerts
D/HtcAlertUtils( 5693): -- cancelReminderNotification --
D/HtcAlertUtils( 5693): broadcastExistReminder!
,I/RemoteViews( 1221): apply : com.nero.android.htc.sync 0 11 4 38
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/GCM     ( 1917): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1917): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/Process (  944): killProcessQuiet, pid=5268,
,I/ActivityManager(  944): Killing 5268:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1221): apply : com.nero.android.htc.sync 1 13 2 53
,I/ActivityManager(  944): Recipient 5268
D/WifiService(  944): Client connection lost with reason: 4
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GmsCoreStatsServiceLauncher( 4251): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4251, uid=10024, userID:0,
,E/MDM     ( 1782): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4251): Restart initialization of location
,I/GLSUser ( 1917): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1917): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1917): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1917): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  944): acquireWL(21342c2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5297 10159 null
,V/GLSActivity( 1917): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5753): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 5753): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5753): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5753): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1782): client connected with version: 7571000
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5297, uid=10159, userID:0
,I/MusicLeanback( 5297): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  944): releaseWL(21342c2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5297): Stop autocaching.
D/Process (  944): killProcessQuiet, pid=5341
I/ActivityManager(  944): Killing 5341:com.htc.task.gtask/u0a66 (adj 15): empty #17,
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5341,
,E/GmsUtils( 5297): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5297): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/Process (  944): killProcessQuiet, pid=5375
I/ActivityManager(  944): Killing 5375:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5375,
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4251, uid=10024, userID:0,
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/CheckinService( 4251): Done disabling old GoogleServicesFramework version
,I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4251, uid=10024, userID:0
,I/GAV2    ( 5575): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 4251): Google Analytics 7.8.99 is starting up.
,D/AutoSetting( 1499): service - handleMessage() stop self
,D/AutoSetting( 1499): service - handleMessage() quit looper,
D/AutoSetting( 1499): service - onDestroy() END
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 7 times.
,I/ActivityManager(  944): Killing 5503:com.htc.updater/u0a84 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5503
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5503,
,D/Process (  944): killProcessQuiet, pid=5551
I/ActivityManager(  944): Killing 5551:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5551
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 8 times.
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{13f3131f u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  944): Waited long enough for: ServiceRecord{2c0acf96 u0 com.htc.musicenhancer/.EnhancerService},
,I/art     (  944): Explicit concurrent mark sweep GC freed 15966(731KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.538ms total 154.664ms
,D/Process (  944): killProcessQuiet, pid=5425
I/ActivityManager(  944): Killing 5425:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5425
,W/MediaManager( 5244): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  944): killProcessQuiet, pid=5406,
I/ActivityManager(  944): Killing 5406:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  944): Recipient 5406,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 3160): handler message = 4011
,E/HtcModeClient( 3160): Check connection and retry 9 times.
,D/PMS     (  944): acquireWL(11581a96): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072}
V/AlarmManager(  944): sending alarm PendingIntent{20a13617: PendingIntentRecord{2fe93a04 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094178531, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{19131bed: PendingIntentRecord{5f34a22 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85847, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{21791cb3: PendingIntentRecord{cc1f270 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=86295, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
,D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
D/PMS     (  944): releaseWL(11581a96): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/Finsky  ( 5753): [582] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5753): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  944): acquireWL(391289e9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{2d15319f: PendingIntentRecord{271ec2ec android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=89551, Int=0
,D/WeatherUtility( 1221): Weather sync is On,
D/PMS     (  944): releaseWL(391289e9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ClockController( 1221): schedule update now=1457094180040 next=59960,
,I/Clock   ( 1221): updateClock:13:23 Europe/Warsaw
,I/Clock   ( 1221): updateClock:13:23 Europe/Warsaw
I/Clock   ( 1221): updateClock:13:23 Europe/Warsaw,
,I/HtcModeClient( 3160): handler message = 4011
,E/HtcModeClient( 3160): Check connection and retry 10 times.
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 11 times.
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  944): acquireWL(3c67fb7a): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(3c67fb7a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(4912c34): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(4912c34): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(28e67fd2): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(28e67fd2): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(a2ed7a0): PARTIAL_WAKE_LOCK  Icing 0x1 4251 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(a2ed7a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3160): handler message = 4011,
E/HtcModeClient( 3160): Check connection and retry 12 times.
,I/HtcModeClient( 3160): handler message = 4011
,E/HtcModeClient( 3160): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 3160): Don't start project servcice
,D/HtcModeClient( 3160): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3160): connectState: CONNECTION_READY = false,
D/SilentMusic( 3160): call stop,
D/HtcModeClient( 3160): close connection
,W/HtcModeClient( 3160): leaveProjectMode: It does not enter ProjectMode,
,W/CANMesgAgentLocalSocket( 3160): read the terminate packet, so break
,D/Process (  944): killProcessQuiet, pid=3160
I/ActivityManager(  944): Killing 3160:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3160
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5969 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  944): acquireWL(164bf59): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10076}
,V/AlarmManager(  944): sending alarm PendingIntent{2208c71e: PendingIntentRecord{99c1bff com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457094198560, Int=60000
D/PMS     (  944): releaseWL(164bf59): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5969): SMSBackupAgentService started
,D/SMSBackup( 5969): Checking restore status
,D/SMSBackup( 5969): Restore complete
D/SMSBackup( 5969): cancelCheckAlarm
,D/PMS     (  944): acquireWL(2318f815): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{276372a: PendingIntentRecord{e320afe com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=102962, Int=0
D/PMS     (  944): acquireWL(25a0791b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1917 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(2318f815): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
D/SMSBackup( 5969): SMSBackupAgentService completed: completed in 0.0 seconds
D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1917): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1917): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1917): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1917): [NET] android_getaddrinfo_proxy+
D/libc    ( 1917): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1917): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  944): Killing 5477:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5477
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
D/PMS     (  944): releaseWL(25a0791b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  944): Recipient 5477
,I/PMS     (  944): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@37c6d9d7
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/PMN     (  944): goingToSleep
W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@37c6d9d7, eanble = 0, strlen(mName) = 91
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@444fc79
W/SensorService(  944): Listener[1] = com.htc.smartdim.sensor_eye@2a6220f4
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1221): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
I/PMS     (  944): Sleeping (uid 1000)...
,D/XAN-DPS (  944): prepareColorFade 1
,W/PMS     (  944): mWirelessDisplayManager is null,
D/PMS     (  944): acquireWL(301bfab8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 944 1000 null
W/PMS     (  944): mWirelessDisplayManager is still null
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  944): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  944): Build Date: 03/09/15 Mon
I/Adreno-EGL(  944): Local Branch: 
I/Adreno-EGL(  944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  944): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  944):                  d74aa161a12b9c6fc6332151
,W/PMN     (  944): goingToSleep done
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,D/PMS     (  944): releaseWL(301bfab8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null,
,D/AlarmManager(  944): ACTION_SCREEN_ON
I/AlarmManager(  944): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done recovering
I/AlarmManager(  944): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done EPS screen off alarm recovering
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5996 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,E/WifiStateMachine(  944): handleMessage: E msg.what=131167,
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  944): handleMessage: E msg.what=155650
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/NetworkPolicy(  944): updateScreenOn: false
D/WifiController(  944): handleMessage: X
,V/NetworkPolicy(  944): updateIfacesLocked()
,D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 5996): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled,
D/WifiStateMachine(  944): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: true
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131127
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  944): handleMessage: X
,E/WifiStateMachine(  944): handleMessage: E msg.what=131129
E/WifiStateMachine(  944): processMsg: InitialState
D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/WifiStateMachine(  944):  InitialState !CMD_CLEAR_BLACKLIST 0 0,
,E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): handleMessage: X
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1221): receive(android.intent.action.SCREEN_ON,1,false)
,D/XAN-DPS (  944): prepareColorFade done
,D/XAN-DPS (  944): setBrightness to 0
,I/CalendarProvider2( 5996): Created com.android.providers.calendar.CalendarAlarmManager@63ff16(com.htc.providers.calendar.HtcCalendarProvider@3508097)
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@444fc79
I/DisplayManagerService(  944): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
V/ActivityManager(  944): Display changed displayId=0
W/SensorService(  944): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1308): [EventService]  onDisplayChanged: 0
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@444fc79, eanble = 0, strlen(mName) = 66
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@2a6220f4
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1308): [EventService] mbHDMIConnect: false, mCoverOn:false
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  944): acquireWL(30e91085): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 5996): wait start:true
D/PMS     (  944): acquireWL(2222beda): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2222beda): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(30e91085): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/AlarmManager(  944): ACTION_SCREEN_OFF,
,I/AlarmManager(  944): [AlarmQueuing] screen off now: ,
I/AlarmManager(  944): [AlarmQueuing] data connection: true
I/AlarmManager(  944): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  944): stopDataStallAlarm 
,E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL false Token 0
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  944): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: InitialState
,E/WifiStateMachine(  944):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  944):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  944): handleMessage: E msg.what=155651
D/WifiController(  944): processMsg: ApStaDisabledState
D/NetworkPolicy(  944): updateScreenOn: false
D/WifiController(  944): processMsg: DefaultState
V/NetworkPolicy(  944): updateIfacesLocked()
D/WifiController(  944): handleMessage: X
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 5996): wait end:false
,I/SensorManager( 1221): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@264887b8, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  944): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  944): pid=1221, uid=10041
,W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@264887b8, eanble = 1, strlen(mName) = 57
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@2a6220f4
W/SensorService(  944): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@264887b8
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/DotMatrix( 1308): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1525): start background delete task...,
,I/IntentController( 1221): receive(android.intent.action.SCREEN_OFF,1,false),
W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5855): MY_DEBUG = false,
D/ContactMessageStore( 1525): size: 0 , 0
,D/ContactMessageStore( 1525): Background delete complete
,D/PMS     (  944): acquireWL(361ed494): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1782 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  944): releaseWL(361ed494): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(2e5dcb3d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1782 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(2e5dcb3d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/SmartSyncUtils( 5855): isEpsOn(), nState = 0
,D/PMS     (  944): acquireWL(a4f32): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5855 1000 null
,D/PMS     (  944): releaseWL(a4f32): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1221): apply : com.htc.updater 0 12 0 36
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
,W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 5855): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5855): isEpsOn(), nState = 0
,W/ContextImpl( 5855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/PowerUsageList:PowerUsageHelper( 5855): PowerProfile::POWER_SCREEN_FULL = 154.8
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2a6220f4,
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2a6220f4, eanble = 0, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@264887b8
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  944): pid=944, uid=1000,
,W/SensorService(  944): Active sensors: size = 2
E/ActivityThread(  944): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@228a901d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@228a901d that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  944): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  944): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  944): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  944): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  944): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  944): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  944): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  944): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  944): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2a6220f4, eanble = 0, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@264887b8
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2a6220f4
,D/PowerUsageList:BatterySipperExt( 5855): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6036 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl(  944): Excessive delay in setPowerMode(): 301ms
D/PMS     (  944): Setting HAL interactive mode to false
D/PowerUsageService( 5855): calcPower(), no data
D/PMS     (  944): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  944): Setting HAL auto-suspend mode to true
D/PMS     (  944): Setting HAL auto-suspend mode done
D/HABCtrl (  944): TPE algorithm. remove timeout.
I/InputMethodManagerService(  944): screenObserver, isScreenOn=false
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
D/PMS     (  944): OOBE c monitor 11
I/InputMethodManagerService(  944): Disable input method client, pid=4439
I/InputManager(  944): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1221): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/NfcService( 1542): ScreenObserver: OFF,
D/NfcService( 1542): applyRouting - 0
,D/PMS     (  944): acquireWL(2be0de39): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1542 1027 null
,D/NfcService( 1542): applyRouting -2
D/NfcService( 1542): applyRouting
D/NfcService( 1542): Ignore this applyRouting...
D/PMS     (  944): acquireWL(b8a2c7e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/PMS     (  944): releaseWL(2be0de39): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(b8a2c7e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/HtcPowerSaver(  944): updateBatteryInfo
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/ClockController( 1221): stop clock update:screen off,
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
D/PowerUsageList:PowerUsageHelper( 5855): MY_DEBUG = false
,D/SmartSyncUtils( 5855): getMobilePolicyEnabled, result = true,
,D/WifiService(  944): New client listening to asynchronous messages,
E/WifiTrafficPoller(  944): ADD_CLIENT: 7
,D/Process (  944): killProcessQuiet, pid=5820,
I/ActivityManager(  944): Killing 5820:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5820,
,D/PMS     (  944): releaseWL(34d04eec): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/CalendarProvider2( 5996): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 5996): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 5693): ---------------------------------------------------
,D/ProviderChangeReceiver( 5693): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,D/HtcAlertService( 5693): start to updateAlertNotification!
,D/Process (  944): killProcessQuiet, pid=5164
I/ActivityManager(  944): Killing 5164:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  944): Recipient 5164
,D/HtcAlertService( 5693): No fired or scheduled alerts
,D/HtcAlertUtils( 5693): -- cancelReminderNotification --
,D/HtcAlertUtils( 5693): broadcastExistReminder!
,D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1221): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1525): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  944): acquireWL(2ad785df): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{1208222c: PendingIntentRecord{1e824f5 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457094215272, Int=0
D/PMS     (  944): acquireWL(1598928a): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
,D/PMS     (  944): releaseWL(2ad785df): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
,D/PMS     (  944): releaseWL(1598928a): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,I/ActivityManager(  944): Killing 5452:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=5452
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5452,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  944): acquireWL(f58a0fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(f58a0fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
,D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: ApStaDisabledState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(6eb3518): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024},
,V/AlarmManager(  944): sending alarm PendingIntent{4e31b71: PendingIntentRecord{31754d56 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143115, Int=0,
D/PMS     (  944): releaseWL(6eb3518): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA,
,D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  944): acquireWL(330651d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{21791cb3: PendingIntentRecord{cc1f270 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=148113, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{2d15319f: PendingIntentRecord{271ec2ec android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149551, Int=0,
V/AlarmManager(  944): sending alarm PendingIntent{9ea8ac4: PendingIntentRecord{6bcfdad android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=166577, Int=0
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
,D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(330651d7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/TelephonyReceiver( 1525): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  454): AtCmdFwd service not published, waiting... retryCnt : 5
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): acquireWL(1490e8e2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  944): n_update end
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): releaseWL(1490e8e2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: ApStaDisabledState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1499): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1cc43e29
I/ActivityManager(  944): Killing 5792:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=5792
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5792
,TIME-OUT KILL (timeout was 150000ms)
```
