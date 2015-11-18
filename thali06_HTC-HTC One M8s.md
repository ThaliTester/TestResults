#### Test 50388019f4ce509_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/Babel_SMS( 4843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 4843): MmsConfig.loadFromDatabase
E/Babel_SMS( 4843): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4843): MmsConfig.loadFromResources
E/Babel_SMS( 4843): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4843): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
--------- beginning of system
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4843, uid=10112, userID:0
W/Settings( 4843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4843): startup - clean
D/PMS     (  964): acquireWL(64346ff): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 964 1000 null
I/Babel   ( 4843): deleted: false for 0
D/PMS     (  964): releaseWL(2b953c0f): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  964): releaseWL(64346ff): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4843, uid=10112, userID:0
E/WifiStateMachine(  964): handleMessage: E msg.what=131155
E/WifiStateMachine(  964): processMsg: ConnectedState
E/WifiStateMachine(  964):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:2946] from screen [on:0 period:430390670] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  964): processMsg: L2ConnectedState
E/WifiStateMachine(  964):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:430390671] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  964):  get link layer stats 0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10112, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4843, uid=10112, userID:0
I/wpa_supplicant( 1350): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  964): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  964): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.29 txretriesrate=0.00 rxrate=1.23 userTriggerdPenalty0
E/WifiStateMachine(  964):  good link -> stuck count =0
E/WifiStateMachine(  964):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  964):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  964): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  964): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/VideoCapabilities( 4843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4843): Unsupported mime video/x-ms-wmv
W/Utils   ( 4843): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 4843): Unsupported mime audio/qcelp
W/AudioCapabilities( 4843): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4843): Unsupported mime audio/qcelp
W/VideoCapabilities( 4843): Unsupported mime video/x-ms-wmv
I/VideoCapabilities( 4843): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4843): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4843): onServiceConnected
W/Babel   ( 4843): Attempted to change video mute state without an active call.
I/ActivityManager(  964): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4884 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  964):  packet count Tx=52 Rx=48
E/WifiTrafficPoller(  964): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils-trace( 4882): Error opening trace file: Permission denied (13)
I/HtcModeClient( 3480): handler message = 4011
E/HtcModeClient( 3480): Check connection and retry 3 times.
D/CustomizationManager( 4882): ====startRecUseTime====
D/htc.customization.log.level( 4882):  is 
W/CustomizationLogLevel( 4882): Level value is invalid, use default level 2
D/CustomizationManager( 4882):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4882): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4882): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4882): Parsing tag category name = system
I/CustomizationCIDLoader( 4882): Parsing tag category name = application
I/CustomizationCIDLoader( 4882): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4882): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4882): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4882): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4882): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4882): add string-array item, value = 42507
I/CustomizationCIDLoader( 4882): add string-array item, value = 21902
I/CustomizationCIDLoader( 4882): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4882): add string-array item, value = 23420
I/CustomizationCIDLoader( 4882): add string-array item, value = 22299
I/CustomizationCIDLoader( 4882): add string-array item, value = 24002
I/CustomizationCIDLoader( 4882): add string-array item, value = 23210
I/CustomizationCIDLoader( 4882): add string-array item, value = 23205
I/CustomizationCIDLoader( 4882): add string-array item, value = 23806
I/CustomizationCIDLoader( 4882): add string-array item, value = 23430
I/CustomizationCIDLoader( 4882): add string-array item, value = 23408
I/CustomizationCIDLoader( 4882): add string-array item, value = 27205
I/CustomizationCIDLoader( 4882): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4882): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4882):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4882):  All configurations done spent 0.097 (s)
W/ResourcesManager( 4884): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4884): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4882 on display 0
W/asset   (  964): Copying FileAsset 0x55ae1850e0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  964): acquireHCC(1d0f541b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 964 1000 null
D/PMS     (  964): acquireHCC(26d3d391): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 964 1000 null
D/PMS     (  964): acquireWL(31c516f7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 964 1000 null
I/FeedHostManager( 1487): [onPause]
I/FeedProviderManager( 1487): onPause
I/FeedHostManager( 1487): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@d2fba01
I/SocialFeedProvider( 1487): +onPause
I/SocialFeedProvider( 1487): -onPause
I/AnimationUtil(  964): isHTCRecent(HelloWorld/Recent screens.)/4
W/HtcSystemUPManager(  964): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
V/JNIHelp ( 4884): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  964): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4927 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/System  ( 4884): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4884): Installed default security provider GmsCore_OpenSSL
E/WifiDataStallTracker(  964): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  964): updateDataStallInfo: mDataStallTxRxSum={txSum=37 rxSum=28} preTxRxSum={txSum=37 rxSum=28}
D/WifiDataStallTracker(  964): updateDataStallInfo: NONE
D/WifiDataStallTracker(  964): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/art     (  964): Explicit concurrent mark sweep GC freed 19764(1053KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 16MB/24MB, paused 2ms total 160.816ms
W/asset   ( 4927): Copying FileAsset 0xac6c3db8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  964): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
I/TrimMemoryManager( 1487): [trimMemory] 20
W/ResourcesManager( 4884): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4884): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 4927): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
E/cutils-trace( 4956): Error opening trace file: Permission denied (13)
I/dex2oat ( 4956): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-641292518.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads-641292518.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4956): dex2oat: override thread count:4
I/LibraryLoader( 4927): Time to load native libraries: 11 ms (timestamps 8563-8574)
I/LibraryLoader( 4927): Expected native library version number "",actual native library version number ""
E/YouTube MDX( 4884): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 4884): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    ( 4884): [NET] android_getaddrinfofornet-, SUCCESS
V/WebViewChromiumFactoryProvider( 4927): Binding Chromium to main looper Looper (main, tid 1) {8beb768}
I/LibraryLoader( 4927): Expected native library version number "",actual native library version number ""
I/chromium( 4927): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/dex2oat ( 4956): dex2oat took 67.611ms (threads: 4)
I/BrowserStartupController( 4927): Initializing chromium process, singleProcess=true
W/art     ( 4927): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4927): ApplicationContext is null in ApplicationStatus
D/VoldConnector(  964): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4884): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/chromium( 4927): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4927): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4927): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4927): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4927): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4927): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4927): Local Branch: 
I/Adreno-EGL( 4927): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4927): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4927):                  d74aa161a12b9c6fc6332151
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  964): java.lang.Throwable: stack dump
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b039c4:true
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4927): 75227668: getState(). Returning 12
D/VoldConnector(  964): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC >>
W/ContextImpl( 4884): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC <<
D/VoldConnector(  964): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4884): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
D/VoldConnector(  964): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4884): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4884): Found 10024
E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  964):  packet count Tx=52 Rx=48
W/art     ( 4927): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4927): onDetachedFromWindow called when already detached. Ignoring
D/VoldConnector(  964): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4884): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/SystemWebViewEngine( 4927): CordovaWebView is running on device made by: HTC
W/art     ( 4927): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4927): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 4927): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 4927): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ActivityManager(  964): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5030 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 4884): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4884): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4884): [NET] android_getaddrinfo_proxy+
D/libc    ( 4884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/art     (  438): Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 215us total 26.851ms
D/Process (  964): killProcessQuiet, pid=4351
I/ActivityManager(  964): Killing 4351:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 128us total 18.267ms
I/InputMethodManager( 4927): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3ba79d2d, mServedView=org.apache.cordova.engine.SystemWebView{360fd262 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@30a29ff3
I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 16.445ms
I/InputMethodManagerService(  964): Disable input method client, pid=1487
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  964): Enable input method client, pid=4927
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
W/XT9_C   ( 1383): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1383): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1383): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1383): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  964): Recipient 4351
W/BindingManager( 4927): Cannot call determinedVisibility() - never saw a connection for the pid: 4927
I/chromium( 4927): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/PMS     (  964): releaseWL(31c516f7): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  964): Displayed com.example.hello/.MainActivity: +1s117ms
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4884): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4884): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 4884): [NET] android_getaddrinfofornet-, SUCCESS
V/AlarmManager(  964): sending alarm PendingIntent{19dd31c0: PendingIntentRecord{22d6def9 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=57713, Int=259200000
V/AlarmManager(  964): sending alarm PendingIntent{2bb1549f: PendingIntentRecord{3443a9ec com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1447834371023, Int=0
D/JsMessageQueue( 4927): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4927): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/libc    ( 4884): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4884): [NET] android_getaddrinfofornet-, err=8
I/iu.UploadsManager( 4744): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
D/jxcore_app_log( 4927): JniHelper::setJavaVM(0xab5568f8), pthread_self() = -1400449704
D/JX-Cordova( 4927): jxcore cordova android initializing
I/iu.UploadsManager( 4744): End new media; added: 0, uploading: 0, time: 55 ms
W/jxcore-log( 4927): Initializing JXcore engine
W/jxcore-log( 4927): JXcore engine is ready
W/jxcore-log( 4927): Starting JXcore engine
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5030): getAccountsCursor
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Atfwd_Sendcmd(  470): AtCmdFwd service not published, waiting... retryCnt : 4
W/GAV2    ( 5030): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5030, uid=10106, userID:0
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  964): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5030): Observing account changes for notifications
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5030, uid=10106, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5030, uid=10106, userID:0
E/Gmail   ( 5030): Error finding the version of the Email provider.....
E/Gmail   ( 5030): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5030): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5030): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5030): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5030): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5030): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5030): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5030): We do not support migrating this version of the Email provider.
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=5030, uid=10106, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=5030, uid=10106, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=5030, uid=10106, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=5030, uid=10106, userID:0
I/Gmail   ( 5030): getAccountsCursor
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 4927): Platform android
W/jxcore-log( 4927): 
W/jxcore-log( 4927): Process ARCH arm
W/jxcore-log( 4927): 
I/ActivityManager(  964): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5081 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5030, uid=10106, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5030, uid=10106, userID:0
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/jxcore-log( 4927): JXcore Cordova bridge is ready!
I/jxcore-log( 4927): 
W/jxcore-log( 4927): JXcore engine is started
E/ActivityThread( 5030): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3ab36be3 that was originally bound here
E/ActivityThread( 5030): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3ab36be3 that was originally bound here
E/ActivityThread( 5030): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 5030): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 5030): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 5030): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5030): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 5030): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 5030): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 5030): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 5030): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 5030): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 5030): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 5030): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5030): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 5030): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  964): Unbind failed: could not find connection for android.os.BinderProxy@2eb1e323
E/SQLiteLog( 5030): (283) recovered 337 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/jxcore-log( 4927): >> HTC-HTC One M8s
E/jxcore-log( 4927): 
I/jxcore-log( 4927): Total memory 1931808768
I/jxcore-log( 4927): 
I/jxcore-log( 4927): Free memory 84996096
I/jxcore-log( 4927): 
I/jxcore-log( 4927): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4927): 
I/jxcore-log( 4927): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4927): 
I/jxcore-log( 4927): userPath [ 'www' ]
I/jxcore-log( 4927): 
I/jxcore-log( 4927): Size 1080 1776
I/jxcore-log( 4927): 
I/jxcore-log( 4927): Screen Brightness 142
I/jxcore-log( 4927): 
E/jxcore-log( 4927): Dummy Error Log.
E/jxcore-log( 4927): 
E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 5
D/WIFI_ICON( 1223): WifiActivity: 3
E/WifiTrafficPoller(  964):  packet count Tx=62 Rx=56
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  964): notifying of data activity 3
I/Gmail   ( 5030): notifyAccountChanged
I/Gmail   ( 5030): getAccountsCursor
I/Gmail   ( 5030): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5030): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  964): acquireWL(2ff28e4c): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5030 10106 null
I/Gmail   ( 5030): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/Gmail   ( 5030): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  964): acquireWL(2ff28e4c): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5030 10106 null
I/Gmail   ( 5030): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5030): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  964): acquireWL(2ff28e4c): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5030 10106 null
I/Gmail   ( 5030): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=5030, uid=10106, userID:0
I/ActivityManager(  964): Killing 4376:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4376
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/AndroidHttpClient( 4681): Leak found
E/AndroidHttpClient( 4681): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4681): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4681): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4681): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4681): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4681): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4681): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4681): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4681): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4681): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4681): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4681): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4681): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4681): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4681): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4681): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4681): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  964): Recipient 4376,
,D/PMS     (  964): releaseHCC(1d0f541b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  964): releaseHCC(26d3d391): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/LocationManagerService(  964): getProviders()=[passive]
,I/ActivityManager(  964): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5113 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
I/Gmail   ( 5030): master sync=false, engine sync=true
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=5081, uid=10085, userID:0,
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=5081, uid=10085, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=5081, uid=10085, userID:0
,I/jxcore-log( 4927): getBuffer is called!!!!
I/jxcore-log( 4927): 
,I/SearchBackgroundTaskFac( 5081): refreshing internal icing corpora
,I/art     (  964): Explicit concurrent mark sweep GC freed 11586(628KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.520ms total 166.283ms,
E/WifiTrafficPoller(  964): ADD_CLIENT: 6
D/WifiService(  964): New client listening to asynchronous messages
I/Gmail   ( 5030): getAccountsCursor
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5030): master sync=false, engine sync=true
,W/BroadcastQueue(  964): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  964): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5156 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/UpdateIcingCorporaServi( 5081): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,D/Process (  964): killProcessQuiet, pid=4410
I/ActivityManager(  964): Killing 4410:com.google.android.configupdater/u0a98 (adj 15): empty #17,
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/WebViewFactory( 5081): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/ActivityManager(  964): Recipient 4410,
,E/WifiStateMachine(  964): handleMessage: E msg.what=131155,
E/WifiStateMachine(  964): processMsg: ConnectedState
E/WifiStateMachine(  964):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:430393694] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  964): processMsg: L2ConnectedState,
E/WifiStateMachine(  964):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:430393695] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  964):  get link layer stats 0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
,I/UpdateIcingCorporaServi( 5081): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] ,
,I/wpa_supplicant( 1350): environment dirty rate=0 [10][0][0]
E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
,E/WifiConfigStore(  964): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  964): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.15 txretriesrate=0.00 rxrate=4.62 userTriggerdPenalty0
E/WifiStateMachine(  964):  good link -> stuck count =0
,E/WifiStateMachine(  964):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  964):  isHighRSSI       ---> score=65
,I/ActivityManager(  964): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5187 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  964): sending alarm PendingIntent{a9c385f: PendingIntentRecord{162b22ac com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60653, Int=0
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  964): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5201 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4,
,D/libc    ( 5156): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5156): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5156): [NET] android_getaddrinfo_proxy+
D/libc    ( 5156): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  964):  packet count Tx=63 Rx=56,
D/WIFI_ICON( 1223): WifiActivity: 2
E/WifiTrafficPoller(  964): notifying of data activity 2
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5156): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
,D/libc    ( 5156): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  964): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5238 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/art     ( 1888): Explicit concurrent mark sweep GC freed 13654(795KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 845us total 49.634ms
,I/LibraryLoader( 5081): Time to load native libraries: 66 ms (timestamps 908-974)
,I/LibraryLoader( 5081): Expected native library version number "",actual native library version number "",
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Search.LoginHelper( 5081): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow,
W/Search.LoginHelper( 5081): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5081): ,	,at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5081): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 5081): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5081): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5081): ,	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5081): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
W/Search.LoginHelper( 5081): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5081): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5081): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5081): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 5156): [NET] android_getaddrinfofornet-, err=8
E/VelvetNetworkClient( 5081): Failed to get auth token
W/art     ( 5081): Attempt to remove local handle scope entry from IRT, ignoring
,D/MdScBoot( 5187): [66f.1.] 30@-081222 -> 40
,D/MdScBootUi( 5187): [66f.1.2.] boot 118
,D/MdScSimSt( 5187): [66f.1.2.] qry 118: 0+1 running 0
,I/MusicStore( 5201): Database version: 120
,W/art     ( 5081): Attempt to remove local handle scope entry from IRT, ignoring,
,D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 21(0x6874632d6e6577),sn(),hints(known),family 0,flags 4
,D/libc    ( 5156): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 21(0x6874632d6e6577),sn(),hints(known),family 0,flags 1024
D/libc    ( 5156): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5156): [NET] android_getaddrinfo_proxy+
D/libc    ( 5156): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 21(0x6874632d6e6577),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/Process (  964): killProcessQuiet, pid=4464
I/ActivityManager(  964): Killing 4464:com.htc.cs.dm/u0a99 (adj 15): empty #17,
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/libc    ( 5081): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
,D/libc    ( 5081): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5081): [NET] android_getaddrinfo_proxy+,
D/libc    ( 5081): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5081): [NET] android_getaddrinfo_proxy-, success,
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5156): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5156): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 5156): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  964): Recipient 4464
,I/ActivityManager(  964): Killing 4489:com.htc.backupreset/1000 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=4489
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4489
,D/Process (  964): killProcessQuiet, pid=4519,
I/ActivityManager(  964): Killing 4519:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4519
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  964):  packet count Tx=118 Rx=116
,D/WIFI_ICON( 1223): WifiActivity: 3
E/WifiTrafficPoller(  964): notifying of data activity 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  964): releaseWL(2ff28e4c): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,D/VoldConnector(  964): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5201): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  964): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5201): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  964): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5201): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5201): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5201): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5201): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5201): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e1b5c0f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5201): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5201): GMSCore installation verified
,I/ConfigStore( 5201): Config Database version: 1,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5201, uid=10159, userID:0,
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,D/MediaRouterService(  964): Client com.google.android.music (pid 5201): Registered,
,D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
,I/MediaRouter( 5201): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 5201): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5201): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 5201): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  964): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5294 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5201, uid=10159, userID:0
,I/GHttpClientFactory( 5201): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5201): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 5294): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  964): Killing 4591:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  964): killProcessQuiet, pid=4591
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  964): Recipient 4591,
,I/CalendarProvider2( 5294): Created com.android.providers.calendar.CalendarAlarmManager@3c3a7a8b(com.htc.providers.calendar.HtcCalendarProvider@8beb768),
,D/CalendarProvider2( 5294): wait start:true,
,D/CalendarProvider2( 5294): wait end:false
,D/AutoSetting( 1576): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5322 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1576): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1576): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1576): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1576): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1576): service - handleMessage() setting current location null
,D/PhoneMonitor( 5322): Register our PhoneStateListener,
,D/Process (  964): killProcessQuiet, pid=3507,
I/ActivityManager(  964): Killing 3507:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  964):  packet count Tx=119 Rx=118
D/MobileConnectivityChangeReceiver( 5322): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5322): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PhoneMonitor( 5322): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5322): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  964): Recipient 3507
,D/Process (  964): killProcessQuiet, pid=4612
I/ActivityManager(  964): Killing 4612:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/HtcModeClient( 3480): handler message = 4011
E/HtcModeClient( 3480): Check connection and retry 4 times.
,I/ActivityManager(  964): Recipient 4612,
,E/WifiDataStallTracker(  964): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  964): updateDataStallInfo: mDataStallTxRxSum={txSum=100 rxSum=93} preTxRxSum={txSum=37 rxSum=28}
D/WifiDataStallTracker(  964): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  964): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/PMS     (  964): acquireWL(1d2ca5a5): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4744 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): acquireWL(33b492b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4744 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  964): releaseWL(1d2ca5a5): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms},
,I/CheckinService( 4744): Checking schedule, now: 1447834375023 next: 1447787714830
I/CheckinService( 4744): active receiver: enabled
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4744, uid=10024, userID:0
,I/CheckinService( 4744): Preparing to send checkin request
,I/EventLogService( 4744): Accumulating logs since 1447833601649
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4744, uid=10024, userID:0
,I/iu.SyncManager( 4744): SYNC; picasa accounts
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkLogImpl( 4744): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4744): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4744): num queued entries: 0,
I/ActivityManager(  964): Waited long enough for: ServiceRecord{f1acb4b u0 com.htc.HTCSpeaker/.NGFService}
,I/iu.UploadsManager( 4744): num updated entries: 0
,I/iu.SyncManager( 4744): NEXT; no task
,I/GcmGroups( 4744): Failed to subscribe to group.
,I/GcmGroups( 4744): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 4744): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 4744): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 4744): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 4744): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 4744): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 4744): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 4744): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 4744): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 4744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 4744): 	at android.os.Looper.loop(Looper.java:155)
I/GcmGroups( 4744): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 4744): Groups upload failed, retrying in 24000:00:00
,D/ChimeraCfgMgr( 4744): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4744): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5358 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 4843): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4843): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4843): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4843): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4843): [NET] android_getaddrinfo_proxy+
D/libc    ( 4843): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4843): [NET] android_getaddrinfo_proxy-, success
,I/DropBoxManagerService(  964): Usage (1282) > Quota (1280),
,I/Babel   ( 4843): connection state changed from UNKNOWN to CONNECTED
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40,
,W/Kids    ( 4744): [AccountUtils] Account not ready
W/Kids    ( 4744): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4744): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4744): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4744): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4744): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4744): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4744): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4744): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4744): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4744): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4744): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4744): 	at java.lang.Thread.run(Thread.java:818)
,I/CheckinRequestBuilder( 4744): Checkin reason type: 8 attempt count: 1
,I/art     ( 4744): Explicit concurrent mark sweep GC freed 23739(1797KB) AllocSpace objects, 19(380KB) LOS objects, 48% free, 4MB/8MB, paused 1.383ms total 66.095ms
D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 7
I/ActivityManager(  964): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4744): Failed to find provider info for com.google.android.wearable.settings
,E/WifiStateMachine(  964): handleMessage: E msg.what=131155
E/WifiStateMachine(  964): processMsg: ConnectedState
,E/WifiStateMachine(  964):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:2934] from screen [on:0 period:430396715] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  964): processMsg: L2ConnectedState
,E/WifiStateMachine(  964):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:430396716] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  964):  get link layer stats 0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1350): environment dirty rate=9 [62][6][0]
,E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  964): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72,
E/WifiConfigStore(  964): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
,I/CalendarProvider2( 5294): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
E/WifiStateMachine(  964): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=33.57 txretriesrate=0.00 rxrate=35.31 userTriggerdPenalty0
W/ContentResolver( 5294): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
E/WifiStateMachine(  964):  good link -> stuck count =0
E/WifiStateMachine(  964):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  964):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  964): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  964): handleMessage: X
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/Process (  964): killProcessQuiet, pid=4637
I/ActivityManager(  964): Killing 4637:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SocialFeedProvider( 1487): +disConnect socialManager
,I/SocialFeedProvider( 1487): disconnect socialManager
,D/VoldConnector(  964): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5358): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  964): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5358): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  964): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5358): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  964): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5358): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5358): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5358):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5358):   adb logcat -s GAv4
,I/art     (  964): Explicit concurrent mark sweep GC freed 16760(882KB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/24MB, paused 1.426ms total 173.843ms
,I/ActivityManager(  964): Recipient 4637
,I/SocialFeedProvider( 1487): -disConnect socialManager,
,W/GAv4    ( 5358): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5358): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5358): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  964):  packet count Tx=124 Rx=122
,W/global  ( 5358): [apache-http] Connection GC has been deprecated!
,W/global  ( 5358): [apache-http] Connection GC has been deprecated!,
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/CheckinRequestBuilder( 4744): awaiting user notification for token
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5402 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 5402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5402): VM with version 2.1.0 has multidex support,
,I/MultiDex( 5402): install
I/MultiDex( 5402): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 5358): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,V/JNIHelp ( 5402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/LibraryLoader( 5358): Time to load native libraries: 1 ms (timestamps 4211-4212),
I/LibraryLoader( 5358): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5358): Binding Chromium to main looper Looper (main, tid 1) {29e0a83c}
,I/LibraryLoader( 5358): Expected native library version number "",actual native library version number "",
,I/chromium( 5358): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5358): Initializing chromium process, singleProcess=true,
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5358): ApplicationContext is null in ApplicationStatus
,W/System  ( 5402): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38ff360d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,W/ActivityThread( 5402): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5402): Installed default security provider GmsCore_OpenSSL
,W/chromium( 5358): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5358): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5358): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5358): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5358): Local Branch: 
I/Adreno-EGL( 5358): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5358): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5358):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 5358): Requires BLUETOOTH permission
,I/NSApplication( 5358): Starting up...
,I/WVCdm   (  400): CdmEngine::OpenSession
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5445 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
,I/ActivityManager(  964): Killing 4660:com.android.smith/1000 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4660
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/art     (  438): Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 185us total 25.654ms
D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  400): Service_Initialize: starts!
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
,I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 136us total 20.484ms,
D/QSEECOMAPI: (  400): Loaded image: APP id = 6
,D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4ab9000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4ab9000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  547): got the req here! ret=0
,D/DrmLibTime(  547): command id, time_cmd_id = 770
D/DrmLibTime(  547): time_getutcsec starts!
D/DrmLibTime(  547): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  547): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  547): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  547): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  547): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  547): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  547): QSEE Time Listener: Retrieved Android system time: 1447834376
D/DrmLibTime(  547): time_getutcsec returns 0, sec = 1447834376; nsec = 0
D/DrmLibTime(  547): time_getutcsec finished! 
D/DrmLibTime(  547): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  547): before calling ioctl to read the next time_cmd
E/QC-time-services(  475): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/art     (  438): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 18.329ms
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
,D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xf4ce2928
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0,
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab370fb0, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2f51c0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab30df80, idLength=0xf4be26f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4be270e, maximum = 0xf4be270f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4be277c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=570198375
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2f87e0
D/DrmWidevineDash(  400): message_length=1611, signature=0xab37db98, signature_length=0xf4be26dc
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  964): Recipient 4660,
,I/GAV2    ( 5030): Thread[GAThread,5,main]: No campaign data found.
,I/GoogleURLConnFactory( 5402): Using platform SSLCertificateSocketFactory,
,I/GAv4-SVC( 4744): Google Analytics 7.8.99 is starting up.
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0,
I/WVCdm   (  400): CdmEngine::CloseSession
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!,
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
,D/libc    ( 5402): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5402): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5402): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5402): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5402): [NET] android_getaddrinfo_proxy+
D/libc    ( 5402): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/art     ( 1888): Explicit concurrent mark sweep GC freed 12255(662KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 690us total 37.889ms
,D/PMS     (  964): acquireWL(14031ef4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 964 1000 null
I/BatteryService(  964): n_update end
D/PMS     (  964): releaseWL(14031ef4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  964): updateBatteryInfo
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/NotificationService(  964): plugged=true pluggin=true
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS,
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/libc    ( 5402): [NET] android_getaddrinfo_proxy-, success
D/PMS     (  964): runPSCheck
D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  964): Checking...
D/UsbnetService(  964): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  964): >> updateStatus
D/UsbnetService(  964):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  964): battery changed pluggedType: 2
D/UsbnetService(  964): BroadcastReceiver::onReceive-
D/WifiController(  964): handleMessage: E msg.what=155652
D/WifiController(  964): processMsg: DeviceActiveState
I/HtcPowerSaver(  964): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  964): processMsg: StaEnabledState
I/HtcPowerSaver(  964): << updateStatus
D/WifiController(  964): processMsg: DefaultState
D/WifiController(  964): handleMessage: X
D/HeadsetStateMachine( 3337): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  964): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2834bcae mBinding = false
W/Settings:Agent(  964): MONITOR_LOG
W/Settings:Agent(  964): name: bluetooth_on
W/Settings:Agent(  964): value: 0
W/Settings:Agent(  964): >> traceCallingStack()
W/Settings:Agent(  964): Process.myPid(): 964
W/Settings:Agent(  964): Process.myTid(): 1161
W/Settings:Agent(  964): Process.myUid(): 1000
W/Settings:Agent(  964): 
W/Settings:Agent(  964): 
W/System.err(  964): java.lang.Throwable: stack dump
,W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  964): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  964): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  964): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  964): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  964): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  964): 
W/Settings:Agent(  964): << traceCallingStack(): 10(ms)
I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  964):  packet count Tx=131 Rx=128
,D/Process (  964): killProcessQuiet, pid=4569
I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5478 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  964): Killing 4569:com.android.settings/1000 (adj 15): empty #17
,D/BluetoothManagerService(  964): Message: MESSAGE_DISABLE
I/DropBoxManagerService(  964): Usage (1281) > Quota (1280)
D/libc    ( 5402): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/PMS     (  964): acquireWL(1d7ab61d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3337 1002 null
D/libc    ( 5402): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  964): New client listening to asynchronous messages
D/BluetoothManagerService(  964): Sending off request.
D/WifiService(  964): setWifiEnabled: false pid=4927, uid=10373
D/libc    ( 5402): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
D/libc    ( 5402): [NET] android_getaddrinfofornet-, err=8
I/WifiService(  964): isSprintWifiRestricted(): false
D/BluetoothAdapterState( 3337): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
I/WifiService(  964): isMdmWifiRestricted(): false
D/BluetoothAdapterProperties( 3337): Setting state to 13
I/BluetoothAdapterState( 3337): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  964): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3337): onBluetoothDisable()
I/bt-btif ( 3337): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 3337): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3337): BTM_SetDiscoverability
I/bt-btm  ( 3337): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3337): disc_mode 0000
I/bt-btm  ( 3337): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3337): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3337): BTM_SetConnectability
I/bt-btm  ( 3337): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3337): disc_mode 0000
I/bt-btm  ( 3337): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  964): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  964): Bluetooth State Change Intent: 12 -> 13
D/WifiManager( 4927): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
E/WifiTrafficPoller(  964): ADD_CLIENT: 8
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
W/Settings:Agent(  964): MONITOR_LOG
W/Settings:Agent(  964): name: wifi_on
W/Settings:Agent(  964): value: 0
W/Settings:Agent(  964): >> traceCallingStack()
W/Settings:Agent(  964): Process.myPid(): 964
W/Settings:Agent(  964): Process.myTid(): 1520
W/Settings:Agent(  964): Process.myUid(): 1000
W/Settings:Agent(  964): 
W/Settings:Agent(  964): 
W/System.err(  964): java.lang.Throwable: stack dump
,W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  964): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  964): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  964): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  964): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  964): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  964): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  964): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  964): 
W/Settings:Agent(  964): << traceCallingStack(): 17(ms)
,D/WifiController(  964): handleMessage: E msg.what=155656
D/WifiController(  964): processMsg: DeviceActiveState
D/WifiController(  964): processMsg: StaEnabledState
D/WifiController(  964): transitionTo: destState=ApStaDisabledState
D/WifiController(  964): handleMessage: new destination call exit/enter
D/WifiController(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  964): invokeExitMethods: DeviceActiveState
D/WifiController(  964): invokeExitMethods: StaEnabledState
D/WifiController(  964): moveTempStackToStateStack: i=0,j=1
D/WifiController(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  964): invokeEnterMethods: ApStaDisabledState
D/WifiController(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131084
E/WifiStateMachine(  964): processMsg: ConnectedState
,E/WifiStateMachine(  964):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  964): processMsg: L2ConnectedState
I/jxcore-log( 4927): ****TEST TOOK:  5144  ms ****,
I/jxcore-log( 4927): 
E/WifiStateMachine(  964):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  964): processMsg: ConnectModeState
E/WifiStateMachine(  964):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  964): processMsg: DriverStartedState
I/jxcore-log( 4927): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4927): 
E/WifiStateMachine(  964):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine(  964): transitionTo: destState=WaitForP2pDisableState
D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  964): invokeExitMethods: ConnectedState
E/WifiStateMachine(  964): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  964): release()
E/WifiStateMachine(  964): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  964): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  964): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  964): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  964): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1350): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1350): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1350): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1350): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1350): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1350): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1350): Power_Mode_Type mode = 0
I/wpa_supplicant( 1350): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  964): setDhcpActive: false
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1888): Read error: ssl=0x55ae024960: I/O error during system call, Connection timed out
E/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  964): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  964): acquireWL(282a9092): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1888 1,0024 WorkSource{10024 com.google.android.gms}
V/NativeCrypto( 1888): SSL shutdown failed: ssl=0x55ae024960: I/O error during system call, Broken pipe
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  964): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  964): [NET] android_getaddrinfofornet-, SUCCESS
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  964): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Validated
D/ConnectivityService(  964): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  964): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  964):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  964):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  964): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524290
I/SecurityController( 1223): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/ActivityManager(  964): Recipient 4569
,D/BluetoothAdapterProperties( 3337): Scan Mode:21
,D/BluetoothAdapterState( 3337): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btif ( 3337): BTA_JvDeleteRecord
I/bt-btif ( 3337): BTA_JvRfcommStopServer
D/bt-btm  ( 3337): BTM_FreeSCN 
E/bt-btif ( 3337): cmd socket is not created
V/BluetoothSapService( 3337): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3337): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:14
E/WifiStateMachine(  964): NetworkAgent != null
D/NGFService( 4052): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/bt-btm  ( 3337): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3337): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3337): BTM_SEC_CLR[15]: id 57
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3337): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3337): BTM_SEC_CLR[17]: id 59
,D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3337): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3337): Write Extended Inquiry Response to controller
I/bt-btm  ( 3337): Write Extended Inquiry Response to controller
I/bt-btm  ( 3337): Write Extended Inquiry Response to controller
I/bt-btm  ( 3337): Write Extended Inquiry Response to controller
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3337): BTM_SetDiscoverability
I/bt-btm  ( 3337): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3337): disc_mode 0000
I/bt-btm  ( 3337): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3337): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3337): BTM_SetConnectability
I/bt-btm  ( 3337): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3337): disc_mode 0000
D/bt-btm  ( 3337): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3337): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3337): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3337): BTM_IsInquiryActive
I/bt-btm  ( 3337): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3337): btm_ble_clear_white_list
W/bt-btif ( 3337): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-btif ( 3337): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3337): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btm  ( 3337): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3337): BTM_FreeSCN 
I/bt-btm  ( 3337): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3337): AVRC_Close handle:0
D/bt-btif ( 3337): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 3337): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3337): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/ConnectivityService(  964): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/bt-l2cap( 3337): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3337): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3337): GATT_Deregister gatt_if=3
I/bt-att  ( 3337): GATT_Listen gatt_if=3
I/bt-btm  ( 3337): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3337): BTM_ReadConnectability
I/bt-btm  ( 3337): btm_ble_set_connectability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 3337): disc_mode 0000
I/bt-att  ( 3337): GATT_Deregister gatt_if=4
I/bt-att  ( 3337): GATT_Listen gatt_if=4
I/bt-btm  ( 3337): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3337): BTM_ReadConnectability
I/bt-btm  ( 3337): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3337): disc_mode 0000
E/bt-btif ( 3337): bta_gattc_deregister Deregister Failedm unknown client cif
,D/PMS     (  964): releaseWL(282a9092): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL true Token 11
,I/bt-btm  ( 3337): btm_ble_clear_white_list_complete
,E/WifiTrafficPoller(  964):  packet count Tx=134 Rx=140
V/NetworkPolicy(  964): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  964): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  964): stopDataStallAlarm 
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  964): ENABLE_DATA_MONITOR_POLL false Token 1
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  964): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  964): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  964): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1350): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1350): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1350): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
,D/wpa_supplicant( 1350): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1350): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1350): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WifiP2pService(  964): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  964): invokeExitMethods: ConnectModeState
,E/WifiStateMachine(  964): invokeExitMethods: DriverStartedState
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
D/WifiP2pService(  964): P2pEnabledState{ when=-8ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
W/ResourcesManager( 5478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  964): noteBatchedScanstop()
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  964): [1,447,834,376,927 ms] noteScanEnd no scan source
E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  964): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131212
E/WifiStateMachine(  964): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  964):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
D/WifiScanningService(  964): SCAN_AVAILABLE : 1
E/WifiStateMachine(  964):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/RttService(  964): SCAN_AVAILABLE : 1
D/WifiScanningService(  964): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/WifiMonitor(  964): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3867087b
D/RttService(  964): EnabledState got{ when=-7ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  964): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  964): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131212
E/WifiStateMachine(  964): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  964):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  964): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  964): handleMessage: X
E/WifiStateMachine(  964): handleMessage: E msg.what=131212
E/WifiStateMachine(  964): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  96,4):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: SupplicantStartedState
E/WifiStateMachine(  964):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  964): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  964): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  964): handleMessage: X
D/WifiNetworkAgent(  964): NetworkAgent: NetworkAgent channel lost
V/BluetoothPbapReceiver( 3337): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3337): ***********state = 13
I/QuickSettingWifi( 1223): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/ActivityManager(  964): Start proc com.android.settings for service com.android.settings/.wifi.WISPrService: pid=5508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/WifiP2pService(  964): P2pDisablingState
D/WifiP2pService(  964): P2pDisablingState{ when=-29ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): p2p socket connection lost
E/WifiStateMachine(  964): handleMessage: E msg.what=131205
D/WifiP2pService(  964): P2pDisabledState
E/WifiStateMachine(  964): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  964):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  964): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiP2pService(  964): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  964): invokeExitMethods: WaitForP2pDisableState
D/WifiP2pService(  964): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  964): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  964): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  964): Call handleNetworkDisconnect() in SupplicantStoppingState
I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  964): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  964): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  964): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  964): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1223): CM callback handler got msg 524292
I/SecurityController( 1223): onLost 100
D/ConnectivityService(  964): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  964): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  964): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  964):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  964): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  964): Removing idletimer
I/ActivityManager(  964): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5522 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  964): sending alarm PendingIntent{35183a63: PendingIntentRecord{8ad3660 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1447834376940, Int=0
I/BtOppRfcommListener( 3337): stopping Accept Thread
I/BtOppRfcommListener( 3337): BluetoothSocket listen thread finished
D/WifiDisplayController(  964): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
E/WifiStateMachine(  964): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
D/WifiDisplayAdapter(  964): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  964):     Client/Owner: Client
D/WifiDisplayAdapter(  964):     GroupId: 
D/WifiDisplayAdapter(  964):     Passphrase: 
D/WifiDisplayAdapter(  964):     SessionId: 0
D/WifiDisplayAdapter(  964):     IP Address: }
E/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1350): Power_Mode_Type mode = 0
I/wpa_supplicant( 1350): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  964): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  964): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
V/AudioService(  964): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  964):     Client/Owner: Client
V/AudioService(  964):     GroupId: 
V/AudioService(  964):     Passphrase: 
V/AudioService(  964):     SessionId: 0
V/AudioService(  964):     IP Address: }
D/HtcEffectManagerBase(  964): onEventChanged id=5 status=false
D/HtcEffectManager(  964): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  964): convertEffect before=902,
D/HtcEffectManager(  964): convertEffect after=902
V/BluetoothPbapService( 3337): Pbap Service closeService in
D/WifiDataStallTracker(  964): setDhcpActive: false
V/BluetoothPbapService( 3337): successfully stopped pbap service
V/BluetoothPbapService( 3337): Pbap Service closeService out
E/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  964): stopping supplicant
W/WifiHW  (  964): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1350): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1350): wlan0: Removing interface wlan0
E/WifiStateMachine(  964): setWifiState: disabling
D/wpa_supplicant( 1350): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1350): TDLS: Tear down peers
D/wpa_supplicant( 1350): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 14
V/BluetoothPbapService( 3337): Pbap Service onDestroy
V/BluetoothPbapService( 3337): Pbap Service closeService in
V/BluetoothPbapService( 3337): Pbap Service closeService out
E/WifiStateMachine(  964): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WIFI    (  964): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI    (  964):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  964): acquireWL(26919719): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 964 1000 null
I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
D/CSLegacyTypeTracker(  964): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WIFI    (  964): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/WIFI_ICON( 1223): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiStateMachine(  964): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  964): handleMessage: E msg.what=196614
D/ConnectivityService(  964): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/ConnectivityService(  964): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  964):  SupplicantStoppingState !CMD_ON_QUIT 0 0
V/NetworkPolicy(  964): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  964): processMsg: DefaultState
D/PMS     (  964): acquireWL(3e5d23de): PARTIAL_WAKE_LOCK  NetworkStats 0x1 964 1000 null
E/WifiStateMachine(  964):  DefaultState !CMD_ON_QUIT 0 0
E/ConnectivityService(  964): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  964): handleMessage: X
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/IntentController( 1223): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/Tethering(  964): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  964): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1223): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  964): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
V/NetworkPolicy(  964): updateIfacesLocked()
V/NetworkPolicy(  964): updateNotificationsLocked()
D/DATA_ICON( 1223): dataConnected: false/false
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkManagementService(  964): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/PMS     (  964): releaseWL(3e5d23de): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
V/NetworkPolicy(  964): updateNotificationsLocked()
D/wpa_supplicant( 1350): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1350): wlan0: Deauthentication notification
D/wpa_supplicant( 1350): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1350): Deauthentication frame IE(s) - hexdump(len=0): [NULL],
I/wpa_supplicant( 1350): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1350): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1350): enter disconnect check
I/wpa_supplicant( 1350): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  964): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  964): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  964): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  964): handleMessage: E msg.what=147460
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1350): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1350): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiStateMachine(  964):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65323
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65324
E/WifiStateMachine(  964): handleMessage: X
D/Tethering(  964): interfaceLinkStateChanged wlan0, false
D/Tethering(  964): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  964): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  964): interfaceLinkStateChanged wlan0, false
D/Tethering(  964): interfaceStatusChanged wlan0, false
V/Tethering(  964): TetherInterfaceSM: wlan0: exit InitialState
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  964): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  964): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbnetService(  964): BroadcastReceiver::onReceive+
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
E/WifiStateMachine(  964): handleMessage: E msg.what=131101
D/PMS     (  964): acquireWL(2a939fea): PARTIAL_WAKE_LOCK  NetworkStats 0x1 964 1000 null
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/UsbDeviceManager(  964): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  964): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  964): BroadcastReceiver::onReceive-
E/WifiStateMachine(  964):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  964): processMsg: DefaultState
,E/WifiStateMachine(  964):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
,D/WifiStateMachine(  964): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  964): releaseWL(2a939fea): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiStateMachine(  964): Default got CMD_TETHER_STATE_CHANGE
V/NetworkPolicy(  964): updateNetworkEnabledLocked()
E/WifiStateMachine(  964): handleMessage: X
V/NetworkPolicy(  964): updateNotificationsLocked()
D/wpa_supplicant( 1350): TDLS: Remove peers on disassociation
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/wpa_supplicant( 1350): wlan0: Disconnect event - remove keys
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5569d0ef88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1350):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1350): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1350): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1350): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1350): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1350): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1350): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  964): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  964): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  964): handleMessage: E msg.what=147462
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
E/WifiStateMachine(  964):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=65335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  964): processMsg: DefaultState
E/WifiStateMachine(  964):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=65336  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  964): handleMessage: X
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5508): -onCreate()
E/cutils-trace( 5527): Error opening trace file: Permission denied (13)
I/dex2oat ( 5527): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5527): dex2oat: override thread count:4
I/QuickSett,ingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1223): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/bt-btm  ( 3337): BTM_BleGetVendorCapabilities
D/MdScPhnSt( 5187): [95f.2.]  listen tmrbb8
W/bt-btif ( 3337): ag scb idx 1 not allocated
,W/bt-btif ( 3337): ag scb idx 2 not allocated
E/bt-btif ( 3337): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3337): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3337): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3337): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3337): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3337): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 3337): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
W/bt-l2cap( 3337): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3337): bta_gattc_deregister Deregister Failedm unknown client cif
V/Settings:HtcSettingsApplication( 5508): [5508/5508] onCreate()
E/bt_userial_mct( 3337): pthread_join() FAILED result:3
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default,
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WISPrService( 5508): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiService(  964): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/WifiService(  964): New client listening to asynchronous messages
E/WifiTrafficPoller(  964): ADD_CLIENT: 9
,D/MdProvGlob( 5238): remove item 101 (p2d19in111) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 5187): [95f.2.] summary 118:p2 ignore
,D/MdProvGlob( 5238): remove item 101 (p2in8) for 15:android.intent.action.ANY_DATA_STATE
,D/PMS     (  964): acquireWL(3203d0b6): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5508 1000 null
,D/MdProvGlob( 5238): remove item 101 (p2d3in15) for 15:android.intent.action.ANY_DATA_STATE
,W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,E/WifiStateMachine(  964): handleMessage: E msg.what=131131
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
D/PMS     (  964): releaseWL(1d7ab61d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiStateMachine(  964):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  964): processMsg: DefaultState
D/MdProvGlob( 5238): remove item 101 (p2d1in14) for 15:android.intent.action.ANY_DATA_STATE
,E/WifiStateMachine(  964):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  964): handleMessage: X
D/WISPrService( 5508): >>>>>WISPrService start isConnected = false<<<<<,
D/WISPrService( 5508): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/ImageRamCache( 5522): create image Cache, size: 31457280.
I/ImageRamCache( 5522): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5522): create image Cache, size: 31457280.
,D/PMS     (  964): releaseWL(3203d0b6): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  964): acquireWL(22262d24): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5508 1000 null
,I/dex2oat ( 5527): dex2oat took 157.534ms (threads: 4)
I/ActivityManager(  964): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5568 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/WISPrService( 5508): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5508): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/System.err(  964): java.lang.Throwable: stack dump
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
D/MdProvGlob( 5238): remove item 101 (p2in24) for 15:android.intent.action.ANY_DATA_STATE
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25744242:true
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
D/WISPrService( 5508): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5508): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/FeedSettings( 5522): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5522): GroupBudget 0.500000 0.380000
I/FeedSettings( 5522): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5522): changeLocale(): en_GB
,D/BluetoothAdapter( 5508): 693360818: getState(). Returning 13
,I/Adreno-EGL( 5402): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5402): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5402): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5402): Local Branch: 
I/Adreno-EGL( 5402): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5402): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5402):                  d74aa161a12b9c6fc6332151
,D/BluetoothInputDevice( 5508): BluetoothInputDevice(),
D/BluetoothManagerService(  964): registerStateChangeCallback+
,D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  964): Registered receivers: 9
,I/Prism.AllAppsOptionsMa_( 5522): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5522): loadGridSize() with Alternative
,D/HtcBtWidget_BTWidgetProvider( 5568): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5568): updateWidget(context) for widget: 
,D/BluetoothPan( 5508): BluetoothPan()
,D/BluetoothManagerService(  964): registerStateChangeCallback+
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  964): Registered receivers: 10
,D/BluetoothMap( 5508): Create BluetoothMap proxy object
D/BluetoothManagerService(  964): registerStateChangeCallback+,
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  964): Registered receivers: 11
E/BluetoothMap( 5508): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  964): registerStateChangeCallback+
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  964): Registered receivers: 12
D/BluetoothSap( 5508): BluetoothSap() call bindService
,D/BluetoothFtpService( 3337): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3337): Shutdown
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothMasReceiver( 3337): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3337): SapReceiver onReceive 
V/BluetoothSapReceiver( 3337): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3337):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3337): startService = false
,D/BluetoothPbap( 5508): BluetoothPbap()
D/BluetoothManagerService(  964): registerStateChangeCallback+,
,E/wpa_supplicant( 1350): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/WifiMonitor(  964): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=28 dispatchEvent: BLACKLIST CLEAR 
D/wpa_supplicant( 1350): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1350): wlan0: Cancelling scan request
D/wpa_supplicant( 1350): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1350): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
D/WifiMonitor(  964): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,D/AuthorizationBluetoothService( 1888): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  964): Registered receivers: 13
D/LocalBluetoothProfileManager( 5508): LocalBluetoothProfileManager construction complete
D/wpa_supplicant( 1350): Remove interface wlan0 from radio phy0
,D/DockEventReceiver( 5508): finishStartingService: stopping service
,D/BluetoothInputDevice( 5508): Proxy object connected
,D/HidProfile( 5508): Bluetooth service connected
,I/SocialManager[SocialBiLogHelper]( 5522): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5522): last commit ulog time 1447739411733
,I/SocialManager[SocialBiLogHelper]( 5522): do commit ulog
,E/cutils-trace( 5502): Error opening trace file: Permission denied (13)
,D/wpa_supplicant( 1350): nl80211: Remove monitor interface: refcount=0,
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,I/bt-btif ( 3337): HAL bt_hal_cbacks->adapter_state_changed_cb,
D/BluetoothAdapterState( 3337): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3337): mProfilesStarted : true supportedProfileServices.length : 6
,D/BluetoothAdapter( 5508): 693360818: getState(). Returning 13
D/wpa_supplicant( 1350): nl80211: Set mode ifindex 29 iftype 2 (STATION)
,D/wpa_supplicant( 1350): nl80211: Unsubscribe mgmt frames handle 0x888888dde1598989 (mode change)
D/BluetoothPan( 5508): BluetoothPAN Proxy object connected
I/wpa_supplicant( 1350): htc_wext_command_deinit +
I/wpa_supplicant( 1350): htc_wext_command_deinit -
I/wpa_supplicant( 1350): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  964): interfaceLinkStateChanged wlan0, false
D/Tethering(  964): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/wpa_supplicant( 1350): Control interface directory not empty - leaving it behind
E/WifiMonitor(  964): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1350): p2p0: Removing interface p2p0
D/wpa_supplicant( 1350): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1350): TDLS: Tear down peers
D/wpa_supplicant( 1350): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
D/PanProfile( 5508): Bluetooth service connected
D/WifiMonitor(  964): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  964): handleMessage: E msg.what=147458
E/WifiStateMachine(  964): processMsg: SupplicantStoppingState
E/WifiStateMachine(  964):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 34 0
E/WifiStateMachine(  964): Supplicant connection lost
,D/HeadsetService( 3337): Received stop request...Stopping profile...
,D/CustomizationManager( 5502): ====startRecUseTime====,
D/htc.customization.log.level( 5502):  is 
W/CustomizationLogLevel( 5502): Level value is invalid, use default level 2
D/SapServerProfile( 5508): Bluetooth service connected
D/PMS     (  964): releaseWL(22262d24): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapterState( 3337): Stopping profile services that were post enabled
I/ActivityManager(  964): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5617 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781
D/HeadsetStateMachine( 3337): Exit Disconnected: -1
,D/BluetoothHeadset(  964): Proxy object disconnected
D/BluetoothHeadset( 4052): Proxy object disconnected
D/NGFService( 4052): BluetoothHeadset onServiceDisconnected: main
D/BluetoothHeadset( 1434): Proxy object disconnected
D/BluetoothHeadset( 1223): Proxy object disconnected
I/QuickSettingMiniLite( 1223): btListener.disconnect:HEADSET
D/A2dpService( 3337): Received stop request...Stopping profile...
D/BluetoothHeadset( 1434): Proxy object disconnected
D/BluetoothHeadset( 1434): Proxy object disconnected
D/A2dpStateMachine( 3337): Exit Disconnected: -1
D/BluetoothPhoneService( 1434): BluetoothHeadset onServiceDisconnected
,I/WVCdm   (  400): CdmEngine::OpenSession
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781,
D/BluetoothA2dp(  964): Proxy object disconnected
D/BluetoothA2dp( 4052): Proxy object disconnected
D/HidService( 3337): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781
D/NGFService( 4052): BluetoothA2dp onServiceDisconnected: main
,D/HealthService( 3337): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781
,D/PanService( 3337): Received stop request...Stopping profile...,
D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781
D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  400): Service_Initialize: starts!
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
,D/BtGatt.DebugUtils( 3337): handleDebugAction() action=null
D/BtGatt.GattService( 3337): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3337): stop()
D/BtGatt.AdvertiseManager( 3337): advertise clients cleared
,D/BluetoothInputDevice( 5508): Proxy object disconnected
,I/ActivityManager(  964): Killing 4718:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/HidProfile( 5508): Bluetooth service disconnected
D/BluetoothAdapterService( 3337): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1785f781
D/BluetoothPan( 5508): BluetoothPAN Proxy object disconnected
D/PanProfile( 5508): Bluetooth service disconnected
D/Process (  964): killProcessQuiet, pid=4718
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/QSEECOMAPI: (  400): Loaded image: APP id = 7
,D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4ab8000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4ab8000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  547): got the req here! ret=0
D/DrmLibTime(  547): command id, time_cmd_id = 770
D/DrmLibTime(  547): time_getutcsec starts!
D/DrmLibTime(  547): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  547): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  547): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  547): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  547): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  547): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  547): QSEE Time Listener: Retrieved Android system time: 1447834377
D/DrmLibTime(  547): time_getutcsec returns 0, sec = 1447834377; nsec = 0
D/DrmLibTime(  547): time_getutcsec finished! 
,D/DrmLibTime(  547): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  547): before calling ioctl to read the next time_cmd
E/QC-time-services(  475): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/CustomizationManager( 5502):  Read ACC file spent 0.047 (s),
,D/CIDMapFileReader( 5502): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__032,
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5502): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 5502): full path : /system/customize/CID/HTC__102.xml,
I/CustomizationCIDLoader( 5502): Parsing tag category name = system
,I/CustomizationCIDLoader( 5502): Parsing tag category name = application
,I/CustomizationCIDLoader( 5502): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 5502): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5502): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5502): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5502): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5502): add string-array item, value = 42507
I/CustomizationCIDLoader( 5502): add string-array item, value = 21902
I/CustomizationCIDLoader( 5502): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5502): add string-array item, value = 23420
I/CustomizationCIDLoader( 5502): add string-array item, value = 22299
I/CustomizationCIDLoader( 5502): add string-array item, value = 24002
I/CustomizationCIDLoader( 5502): add string-array item, value = 23210
I/CustomizationCIDLoader( 5502): add string-array item, value = 23205
I/CustomizationCIDLoader( 5502): add string-array item, value = 23806
I/CustomizationCIDLoader( 5502): add string-array item, value = 23430
I/CustomizationCIDLoader( 5502): add string-array item, value = 23408
I/CustomizationCIDLoader( 5502): add string-array item, value = 27205
I/CustomizationCIDLoader( 5502): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 26006:D:1:0
,I/CustomizationCIDLoader( 5502): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5502): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5502):  Read CID file spent 0.097 (s)
D/CustomizationManager( 5502):  All configurations done spent 0.097 (s)
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xffafc2e8
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab30e700, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3608f0, wrapped_rsa_key_length=1280
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab30dfc0, idLength=0xf4be26f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,V/SocialManagerService( 1576): getDataSources,
W/BluetoothHeadset( 1223): Proxy not attached to service
I/QuickSettingMiniLite( 1223): updateLiteState:no connect device!
I/SocialManagerService( 1576): plugin added: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1576): plugin added: com.google
I/SocialManagerService( 1576): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1576): plugin added: com.htc.club
I/SocialManagerService( 1576): plugin added: com.twitter.android.auth.login
,I/SocialManagerService( 1576): plugin added: com.htc.linkedin
I/SocialManagerService( 1576): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1576): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1576): plugin added: com.facebook.auth.login
I/SocialManagerService( 1576): plugin added: com.htc.drive.activator
I/SocialManagerService( 1576): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1576): device total memory: 1842M
I/SocialManagerService( 1576): groupAccounts
I/ImageRamCache( 5617): create image Cache, size: 31457280.
I/ImageRamCache( 5617): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5617): create image Cache, size: 31457280.
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4be270e, maximum = 0xf4be270f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4be277c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=1000730730
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2f7810
D/DrmWidevineDash(  400): message_length=1645, signature=0xab2f8500, signature_length=0xf4be26dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/FeedSettings( 5617): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5617): GroupBudget 0.500000 0.380000
I/FeedSettings( 5617): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 5617): changeLocale(): en_GB
,I/ActivityManager(  964): Recipient 4718
,I/ActivityManager(  964): Killing 4681:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=4681
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SocialManagerService( 1576): cannot find this plugin service: com.htc.drive.activator,
I/Prism.AllAppsOptionsMa_( 5617): loadSortType() with Custom
D/PackageManager(  964): deletePackageAsUser: pkg=com.example.hello, pid=5502, uid=2000 userid=0
E/SocialManagerService( 1576): error when get process name! process name is null!
E/SocialManagerService( 1576): skip binding the plugin without process namecom.htc.drive.activator
I/Prism.AllAppsOptionsMa_( 5617): loadGridSize() with Alternative
,I/SocialManagerService( 1576): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to pending queue!
I/SocialManagerService( 1576): add com.google to pending queue!
I/SocialManagerService( 1576): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1576): add com.htc.club to pending queue!
I/SocialManagerService( 1576): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1576): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1576): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1576): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1576): add com.htc.sense.socialnetwork.instagram to pending queue!
,I/SocialManagerService( 1576): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to process map!
V/SocialManagerService( 1576): initiating bind to plugin type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1576): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connecting, adding msg, has message?true
E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL false Token 15 num clients 9
,W/PackageSettings(  964): Skipping PackageSetting{2d977362 com.test.thalitest/10366} due to missing metadata,
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  400): CdmEngine::CloseSession,
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4744): Classify the device as Phone.
,I/ActivityManager(  964): Recipient 4681,
,W/BluetoothHeadsetServiceJni( 3337): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3337): Cleaning up Bluetooth Handsfree callback object,
,I/SocialManagerService( 1576): add com.google to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.google
I/SocialManagerService( 1576): com.google connecting, adding msg, has message?true
,W/BluetoothHidServiceJni( 3337): Cleaning up Bluetooth HID Interface...,
W/BluetoothHidServiceJni( 3337): Cleaning up Bluetooth GID callback object
,I/ActivityManager(  964): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/BluetoothHealthServiceJni( 3337): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3337): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3337): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3337): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3337): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3337): Setting state to 10
I/BluetoothAdapterState( 3337): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  964): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  964): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  964): Broadcasting onBluetoothStateChange(false) to 13 receivers.
,I/BluetoothAdapterState( 3337): Entering OffState
D/BluetoothA2dp( 4052): onBluetoothStateChange: up=false
I/ActivityManager(  964): Killing 4927:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  964): killProcessQuiet, pid=4927
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,E/WifiTrafficPoller(  964): TRAFFIC_STATS_POLL false Token 15 num clients 9,
,I/wpa_ctrl(  964): [wpa_ctrl_close] ctrl=0x55ae1a8db0,
I/wpa_ctrl(  964): [wpa_ctrl_close] ctrl=0x55ae1a8ea0
,I/ActivityManager(  964): Recipient 4927,
,D/WifiService(  964): Client connection lost with reason: 4
I/WindowState(  964): WIN DEATH: Window{3f48c742 u0 com.example.hello/com.example.hello.MainActivity}
,E/InputEventReceiver( 1383): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{37f82454 uid 10373 pid 4927} (c)'
,W/ActivityManager(  964): Force removing ActivityRecord{330939b8 u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello,
D/DotMatrix( 1311): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
D/PMS     (  964): acquireWL(2320891c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  964): releaseWL(2320891c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1724): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1434): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1724): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ActivityManager(  964): Spurious death for ProcessRecord{6491925 4927:com.example.hello/u0a373}, curProc for 4927: null
,E/WifiStateMachine(  964): setWifiState: disabled
D/BluetoothA2dp(  964): onBluetoothStateChange: up=false,
I/SocialManagerService( 1576): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connected, removed msg, has message?false
,W/SystemReader(  964): Cannot find grip_rejection_width, use default value instead
I/FeedHostManager( 1487): [onResume]
I/FeedProviderManager( 1487): onResume
I/SocialFeedProvider( 1487): +onResume
I/SocialFeedProvider( 1487): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1487): -onResume
I/ConnectivityHelper( 1487): [getCurrentConnectionType] no network connection
I/Prism.ItemManager( 5522): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5522): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/BlinkFeedPluginService( 2389): Set icon to :2130837679
D/BlinkFeedPluginService( 2389): class com.htc.blinkfeed.provider.DummyIdentityProvider
D/BlinkFeedPluginService( 2389): Not filterable
,D/SocialManagerService( 1576): handling plugin: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin set result in bg
I/SocialManagerService( 1576): remove account type: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin from process map!
I/SocialManagerService( 1576): remove process: pl.k2.droidoaudioteka from process map!
,I/ActivityManager(  964): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.googleplus/com.htc.plugin.googleplus.GooglePlusSocialPluginService: pid=5654 uid=10021 gids={50021, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a,
I/SocialManagerService( 1576): add com.twitter.android.auth.login to process map!
I/ActivityManager(  964): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg,
V/SocialManagerService( 1576): initiating bind to plugin type com.twitter.android.auth.login
I/SocialManagerService( 1576): com.twitter.android.auth.login connecting, adding msg, has message?true
,I/InputMethodManagerService(  964): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/AccTypeManager( 1724): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/WifiStateMachine(  964): Enter handleNetworkDisconnect
,E/WifiStateMachine(  964): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
I/IntentController( 1223): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WIFI_ICON( 1223): updateWifiState: WIFI_STATE_CHANGED disabled
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/PMS     (  964): acquireWL(2c6046aa): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 964 1000 null
E/WifiStateMachine(  964): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/Settings( 1834): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): Exit handleNetworkDisconnect
E/WifiStateMachine(  964): [MLHD] Error! unhandled message 6 { when=-767ms what=147458 arg1=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  964): transitionTo: destState=InitialState
E/WifiStateMachine(  964): handleMessage: new destination call exit/enter
E/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  964): invokeExitMethods: SupplicantStoppingState
,E/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  964): invokeEnterMethods: InitialState
W/Settings( 4843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/SocialManagerService( 1576): on plugin completed! plugin session type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
D/BluetoothHeadset(  964): onBluetoothStateChange: up=false
I/SocialManagerService( 1576): add com.htc.club to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.club
I/SocialManagerService( 1576): com.htc.club connecting, adding msg, has message?true
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
,D/WIFI_ICON( 1223): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1223): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/ExternalAccountType( 1724): Unsupported attribute readOnly
,I/QuickSettingWifi( 1223): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
,I/QuickSettingWifi( 1223): receive.wifiConnect:false wifiAPname:null elapse:0,
,W/PackageManager(  964): Unable to load service info ResolveInfo{1dea7267 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  964): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  964): 	,at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  964): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  964): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  964): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  964): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  964): Explicit concurrent mark sweep GC freed 37909(2MB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.767ms total 226.643ms
,I/art     (  964): WaitForGcToComplete blocked for 123.118ms for cause Explicit
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4744, uid=10024, userID:0
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4744, uid=10024, userID:0,
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4744, uid=10024, userID:0
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4744, uid=10024, userID:0
W/asset   (  964): Copying FileAsset 0x55ae3b0760 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/JobSchedulerService(  964): Receieved: android.intent.action.PACKAGE_REMOVED
,E/WifiTrafficPoller(  964): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/TaskPersister(  964): removeObsoleteFile: deleting file=8_task.xml
,W/SystemReader(  964): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1724): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1724): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/art     (  964): Explicit concurrent mark sweep GC freed 5206(267KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.899ms total 148.028ms
D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
,D/StatusBarManagerService(  964): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  964): hiding MENU key
,I/SocialManagerService( 1576): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1576): com.htc.opensense.htcnews connecting, adding msg, has message?true
,D/AccTypeManager( 1724): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/FindExtension( 1487): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
D/BluetoothInputDevice( 5508): onBluetoothStateChange: up=false
,I/ThreadedRenderer( 1487): Defer allocateBuffers to drawing time
I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/BluetoothPbap( 5508): onBluetoothStateChange: up=false
I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/WISPrService( 5508): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5508): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4927 uid 10373
I/SocialManagerService( 1576): add com.htc.linkedin to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.linkedin
I/SocialManagerService( 1576): com.htc.linkedin connecting, adding msg, has message?true
I/SocialManagerService( 1576): com.htc.club connected, removed msg, has message?false
W/ResourcesManager(  964): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/BluetoothMap( 5508): onBluetoothStateChange: up=false
E/BluetoothMap( 5508): 
E/BluetoothMap( 5508): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@29c2ca98
E/BluetoothMap( 5508): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5508): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5508): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5508): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5508): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5508): 	at android.os.Binder.execTransact(Binder.java:454)
E/ExternalAccountType( 1724): Unsupported attribute readOnly
D/StatusBarManagerService(  964): swetImeWindowStatus vis=0 backDisposition=0
D/BluetoothHeadset( 4052): onBluetoothStateChange: up=false
I/InputMethodManagerService(  964): Enable input method client, pid=1487
,I/SocialManagerService( 1576): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1576): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
,I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1487): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/BluetoothSap( 5508): onBluetoothStateChange on: false
V/BluetoothSapService( 3337): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@38ff360d
,D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!,
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,I/SocialManagerService( 1576): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1576): com.htc.venuesrecommend connecting, adding msg, has message?true
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/BluetoothPan( 5508): onBluetoothStateChange on: false
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
D/BluetoothManagerService(  964): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  964): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1434): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3ef1a147
D/GCM     ( 1888): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/BlinkFeedPluginService( 5156): Set icon to :2130837554
D/BlinkFeedPluginService( 5156): URI:
D/BlinkFeedPluginService( 5156): Not filterable
D/SocialManagerService( 1576): handling plugin: com.htc.club set result in bg
D/BluetoothAdapter( 1434): onBluetoothServiceDown: done
,I/SocialManagerService( 1576): remove account type: com.htc.club from process map!
I/SocialManagerService( 1576): remove process: com.htc.club from process map!
D/BluetoothAdapter( 1223): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@a0b3445
D/BluetoothAdapter( 1223): onBluetoothServiceDown: done
,V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.club
I/ActivityManager(  964): Killing 4210:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/BluetoothAdapter( 1834): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1c2587f8
D/BluetoothAdapter( 1834): onBluetoothServiceDown: done
D/Process (  964): killProcessQuiet, pid=4210
D/BluetoothAdapter(  964): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2834bcae
D/BluetoothAdapter(  964): onBluetoothServiceDown: done
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/BluetoothAdapter( 2389): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@15a5fb13
D/BluetoothAdapter( 2389): onBluetoothServiceDown: done
D/BluetoothAdapter( 4052): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@6d09ed6
D/BluetoothAdapter( 4052): onBluetoothServiceDown: done
D/BluetoothAdapter( 1451): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1f6c5475
D/BluetoothAdapter( 1451): onBluetoothServiceDown: done
D/BluetoothAdapter( 3337): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@17198abd
D/BluetoothAdapter( 3337): onBluetoothServiceDown: done
D/BluetoothAdapter( 5508): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@6d09ed6
D/BluetoothAdapter( 5508): onBluetoothServiceDown: done
D/BluetoothManagerService(  964): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2834bcae mBinding = false
D/BluetoothManagerService(  964): Sending unbind request.
,I/SocialManagerService( 1576): com.htc.opensense.htcnews connected, removed msg, has message?false
W/Prism.AllAppsManager( 1487): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 5617): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5617): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/SocialManagerService( 1576): handling plugin: com.htc.opensense.htcnews set result in bg
,I/SocialManagerService( 1576): remove account type: com.htc.opensense.htcnews from process map!
,I/Prism.ItemManager( 5617): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
I/Prism.ItemManager( 5617): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/PackageManager(  964): Unable to load service info ResolveInfo{33788bef com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  964): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  964): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  964): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  964): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  964): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  964): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  964): hiding MENU key
,I/BackupManagerService(  964): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/ActivityManager(  964): Recipient 4210,
,D/AuthorizationBluetoothService( 1888): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,D/BluetoothManagerService(  964): Bluetooth State Change Intent: 13 -> 10
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false),
V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.opensense.htcnews
,I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
V/GmsCoreStatsServiceLauncher( 4744): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SocialManagerService( 1576): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
I/bt-btif ( 3337): HAL bt_hal_cbacks->thread_evt_cb
D/LocationSocialPlugin( 5522): onBind
D/StreamPluginService( 5522): getDataSources start
D/SocialManagerService( 1576): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
I/SocialManagerService( 1576): com.htc.venuesrecommend connected, removed msg, has message?false
I/SocialManagerService( 1576): remove account type: com.htc.socialnetwork.rss.octopus from process map!
I/ActivityManager(  964): Killing 4884:com.google.android.youtube/u0a176 (adj 15): empty #17
,D/Process (  964): killProcessQuiet, pid=4884
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/LocationIdentityProvider( 5522): is_approved false
D/LocationSocialPlugin( 5522): account null,
D/LocationSocialPlugin( 5522): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
,D/LinkedIn( 5654): contentprovider oncreate getReadableDatabase
,D/Tethering(  964): interfaceRemoved wlan0
,E/Tethering(  964): attempting to remove unknown iface (wlan0), ignoring
,I/ActivityManager(  964): Recipient 4884
,D/Tethering(  964): interfaceLinkStateChanged p2p0, false,
D/Tethering(  964): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  964): WiFiDisplay: getWifidisplayApEnabled=false
,V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
,I/SocialManagerService( 1576): consume pending plugin session,
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1576): handling plugin: com.htc.venuesrecommend set result in bg
I/SocialManagerService( 1576): remove account type: com.htc.venuesrecommend from process map!
I/SocialManagerService( 1576): remove process: com.htc.sense.news from process map!
V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
E/SharedPreferencesImpl( 1834): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml.bak
E/SharedPreferencesImpl( 1834): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml.bak
I/art     ( 3337): System.exit called, status: 0
,D/NfcHandover( 1451): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
I/IntentController( 1223): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 4052): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 4052): Bluetooth Adapter: OFF
D/LocalBluetoothProfileManager( 5508): setBluetoothStateOff
W/BluetoothEventManager( 5508): unregister mProfileBroadcastReceiver fail
V/GmsNetworkLocationProvi( 1834): DISABLE
,I/GCoreNlp( 1834): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/Tethering(  964): interfaceRemoved p2p0
,E/Tethering(  964): attempting to remove unknown iface (p2p0), ignoring
,E/SQLiteLog( 1888): (3850) statement aborts at 36: [INSERT INTO partner(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDBG( 1888): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.google.android.gsf/databases/googlesettings.db, handle: 0x55adf0b480
,D/TetherPref( 5508): persistRestoreBluetoothState false
,D/BluetoothAdapter( 1223): 635304054: getState() :  mService = null. Returning STATE_OFF
E/SQLiteDatabase( 1888): Error inserting ...
E/SQLiteDatabase( 1888): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 1888): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 1888): 	at com.google.android.gsf.settings.GoogleSettingsProvider.insert(GoogleSettingsProvider.java:287)
E/SQLiteDatabase( 1888): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 1888): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:199)
E/SQLiteDatabase( 1888): 	at android.os.Binder.execTransact(Binder.java:454)
I/QuickSettingBluetooth( 1223): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/PMS     (  964): acquireWL(d3f0025): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  964): applying state to connected service
D/PMS     (  964): releaseWL(d3f0025): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  964): applying state to connected service
,D/PMS     (  964): acquireWL(177c85fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  964): acquireWL(1f8479a1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  964): releaseWL(177c85fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  964): releaseWL(1f8479a1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  964): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5699 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4744, uid=10024, userID:0
,W/OpenGLRenderer( 1487): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
I/ActivityManager(  964): Recipient 3337
,I/ActivityManager(  964): Process com.android.bluetooth (pid 3337) has died
,W/ActivityManager(  964): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
W/ActivityManager(  964): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 11000ms
I/BroadcastQueue(  964): Schedule to resend BroadcastRecord{3bfd07c6 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=964 callingUid=1000} for ResolveInfo{2c3ed387 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,I/ActivityManager(  964): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5719 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 96,
D/AccFlag ( 1434): sku_id=118
,W/ResourcesManager( 5699): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5699): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CustomHighlightReceiver( 5522): [custom highlight] onReceive,
D/libc    ( 4744): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4744): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4744): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4744): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4744): [NET] android_getaddrinfo_proxy+
D/libc    ( 4744): [NET] android_getaddrinfo_proxy get netid:0
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1434): sku_id=118
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 4744): [NET] android_getaddrinfo_proxy-, NODATA,
E/CheckinTask( 4744): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/SharedPreferencesImpl( 4744): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
D/CustomHighlightService( 5522): [custom highlight] onHandleIntent
,D/NewsDB  ( 5522): set custom highlight []
,E/SQLiteLog( 5522): (3850) statement aborts at 3: [DELETE FROM tag_custom_highlight] disk I/O error
,E/SQLiteDBG( 5522): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.launcher/databases/news.db, handle: 0x55acc1bcc0
,I/MultiDex( 5699): VM with version 2.1.0 has multidex support
I/MultiDex( 5699): install
I/MultiDex( 5699): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  964): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5748 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/LocationInitializer( 4744): Restart initialization of location,
E/AndroidRuntime( 5522): FATAL EXCEPTION: IntentService[CustomHighlightkService]
E/AndroidRuntime( 5522): Process: com.htc.sense.news, PID: 5522
E/AndroidRuntime( 5522): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5522): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5522): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 5522): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5522): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5522): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 5522): 	at com.htc.lib2.opensense.social.SelectionBuilder.delete(SelectionBuilder.java:235)
E/AndroidRuntime( 5522): 	at com.htc.plugin.news.provider.NewsProvider.delete(NewsProvider.java:487)
E/AndroidRuntime( 5522): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 5522): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 5522): 	at com.htc.plugin.news.provider.NewsDbHelper.clearCustomHighlightTagIds(NewsDbHelper.java:3465)
E/AndroidRuntime( 5522): 	at com.htc.plugin.news.provider.NewsDbHelper.setCustomHighlightTagIds(NewsDbHelper.java:3482)
E/AndroidRuntime( 5522): 	at com.htc.plugin.news.remote.CustomHighlightService.onHandleIntent(CustomHighlightService.java:36)
E/AndroidRuntime( 5522): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5522): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  964):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4744, uid=10024, userID:0
I/CheckinService( 4744): Checking schedule, now: 1447834379183 next: 1447834389159
F/PackageManager(  964): Unable to backup user packages state file, current changes will be lost at reboot
I/CheckinService( 4744): active receiver: disabled
E/ActivityManager(  964): App crashed! Process: com.htc.sense.news
D/ErrorReport(  964): HtcErrorReportManager Begin---add error logs to dropbox
,W/ResourcesManager( 5719): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/PMS     (  964): releaseWL(33b492b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
W/System.err(  964): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
D/GooglePlusSocialPluginService( 5654): Bind
,W/System.err(  964): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
E/DropBoxManagerService(  964): Can't write: system_server_wtf
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop28.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12665)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12469)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12441)
E/DropBoxManagerService(  964): 	at android.os.Handler.handleCallback(Handler.java:739)
E/DropBoxManagerService(  964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService(  964): 	at android.os.Looper.loop(Looper.java:155)
E/DropBoxManagerService(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  964): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/DropBoxManagerService(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 13 more
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
,D/AccFlag ( 1434): sku_id=118
W/System.err(  964): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 14 more
I/SocialManagerService( 1576): com.google connected, removed msg, has message?false
I/SocialManagerService( 1576): com.twitter.android.auth.login connected, removed msg, has message?false
V/JNIHelp ( 5699): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  964): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 12 more
W/System.err(  964): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  964): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  964): 	at com.android.serve,r.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 14 more
I/GooglePlusSocialPluginService( 5654): getDataSources start
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 93
D/AccFlag ( 1434): sku_id=118
,E/ErrorReport(  964): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  964): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1447834379234.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  964): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  964): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  964): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  964): 	... 4 more
,E/SQLiteDatabase( 5654): Failed to open database '/data/data/com.htc.sense.socialnetwork.googleplus/databases/googleplus.db'.,
E/SQLiteDatabase( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteDatabase( 5654): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5654): ,	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5654): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5654): Couldn't open googleplus.db for writing (will try read-only):
E/SQLiteOpenHelper( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at java.lang.Thread.run(Thread.java:818)
W/ActivityManager(  964): Can't addPackageDependency on system process
W/SQLiteOpenHelper( 5654): Opened googleplus.db in read-only mode
,E/SQLiteDatabase( 5654): Failed to open database '/data/data/com.htc.sense.socialnetwork.twitter/databases/htcchirp.db'.
E/SQLiteDatabase( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5654): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteDatabase( 5654): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5654): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5654): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5654): Couldn't open htcchirp.db for writing (will try read-only):
E/SQLiteOpenHelper( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5654): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at android.,content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5654): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 5654): Opened htcchirp.db in read-only mode
D/LinkedIn( 5654): service onBind
I/GooglePlusSocialPluginService( 5654): getDataSources end
D/SocialManagerService( 1576): handling plugin: com.google set result in bg
I/SocialManagerService( 1576): remove account type: com.google from process map!
,W/ActivityThread( 5699): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5699): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38ff360d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5699): Installed default security provider GmsCore_OpenSSL
,D/StatusBarManagerService(  964): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  964): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/SocialManagerService( 1576): on plugin completed! plugin session type com.google
D/StatusBarManagerService(  964): hiding MENU key
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): add com.facebook.auth.login to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.facebook.auth.login
I/SocialManagerService( 1576): com.facebook.auth.login connecting, adding msg, has message?true
D/GooglePlusSocialPluginService( 5654): Unbind
,I/SocialManagerService( 1576): com.htc.linkedin connected, removed msg, has message?false
D/AdapterServiceConfig( 5719): Adding HeadsetService
D/AdapterServiceConfig( 5719): Adding A2dpService
D/AdapterServiceConfig( 5719): Adding HidService
D/AdapterServiceConfig( 5719): Adding HealthService
D/AdapterServiceConfig( 5719): Adding PanService
D/AdapterServiceConfig( 5719): Adding GattService
V/BluetoothPbapReceiver( 5719): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
I/SocialManagerService( 1576): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1576): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1576): remove account type: com.twitter.android.auth.login from process map!
V/BluetoothPbapReceiver( 5719): ***********state = 10
E/BluetoothMasService( 5719): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
V/SocialManagerService( 1576): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1576): consume pending plugin session
I/SocialManagerService( 1576): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1576): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1576): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
D/PMS     (  964): acquireWL(adbe126): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5508 1000 null
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothMasService( 5719): Add permission for SmsProvider.
D/PMS     (  964): releaseWL(adbe126): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/SocialManagerService( 1576): handling plugin: com.htc.linkedin set result in bg
D/PMS     (  964): acquireWL(3647ed03): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5508 1000 null
I/SocialManagerService( 1576): remove account type: com.htc.linkedin from process map!
D/HtcBtWidget_BTWidgetProvider( 5568): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5568): updateWidget(context) for widget: 
W/System.err(  964): java.lang.Throwable: stack dump
D/BluetoothManagerService(  964): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  964): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  964): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dd61ab9:true
W/System.err(  964): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
V/BluetoothMasService( 5719): Starting MAS instances
V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.linkedin
D/BluetoothAdapter( 5719): 851517308: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 5508): finishStartingService: stopping service
I/SocialManagerService( 1576): com.facebook.auth.login connected, removed msg, has message?false
D/PMS     (  964): releaseWL(3647ed03): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/MailMessageReceiver( 5719): reg:com.android.bluetooth.btservice.AdapterApp@9ba6005 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@367a985a
,I/MailManager( 5719): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@367a985a
V/EmailUtils( 5719): Manager Instance is not NULL
D/WearableService( 5699): callingUid 10024, callindPid: 5699
,W/NativeLibraryUtils( 5699): Failed to open lock file
W/NativeLibraryUtils( 5699): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5699): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 5699): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 5699): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 5699): 	,at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 5699): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5699): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5699): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 5699): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 5699): 	... 3 more
,I/ActivityManager(  964): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5779 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/d       ( 5654): get htcisdemo: false,
D/FacebookSocialPluginService( 5654): get htcisdemo: false
D/Facebook_Session( 5654): MSG_QUERY_ACCOUNT
D/Facebook_Session( 5654): queryAccount
D/Facebook_Session( 5654): queryAccount enter lock
,D/Facebook_Session( 5654): Facebook Session created,
D/Facebook_Session( 5654): queryAccount
,E/SQLiteDatabase( 5654): Failed to open database '/data/data/com.htc.sense.socialnetwork.facebook/databases/facebook.db'.
E/SQLiteDatabase( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteDatabase( 5654): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteDatabase( 5654): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteDatabase( 5654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5654): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5654): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 5654): Couldn't open facebook.db for writing (will try read-only):
E/SQLiteOpenHelper( 5654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5654): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5654): 	,at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5654): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteOpenHelper( 5654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5654): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 5654): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 5654): Opened facebook.db in read-only mode
,D/Facebook_Session( 5654): Query Facebook account complete,
I/ActivityManager(  964): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5799 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Facebook_Session( 5654): queryAccount enter lock
I/ActivityManager(  964): Killing 5030:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5030
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Facebook_Session( 5654): Query Facebook account complete
,D/SocialManagerService( 1576): handling plugin: com.facebook.auth.login set result in bg
,I/SocialManagerService( 1576): remove account type: com.facebook.auth.login from process map!
,I/ActivityManager(  964): Recipient 5030,
,I/SocialManagerService( 1576): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false,
V/SocialManagerService( 1576): on plugin completed! plugin session type com.facebook.auth.login
,D/SocialManagerService( 1576): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
,I/SocialManagerService( 1576): remove account type: com.htc.sense.socialnetwork.instagram from process map!
I/SocialManagerService( 1576): remove process: com.htc.sense.socialplugins from process map!
V/SocialManagerService( 1576): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1576): onSessionCompleted
I/ActivityManager(  964): Killing 5113:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  964): killProcessQuiet, pid=5113
D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/MDM     ( 1834): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  964): Recipient 5113
,I/Prism.ItemManager( 5522): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5522): loadItems() com.htc.launcher.pageview.WidgetManager@388ddf29 +
I/Prism.WidgetManager( 5522): onLoadItems() +
,I/SocialManager[SocialBiLogHelper]( 5522): social manager disconnect
D/SMSBackup( 5799): Got a database change event
,D/HtcAdjCursorFactory( 5779): Set CursorWindow size to: 4194304 KB, Tid: 5809
I/HtcModeClient( 3480): handler message = 4011
E/HtcModeClient( 3480): Check connection and retry 5 times.
,E/SQLiteDatabase( 5779): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5779): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5779): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5779): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5779): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5779): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5779): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5779): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteOpenHelper( 5779): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5779): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5779): 	at com.htc.android.mail.kq.a(MailProvider.java:543,3)
E/SQLiteOpenHelper( 5779): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5779): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5779): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5779): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5779): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 5522): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/SQLiteOpenHelper( 5779): Opened mail.db in read-only mode
I/ActivityManager(  964): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5826 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,E/SQLiteDatabase( 5617): Failed to open database '/data/data/com.htc.launcher/databases/BiLogClient'.,
E/SQLiteDatabase( 5617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5617): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/SQLiteDatabase( 5617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5617): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5617): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5617): FATAL EXCEPTION: IntentService[BiLogUploadService]
E/AndroidRuntime( 5617): Process: com.htc.launcher:biclient, PID: 5617
E/AndroidRuntime( 5617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5617): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/AndroidRuntime( 5617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5617): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  964): HtcErrorReportManager Begin---add error logs to dropbox
E/ActivityManager(  964): App crashed! Process: com.htc.launcher:biclient
W/System.err(  964): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  964): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
,W/System.err(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  964): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 12 more
E/SharedPreferencesImpl( 5522): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/com.htc.launcher_preferences.xml to backup file /data/data/com.htc.launcher/shared_prefs/com.htc.launcher_preferences.xml.bak
D/EmailUtils( 5719): ============NULL aList========
V/EmailUtils( 5719): <-getEmailAccountIdList
V/BluetoothMasService( 5719): onCreate: mIsEmailEnabled: true
,W/System.err(  964): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
,W/System.err(  964): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 14 more
,W/System.err(  964): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
I/ActivityManager(  964): Killing 5081:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
W/System.err(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  964): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  964): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
,W/System.err(  964): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  964): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  964): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  964): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  964): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
D/Process (  964): killProcessQuiet, pid=5081
W/System.err(  964): 	at libcore.io.Posix.open(Native Method)
W/System.err(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  964): 	... 14 more
,D/Process (  964): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/HtcWrapAdjustableCursorFactory( 5826): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5826): onCreate,

```
