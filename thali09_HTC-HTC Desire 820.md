#### Test 5024228542a63d7_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  911): sending alarm PendingIntent{421a7168: PendingIntentRecord{421a8ce8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=42892, Int=259200000
V/AlarmManager(  911): sending alarm PendingIntent{41d59088: PendingIntentRecord{4247ced8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49667, Int=0
,--------- beginning of /dev/log/main
D/Process (  911): killProcessQuiet, pid=3212
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  911): killProcessQuiet, pid=3198
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3550 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  911): Killing 3212:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  911): Killing 3198:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
I/ActivityManager(  911): Recipient 3198
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3212
I/SensorManager(  911): mEventCount = 300
D/MessagingNotification( 2785): New incoming message, can't cancel notification now
D/MessagingNotification( 2785): newMsgCnt: 0, false
I/MusicStore( 3550): Database version: 95
W/ContextImpl( 3550): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3550): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3550): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3550, uid=10154, userID:0
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
D/MediaRouterService(  911): Client com.google.android.music (pid 3550): Registered
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
I/MediaRouter( 3550): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (3550/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2377/10021)
I/NetworkMonitor( 3550): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3574 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/cutils-trace( 3562): Error opening trace file: No such file or directory (2)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/MediaRouter( 3550): getSelectedRoute
I/NetworkMonitor( 3550): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3550/10154)
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3550, uid=10154, userID:0
D/Process (  911): killProcessQuiet, pid=3224
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(422c9c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
I/ActivityManager(  911): Killing 3224:com.google.android.youtube/u0a168 (adj 15): empty #17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(422c9c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  911): Recipient 3224
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  911): Client com.google.android.youtube (pid 3224): Died!
D/ACRA    ( 3574): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 3574): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 3574): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/CustomizationManager( 3562): ====startRecUseTime====
D/htc.customization.log.level( 3562):  is 
W/CustomizationLogLevel( 3562): Level value is invalid, use default level 2
W/SystemClassLoaderAdder( 3574): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 3574): Preparing secondary program dexes.
V/DexLibLoader( 3574): Loaded 4 raw lines of metadata.
V/DexLibLoader( 3574): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3574): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3574): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 3574): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3574): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3574): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3574): Dex already copied
D/OdexVerifier( 3574): Odex verification is skipped.
V/DexLibLoader( 3574): Creating class loader
V/DexLibLoader( 3574): Finished creating class loader
V/DexLibLoader( 3574): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3574): Dex already copied
D/OdexVerifier( 3574): Odex verification is skipped.
V/DexLibLoader( 3574): Creating class loader
V/DexLibLoader( 3574): Finished creating class loader
V/DexLibLoader( 3574): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3574): Dex already copied
D/OdexVerifier( 3574): Odex verification is skipped.
V/DexLibLoader( 3574): Creating class loader
V/DexLibLoader( 3574): Finished creating class loader
V/DexLibLoader( 3574): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3574): Dex already copied
D/OdexVerifier( 3574): Odex verification is skipped.
V/DexLibLoader( 3574): Creating class loader
D/CustomizationManager( 3562):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3562): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3562): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3562): Parsing tag category name = system
I/CustomizationCIDLoader( 3562): Parsing tag category name = application
I/CustomizationCIDLoader( 3562): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3562): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3562): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3562): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3562): Parsing tag category name = Settings
D/CustomizationManager( 3562):  Read CID file spent 0.115 (s)
D/CustomizationManager( 3562):  All configurations done spent 0.115 (s)
V/DexLibLoader( 3574): Finished creating class loader
V/DexLibLoader( 3574): Verifying classes from secondary dexes.
W/HtcNativeFlag( 3562): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3562): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3562): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3562): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/asset   (  911): Copying FileAsset 0x67225530 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3562
D/PMS     (  911): acquireHCC(423543f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(425ff1d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1112860640
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
D/DexLibLoader( 3574): DexLibLoader.ensureDexLoaded took 142 ms
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c53ff0
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  911): acquireWL(425e7708): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3596 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/ActivityManager(  911): Waited long enough for: ServiceRecord{42643f80 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 3596): Copying FileAsset 0x5c853428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3596): Binding Chromium to main looper Looper (main, tid 1) {41af0d68}
I/LibraryLoader( 3596): Expected native library version number "",actual native library version number ""
I/chromium( 3596): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3596): Initializing chromium process, renderers=0
D/PMS     (  911): acquireWL(42592a00): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  911): acquireWL(4264c318): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4264c3e0:true
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3596): 1102079840: getState(). Returning 12
D/PMS     (  911): releaseWL(4264c318): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3596): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3596): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3596): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3596): Local Branch: 
I/Adreno-EGL( 3596): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3596): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3596):                  aa63bbd948f41d15fc72f585e
W/chromium( 3596): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3596): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3596): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3596): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3596): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3596): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3596): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3596): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3596): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3596): CordovaWebView is running on device made by: HTC
,D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/AwContents( 3596): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1273
W/ResourceType( 3596): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3596): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b37bd0, mServedView=org.apache.cordova.engine.SystemWebView{41afda80 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3596): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  911): Displayed com.example.hello/.MainActivity: +279ms
I/InputMethodManagerService(  911): Enable input method client, pid=3596
D/PMS     (  911): releaseWL(425e7708): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 3596): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3596): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3596): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3596): JniHelper::setJavaVM(0x415c3048), pthread_self() = 1658248384
D/JX-Cordova( 3596): jxcore cordova android initializing
W/jxcore-log( 3596): Initializing JXcore engine
W/jxcore-log( 3596): JXcore engine is ready
W/jxcore-log( 3596): Starting JXcore engine
W/dalvikvm( 3574): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/jxcore-log( 3596): Platform android
W/jxcore-log( 3596): 
W/jxcore-log( 3596): Process ARCH arm
W/jxcore-log( 3596): 
I/jxcore-log( 3596): JXcore Cordova bridge is ready!
I/jxcore-log( 3596): 
W/jxcore-log( 3596): JXcore engine is started
E/jxcore  ( 3596): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3596): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:267:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
D/WIFI_ICON( 1119): WifiActivity: 1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/dalvikvm( 3574): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3574): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/FbInjectorInitializer( 3574): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
W/fb4a(:<default>):StaticBindingVerifier( 3574): Verify
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (3574/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3574): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3574): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3574): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  911): killProcessQuiet, pid=3276
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3276:com.android.vending/u0a74 (adj 15): empty #17
,D/AutoSetting( 1322): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3649 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1322): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
D/AutoSetting( 1322): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1322): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1322): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1322): service - handleMessage() setting current location null
D/AutoSetting( 1322): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1322): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
,I/ActivityManager(  911): Recipient 3276
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MobileConnectivityChangeReceiver( 3649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3649): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3649): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3649): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  911): killProcessQuiet, pid=3183
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/fb4a(:<default>):UserScope( 3574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3663 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  911): Killing 3183:com.android.settings/1000 (adj 15): empty #17
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (3649/10079)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3574): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (3649/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (3649/10079)
I/ActivityManager(  911): Recipient 3183
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  911): acquireWL(42638d08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426e6af8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2156): Checkin interval check for package: unspecified last checkin: 1452274719723 min interval config: 0 actual interval: 1899455
,D/PMS     (  911): releaseWL(42638d08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):UserScope( 3574): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/CheckinService( 2156): Checking schedule, now: 1452276619188 next: 1452274749692
I/CheckinService( 2156): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2156, uid=10029, userID:0
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/CheckinService( 2156): Preparing to send checkin request
,I/EventLogService( 2156): Accumulating logs since 1452275670118
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  911): releaseHCC(423543f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(425ff1d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/Process (  911): killProcessQuiet, pid=3362
D/WifiNative-wlan0(  911):    returned true
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3681 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  911): Killing 3362:com.htc.sense.browser/u0a12 (adj 15): empty #17
,E/dalvikvm( 3574): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3574): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 3574): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3574): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3574): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3574): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3574): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3574): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3574): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3574): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3574): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3574): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3574): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3574): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3574): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3574): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3574): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3574): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 3574): Grow heap (frag case) to 9.916MB for 39954-byte allocation
,I/CheckinRequestBuilder( 2156): Checkin reason type: 8 attempt count: 1
,W/GAV2    ( 3681): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 3574): Grow heap (frag case) to 9.993MB for 79892-byte allocation
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3362
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3574): Grow heap (frag case) to 10.041MB for 84664-byte allocation
,I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
,D/WifiService(  911): New client listening to asynchronous messages
,E/ActivityThread( 2156): Failed to find provider info for com.google.android.wearable.settings
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 3574): Grow heap (frag case) to 10.279MB for 75760-byte allocation
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (3574/10027)
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426f7d50 u0 ReceiverList{42601d50 3574 com.facebook.katana/10027/u0 remote:42614f98}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426f7d50 u0 ReceiverList{42601d50 3574 com.facebook.katana/10027/u0 remote:42614f98}}
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426e8090 u0 ReceiverList{425fcc30 3574 com.facebook.katana/10027/u0 remote:425f09e8}}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (3681/10151)
,V/WebViewChromiumFactoryProvider( 3681): Binding Chromium to main looper Looper (main, tid 1) {41ae75e8}
,I/LibraryLoader( 3681): Expected native library version number "",actual native library version number ""
,I/chromium( 3681): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3681): Initializing chromium process, renderers=0
,D/PMS     (  911): acquireWL(42755968): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (3574/10027)
,D/PMS     (  911): releaseWL(42755968): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (3574/10027)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/AudioManagerAndroid( 3681): BLUETOOTH permission is missing!
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (3574/10027)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 3681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3681): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3681): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3681): Local Branch: 
I/Adreno-EGL( 3681): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3681): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3681):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2156/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  911): acquireWL(42715e40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,I/NSApplication( 3681): Starting up...
D/PMS     (  911): releaseWL(42715e40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (3681/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (3681/10151)
,I/ActivityManager(  911): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3722 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3403
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3403:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3403
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 1372): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3742 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3722/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3722/10160)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3722/10160)
,D/Process (  911): killProcessQuiet, pid=3415
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3722/10160)
I/ActivityManager(  911): Killing 3415:com.htc.contacts/u0a44 (adj 15): empty #17
D/PMS     (  911): acquireWL(4240f0a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3722 10160 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 3742): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/MultiDex( 3742): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3742): install
,I/MultiDex( 3742): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/PMS     (  911): acquireWL(426784f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3722 10160 null
,D/PMS     (  911): releaseWL(4240f0a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/MultiDex( 3742): loading existing secondary dex files
,I/MultiDex( 3742): load found 3 secondary dex files
,I/MultiDex( 3742): install done
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/iu.SyncManager( 2156): SYNC; picasa accounts
,D/NetworkLogImpl( 2156): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 3742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,W/dalvikvm( 3742): VFY: unable to resolve instance field 36
,I/iu.Environment( 2156): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/dalvikvm( 3742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/iu.UploadsManager( 2156): num queued entries: 0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 2156): num updated entries: 0
I/iu.SyncManager( 2156): NEXT; no task
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,V/JNIHelp ( 3742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
I/ActivityManager(  911): Recipient 3415
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/AlertReceiver( 3458): beginStartingService
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  911): acquireWL(4247a1b8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3458 10013 null
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
,D/PMS     (  911): releaseWL(426784f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PMS     (  911): acquireWL(425ae4e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3507 10071 null
,D/PMS     (  911): acquireWL(42441e98): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3507 10071 null
,D/PMS     (  911): releaseWL(425ae4e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/WeatherUtility( 3478): can't get weather sync account
,I/ActivityManager(  911): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3774 uid=10090 gids={50090, 3003, 5012, 1028}
D/AlertService( 3458): start to updateAlertNotification!
D/TodoTaskshortcut( 3507): update TASK shortcut>
,I/TodoTaskNotifyService( 3507): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ProviderInstaller( 3742): Installed default security provider GmsCore_OpenSSL
,D/AlertService( 3458): No fired or scheduled alerts
,D/HtcAlertUtils( 3458): -- cancelReminderNotification --
,D/HtcAlertUtils( 3458): broadcastExistReminder!
,I/TodoTaskNotifyService( 3507): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,W/WeatherRequest( 1119): request cur loc, but there is no sys cur
,D/PMS     (  911): releaseWL(4247a1b8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/AlertReceiver( 3458): stopSelfResult true
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/NotifyReceiver( 3507): stopSelfResult true
D/PMS     (  911): releaseWL(42441e98): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/dalvikvm( 3742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3742): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 3742): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 3742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,W/WeatherRequest( 3478): request cur loc, but there is no sys cur
,W/Settings( 3478): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WorldClock.Global( 3774): isHtcDevice = true
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/WorldClock.Global( 3774): isHtcDevice = true
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 2 10 17
W/ContextImpl( 3170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3774): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  911): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3790 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 3774): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3774): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1119): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/NativeLibraryUtils( 3742): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,D/TimeService( 3790): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452276620289
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/Process (  911): killProcessQuiet, pid=3430
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  911): Killing 3430:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/PMS     (  911): releaseWL(42592a00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  911): acquireWL(426f70d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426f70d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms},
,I/CheckinService( 2156): Checkin interval check for package: unspecified last checkin: 1452274719723 min interval config: 0 actual interval: 1900644
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,W/dalvikvm( 3742): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3742): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/PMS     (  911): acquireWL(4247f648): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2156 10029 null
W/dalvikvm( 3742): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3742): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/PMS     (  911): acquireWL(426a1df0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
D/WVCdm   (  369): PrepareKeyRequest: nonce=249331886
,I/GoogleURLConnFactory( 3742): Using platform SSLCertificateSocketFactory
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
D/PMS     (  911): releaseWL(4247f648): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  911): releaseWL(426a1df0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Recipient 3430
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3807 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  911): sending alarm PendingIntent{42563b68: PendingIntentRecord{42482898 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53598, Int=0
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/libc    ( 3742): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3742): [NET] getaddrinfo-,err=8
D/libc    ( 3742): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3742): [NET] getaddrinfo-, 1
D/libc    ( 3742): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =6784 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
I/ActivityManager(  911): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3822 uid=10041 gids={50041}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  911): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3837 uid=10091 gids={50091, 3003, 5012}
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 242
D/libc    (  362): [NET]res_nsend:resplen=86
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3742): [NET] getaddrinfo_proxy-, success
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3574): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/SMSBackup( 3446): Got a database change event
,D/Process (  911): killProcessQuiet, pid=3493
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3851 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  911): Killing 3493:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3493
,D/libc    ( 3742): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3742): [NET] getaddrinfo-,err=8
D/libc    ( 3742): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3742): [NET] getaddrinfo-,err=8
,D/MdScBoot( 3807): [df8.1.] 30@-190950 -> 40@-191020
,D/Process (  911): killProcessQuiet, pid=2785
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  911): killProcessQuiet, pid=3522
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2785:com.htc.sense.mms/u0a65 (adj 15): empty #17
I/ActivityManager(  911): Killing 3522:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3522
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3851): create image Cache, size: 31457280.
I/ImageRamCache( 3851): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3851): create image Cache, size: 12582912.
,I/FeedSettings( 3851): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3851): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3851): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3851): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3851): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3851): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3851): [custom highlight] onReceive
,D/CustomHighlightService( 3851): [custom highlight] onHandleIntent
,D/NewsDB  ( 3851): set custom highlight []
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2785
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/LocationInitializer( 2156): Restart initialization of location
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/MDM     ( 1225): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  911): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 5 times.
,D/CustomHighlightService( 3851): [custom highlight] set tags 
,D/Process (  911): killProcessQuiet, pid=3536
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3536:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3536
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=3871 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  911): acquireWL(42675d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42675d48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/MessageFrequencyProvider( 3871): onCreate
,V/GetPrviateResource( 3871): GetPrviateResource
,V/GetPrviateResource( 3871): GetPrviateResource
,D/MessageCustFlag( 3871): sense_version=6.0
,D/BTAccessoryUtil( 3871): createReceiver
,D/BTAccessoryUtil( 3871): registerReceiver return intent = null
D/MessageCustFlag( 3871): sku_id=99
,W/SystemReader( 3871): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3871): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3871): networkCode: 
D/MessageCustFlag( 3871): sku_id=99
D/MmsConfig( 3871): SIE smsPri: null
,D/MmsConfig( 3871): networkCode: 
,D/HtcTelephonyCapability( 3871): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 3871): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3871): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3871): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 3871): packageName: com.htc.vvm.att does not exist
,D/MessagingShortcutReceiver( 3871): keep hiding shortcut bubble
,D/MessagingShortcut( 3871): updateMsgShortcut, msg count> -1
,D/SettingsManager( 3871): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41afbb98
D/MessagingShortcut( 3871): After query: 0
D/MessagingShortcut( 3871): mPresentUnreadCount: -1
,D/MessagingShortcut( 3871): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 3871): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderNotification, total:0
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcBroadcastReceiver( 1246): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/TodoTaskshortcut( 3507): update TASK shortcut>
,I/ActivityManager(  911): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  911): Resuming delayed broadcast
D/MtpReceiver( 2377): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2377): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2377): [MTP][handleMessage][startService]
,D/MtpReceiver( 2377): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2377): [MTP][handleMessage]-
I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3891 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2377): [MTP] startForeground
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1119): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1119): com.android.providers.media 6 2 10
,I/RemoteViews( 1119): com.android.providers.media (false,0)
,D/MtpService( 2377): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2377): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews.Performance( 1119): com.android.providers.media 5 3 15
D/PMS     (  911): acquireWL(42409bd8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3722 10160 null
,D/MtpService( 2377): [isMtpConnected] connected: true
D/PMS     (  911): acquireWL(42366f58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2156 10029 null
,D/MdScBoot( 3807): [1a0.1.] 40@-191020
,D/Process (  911): killProcessQuiet, pid=3550
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3550:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/dalvikvm-heap( 3722): Grow heap (frag case) to 15.216MB for 1821008-byte allocation
,I/ActivityManager(  911): Recipient 3550
,D/MediaRouterService(  911): Client com.google.android.music (pid 3550): Died!
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3891): Loading default preferences
,I/iu.UploadsManager( 2156): End new media; added: 0, uploading: 0, time: 81 ms
,D/PMS     (  911): releaseWL(42366f58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
W/Resources( 3891): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  911): releaseWL(42409bd8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/Process (  911): killProcessQuiet, pid=3574
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3574:com.facebook.katana/u0a27 (adj 15): empty #17
,D/WifiService(  911): New client listening to asynchronous messages
,D/SyncApplication( 3891): Overriding preferences with custom values
,D/SyncApplication( 3891): Updating preferences succeeded
,E/SyncApplication( 3891): Application created.
D/VolumeInfo( 3891): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3891): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3891): Found 0 mount point(s)
,V/VolumeInfo( 3891): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3891): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3891): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3891): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3891): getNewCalendarAuthority()...
,D/SyncApplication( 3891): enableAppOperation()+
,D/SyncApplication( 3891): enableAppOperation()-
,D/HTCUtilities( 3891): isNeorSinged() + 
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3891, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3891, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,I/Adreno-EGL( 3742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3742): Local Branch: 
I/Adreno-EGL( 3742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3742):                  aa63bbd948f41d15fc72f585e
,D/HTCUtilities( 3891): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3891): isNeorSinged() return false
D/CDMountReceiver( 3891): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3891): USB connected to PC
I/ActivityManager(  911): Recipient 3574
D/WifiService(  911): Client connection lost with reason: 4
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/FOTAReceiver( 3891): onReceive() enter 
,D/FOTAReceiver( 3891): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  911): killProcessQuiet, pid=3649
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3916 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  911): Killing 3649:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/Adreno-EGL( 3742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3742): Local Branch: 
I/Adreno-EGL( 3742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3742):                  aa63bbd948f41d15fc72f585e
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
I/ActivityManager(  911): Recipient 3649
,D/HtcFingerPrintQuickLaunchProvider( 3916): -onCreate()
,V/Settings:HtcSettingsApplication( 3916): [3916/3916] onCreate()
,D/TetherSettings( 3916): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3916): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3916): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3916): Cust_ConnectToPC   : spcsc>false
D/        ( 3916): Cust_ConnectToPC   : IPT>true
,D/        ( 3916): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3916): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3916): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3916): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3916): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3916): Cust_ConnectToPC   : spcsc>false
D/        ( 3916): Cust_ConnectToPC   : IPT>true
D/        ( 3916): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3916): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3916): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3916): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3916): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3916): usb_cable_connect = 1
,D/SmartNS_Utility( 3916): usb_denied = 0
I/SmartNS_NSReceiver( 3916): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3916): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3916): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3916): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3916): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3916):  defaultType:0
I/SmartNS_PSService( 3916): fail notificaiton:false
D/SmartNS_Utility( 3916): usb_cable_connect = 1
D/SmartNS_Utility( 3916): usb_denied = 0
I/SmartNS_PSService( 3916): usb notificaiton:true
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (3916/1000)
V/Tethering(  911): bSetPropertyMultiRAB:false
,D/WVCdm   (  369): PrepareKeyRequest: nonce=1679930888
D/SmartNS_Utility( 3916): usb_cable_connect = 1
,I/RemoteViews( 1119): com.android.settings (true,33751552)
D/SmartNS_Utility( 3916): usb_denied = 0
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3916): usb notificaiton:true
,I/RemoteViews.Performance( 1119): com.android.settings 1 2 10
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  911): bSetPropertyMultiRAB:false
,W/WeatherUtility( 3478): can't get weather sync account
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (3916/1000)
,D/SmartNS_Utility( 3916): usb_cable_connect = 1
D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,D/SmartNS_Utility( 3916): usb_denied = 0
,I/RemoteViews( 1273): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1273): com.google.android.googlequicksearchbox 2 0 5
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1119): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1119): com.android.settings 1 0 10
,D/SMSBackup( 3446): Got a database change event
,I/SmartNS_PSService( 3916): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3916): USB Plugged, Set USBPlugged=  truePSenabled:false
,W/WeatherRequest( 3478): request cur loc, but there is no sys cur
,W/Settings( 3478): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 1 6 17
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/PMS     (  911): acquireWL(426bd6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  911): releaseWL(426bd6e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3934 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=33 [27][9][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 3934): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3934): call getInstance()
,D/PMS     (  911): acquireWL(4260dd58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3934 1000 null
D/PowerUsageList:PowerUsageHelper( 3934): MY_DEBUG = false
W/WeatherUtility( 1119): can't get weather sync account
D/WeatherUtility( 1322): Weather sync is On
D/WSP     ( 1322): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3478): can't get weather sync account
I/ActivityManager(  911): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3951 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/WeatherRequest( 3478): request cur loc, but there is no sys cur
,W/Settings( 3478): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 0 7 17
,W/Settings( 3742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/Adreno-EGL( 3742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3742): Local Branch: 
I/Adreno-EGL( 3742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3742):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (3742/10029)
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3969 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3663
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3663:com.android.chrome/u0a96 (adj 15): empty #17
,I/MusicStore( 3969): Database version: 95
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3663
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3969): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3969): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3969): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3969, uid=10154, userID:0
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/MediaRouterService(  911): Client com.google.android.music (pid 3969): Registered
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
I/MediaRouter( 3969): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 3969): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (3969/10154)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/CheckinRequestBuilder( 2156): Classify the device as Phone.
,D/MediaRouter( 3969): getSelectedRoute
,I/NetworkMonitor( 3969): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3969/10154)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3969, uid=10154, userID:0
,D/PMS     (  911): acquireWL(4258c840): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/Process (  911): killProcessQuiet, pid=3681
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TelephonyReceiver( 1246): bind: true
D/PMS     (  911): releaseWL(4258c840): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Killing 3681:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WIFI_ICON( 1119): WifiActivity: 1
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/ActivityManager(  911): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3992 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/GenericMessagesProvider( 3871): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3871): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 3871): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3871): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3871): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 3871): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3871): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3871): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3871): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3871): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3871): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3871): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3871): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3871): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3871): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3871): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3871): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3871): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3871): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3871): 	at android.os.Binder.execT,ransact(Binder.java:412)
W/System.err( 3871): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
D/DFPI.PIReciver( 3992): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3992): onHandleIntent
I/DFPI.ApkInstallService( 3992): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3992): check CID = HTC__032
I/DFPI.ApkInstallService( 3992): There is no Demo.apk in sd card or phone storage
D/Process (  911): killProcessQuiet, pid=3458
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Killing 3458:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  911): Recipient 3458
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4006 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
D/libc    ( 2156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2156): [NET] getaddrinfo-,err=8
D/libc    ( 2156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2156): [NET] getaddrinfo-, 1
D/libc    ( 2156): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =5d57 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,I/ActivityManager(  911): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  911): Recipient 3681
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (4006/10053)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (4006/10053)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 210
D/libc    (  362): [NET]res_nsend:resplen=84
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2156): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2156): [NET] getaddrinfo-,err=8
,D/libc    ( 2156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2156): [NET] getaddrinfo-,err=8
D/libc    ( 2156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2156): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2156): Sending checkin request (12236 bytes)
,W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42807c58 u0 ReceiverList{427aa238 4006 com.htc.musicenhancer/10053/u0 remote:42723218}}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4006): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
V/AlarmManager(  911): sending alarm PendingIntent{425eb960: PendingIntentRecord{4266c8f0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452276622896, Int=0
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  911):   Scheme: "mms"
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 3851): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3851): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  911): Resuming delayed broadcast
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/ActivityManager(  911): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4027 uid=10081 gids={50081, 5001, 1028, 1015}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
,D/Process (  911): killProcessQuiet, pid=3774
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/ActivityManager(  911): Killing 3774:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,D/Messaging( 3871): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 3871): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3871): 
D/MmsAsyncWorkHandler( 3871): HM tk = 20001
,D/ReportIndicatorCache( 3871): MSG_QUERY_REPORTS >>
,I/Messaging( 3871): mccmnc> 
D/DraftCache( 3871): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3871): [DraftCache/1] refresh
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/MmsConfig( 3871): networkCode: 
D/Messaging( 3871): ViewCache CreatePreloadOnlyConversationList
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/PhoneStorageUtil( 3871): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3871): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3871): createReceiver
,D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 3871): sense_version=6.0
D/TelephUtils( 1246): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1246): Update uri=content://mms, match=0
,V/MmsProvider( 1246): selection=st=129 AND m_type!=134
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,D/Jerry   ( 3871): start to preload cursor >>>>>>>
,W/ContextImpl( 4027): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] startService
,D/Messaging( 3871): Reset downloading state: 0
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1246): sku_id=99
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4027): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4027): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4027): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,V/MmsSystemEventReceiver( 3871): TransactionService is going to be woken up.
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 4027): MODE_GSM access default DB
,D/DraftCache( 3871): [DraftCache/373] rebuildCache
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/ActivityManager(  911): Delaying start of: ServiceRecord{425ef870 u0 com.htc.sense.mms/.transaction.TransactionService}
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
D/MmsSmsV2Provider( 1246):  phoneType = -1
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4027): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/Messaging( 3871): ViewCache CreatePreload
D/Messaging( 3871): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1246):  phoneType = -1
D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/Cust_MMSMS( 3871): _has_set_default_values_2=true
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/MsgPreferenceUtils( 3871): def_index: 0
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MsgPreferenceUtils( 3871): globalIndex = 1
D/MsgPreferenceUtils( 3871): phone state: true
D/MsgPreferenceUtils( 3871): sd state: false
,D/MsgPreferenceUtils( 3871): vIndex = 0
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  911): Recipient 3774
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/Messaging( 3871): mNeedToUpdateDate2: false
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/Jerry   ( 1246): URI_DRAFT
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/DraftCache( 3871): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3871): [DraftCache/373] rebuildCache time: 1
D/MmsAsyncWorkHandler( 3871): 
D/MmsAsyncWorkHandler( 3871): HM tk = 20002
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1246):  phoneType = -1
D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/Messaging( 3871): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1246): sku_id=99
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1246): sku_id=99
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,W/PackageManager(  911): Unable to load service info ResolveInfo{42651998 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,V/TransactionService( 3871): 1-Creating TransactionService
,I/CheckinRequestBuilder( 2156): Checkin reason type: 8 attempt count: 1
V/TransactionService( 3871): onStartCommand: 1
,D/MmsSystemEventReceiver( 3871): unRegisterForConnectionStateChanges
V/TransactionService( 3871): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 3871): Loading previous transactions.
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2156): Failed to find provider info for com.google.android.wearable.settings
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1246): device_type: 1
D/TransactionService( 3871): Force set service start id to 1
V/TransactionService( 3871): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3871): unRegisterForConnectionStateChanges
,V/TransactionService( 3871): Destroying TransactionService
,D/TransactionService( 3871): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3871): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3170
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3170:com.android.settings:remote/1000 (adj 15): empty #17
,D/DFPI.PIReciver( 3992): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3992): onHandleIntent
,I/DFPI.ApkInstallService( 3992): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3992): check CID = HTC__032
,I/DFPI.ApkInstallService( 3992): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4027): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4027): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
V/SoundPicker( 4027): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4027): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4027): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current, setting uri = content://media/internal/audio/media/262
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2156/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=23 [17][4][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3170
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.task/.TodoTaskReceiver
,I/CheckinRequestBuilder( 2156): Classify the device as Phone.
,I/ActivityManager(  911): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4069 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/CheckinTask( 2156): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/DFPI.PIReciver( 3992): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/CheckinService( 2156): Checking schedule, now: 1452276623468 next: 1452799560438
,I/CheckinService( 2156): active receiver: disabled
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2156, uid=10029, userID:0
I/DFPI.ApkInstallService( 3992): onHandleIntent
I/DFPI.ApkInstallService( 3992): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3992): check CID = HTC__032
I/DFPI.ApkInstallService( 3992): There is no Demo.apk in sd card or phone storage
,I/EASAppSvc( 4069): [ NA ]- onCreate()
,I/EASAppSvc( 4069): [ NA ]> onUpgrade: version = 63
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,D/CheckinService( 2156): Recording last checkin time for package unspecified as 1452276623490
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(426e6af8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ORMLib  ( 3507): put()
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3790
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3790:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3790
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4027): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4027): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4027): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4027): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4027): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): New client listening to asynchronous messages
I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (4069/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (4069/10064)
I/EASAppSvc( 4069): [ NA ]- onDestroy()
,I/EASAppSvc( 4069): [ NA ]> uninitEASService
D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (4069/10064)
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,D/LocationProviderProxy(  911): applying state to connected service
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/PMS     (  911): acquireWL(428f2668): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(428f2668): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  911): applying state to connected service
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/PMS     (  911): acquireWL(42376160): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): releaseWL(42376160): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/EASRequestController( 4069): [ NA ]release
D/PMS     (  911): acquireWL(428e3e88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/PMS     (  911): releaseWL(428e3e88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/EASAppSvc( 4069): [ NA ]< uninitEASService
I/EASAppSvc( 4069): [ NA ]- onCreate()
,I/EASAppSvc( 4069): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (4069/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (4069/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (4069/10064)
,D/ORMLib  ( 3507): put()
D/PMS     (  911): releaseWL(4260dd58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/EASAppSvc( 4069): [ NA ]- onDestroy()
,I/EASAppSvc( 4069): [ NA ]> uninitEASService
,I/EASRequestController( 4069): [ NA ]release
,I/EASAppSvc( 4069): [ NA ]< uninitEASService
I/ActivityManager(  911): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4103 uid=10068 gids={50068, 3003, 5012}
,D/AutoSetting( 1322): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1322): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1322): service - requestNLP() NetworkLocationProvider not enabled
,I/MediaStoreImporter( 3969): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  911): killProcessQuiet, pid=3837
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Killing 3837:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ORMLib  ( 3507): put()
I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  911): Recipient 3837
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DFPI.PIReciver( 3992): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3992): onHandleIntent
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3992): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3992): check CID = HTC__032
,I/DFPI.ApkInstallService( 3992): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Resuming delayed broadcast
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4027): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4027): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4027): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4027): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4027): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4027): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4027): MODE_GSM access default DB
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 4027): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4027): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4027): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4027): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3969): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(4264dea0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1496 10014 null
I/ActivityManager(  911): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  911): releaseWL(4264dea0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null,
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4131 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  911): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3851
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3851:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2904): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PMS     (  911): acquireWL(42358308): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42358308): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41fe04d8): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41fe04d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/SocialFeedProvider( 1273): +disConnect socialManager
,I/SocialFeedProvider( 1273): disconnect socialManager
,D/PMS     (  911): acquireWL(4238e9e0): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,I/SocialFeedProvider( 1273): -disConnect socialManager
I/ActivityManager(  911): Recipient 3851
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(4238e9e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425ed600): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425ed600): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42407620): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42407620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4257e240): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4257e240): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(420e7bf8): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(420e7bf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b7ec68 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,D/PMS     (  911): acquireWL(425b6aa0): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425b6aa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42427f38): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42427f38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41dff408): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41dff408): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41dffee8): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(41dffee8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/asset   ( 2904): Copying FileAsset 0x6440b368 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/PMS     (  911): acquireWL(426f2f10): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2904): UpdateCorporaTask done [took 420 ms] updated apps [took 420 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4149 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4149): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4149 dbg=false s=true
,I/DeviceManagement( 4149): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4162 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Process (  911): killProcessQuiet, pid=3807
,I/ActivityManager(  911): Killing 3807:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  911): Recipient 3807
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b7ec68 -
,D/PhoneApp( 1246): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1246): -- N1 =0
,D/PhoneApp( 1246): -- N2 =0
,D/PhoneApp( 1246): -- N3 =0
,I/ActivityManager(  911): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4162/10100)
,W/GAV2    ( 4162): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4162/10100)
,I/ActivityManager(  911): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4185 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  911): sending alarm PendingIntent{42510aa0: PendingIntentRecord{42510a40 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452276625214, Int=0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/ImageRamCache( 4185): create image Cache, size: 31457280.
I/ImageRamCache( 4185): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4185): create image Cache, size: 12582912.
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
I/FeedSettings( 4185): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4185): GroupBudget 0.500000 0.380000
D/WifiNative-wlan0(  911):    returned true
,I/FeedSettings( 4185): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4185): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4185): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4185): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4185): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4185): last commit ulog time 1452231696147
,I/SocialManager[SocialBiLogHelper]( 4185): skip commit this time
,D/Process (  911): killProcessQuiet, pid=3722
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3722:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3722
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Resuming delayed broadcast
,W/GAV2    ( 4162): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  911): killProcessQuiet, pid=3891
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4201 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  911): Killing 3891:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/Icing   ( 2156): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,I/ActivityManager(  911): Recipient 3891
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Icing   ( 2156): Loaded CLD2 Version V2.0 - 20141016
D/WifiService(  911): Client connection lost with reason: 4
,I/htcbackup-core( 4201): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4201): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4201): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 4149): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4149): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.cirmodule, com.htc.htcpowermanager, com.android.CSDFunctionG, com.htc.home.personalize, com.android.keychain, com.qualcomm.privinit, com.htc.smartdim, com.htc.drive.activator, com.htc.android.htcsetupwizard, com.android.settings, com.htc.autobot.cargps.provider, com.htc.guide, com.htc.mirrorlinkserver, com.qualcomm.timeservice, com.android.providers.settings, com.htc.checkinprovider, com.htc.android.htcloglevel, com.htc.backupreset, com.android.location.fused, com.htc.backup, com.htc.feedback, android, com.htc.usage, com.htc.lockscreen, com.android.inputdevices]
,I/DeviceManagement( 4149): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  911): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4219 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  911): killProcessQuiet, pid=3916
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3916:com.android.settings/1000 (adj 15): empty #17
,I/Icing   ( 2156): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,I/DeviceManagement( 4149): WorkflowService: Starting workflow service
I/DeviceManagement( 4149): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b2a890] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4149): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4149): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  911): Recipient 3916
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4149): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4149): SessionStateController: Checking invariants...
D/PMS     (  911): releaseWL(426f2f10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/HtcCupdReceiver(Provider)( 4219):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  911): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 6 times.
,I/DeviceManagement( 4149): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 4149): SessionStateController: Checking invariants...
,I/DeviceManagement( 4149): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4149): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b2a890]
,I/DeviceManagement( 4149): WorkflowService: Stopping workflow service
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4234 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3822
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3822:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3822
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  911): sending alarm PendingIntent{41d24db0: PendingIntentRecord{424e3158 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59284, Int=0
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(428e3e88): PARTIAL_WAKE_LOCK  AsyncService 0x1 4234 10160 null
,D/PMS     (  911): releaseWL(428e3e88): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(42842378): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4234 10160 null
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
,D/PMS     (  911): acquireWL(42841fe8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4234 10160 null
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(42842378): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4234/10160)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4234/10160)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(42841fe8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4257 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=3446
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3446:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3446
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 4257): -onCreate()
,V/Settings:HtcSettingsApplication( 4257): [4257/4257] onCreate()
,I/ActivityManager(  911): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4272 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3934
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3934:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4272, uid=10074, userID:0
,I/ActivityManager(  911): Recipient 3934
,D/Settings:HtcWirelessFeatureFlags( 4257): id/is att sku: 99/false
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 4257): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 4272): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (4272/10074)
,W/SystemReader( 4257): Cannot find support_harman, use default value instead
,W/SystemReader( 4257): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4257): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4257): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4257): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4257): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]support         :false
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/FingerprintManager( 4257): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4257): isSupportVoWifi: null
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4257): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (4272/10074)
,D/Finsky  ( 4272): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4272): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4272): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4272, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4257): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4257): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4257): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4257): [supportHomeButton]support         :false
,W/FingerprintManager( 4257): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4257): isSupportVoWifi: null
,D/Ads     ( 4272): Skipping gmscore version check
,D/Finsky  ( 4272): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4272): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4257): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/Finsky  ( 4272): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4272): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 4272): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/Process (  911): killProcessQuiet, pid=3478
,D/PackageBroadcastService( 2156): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,W/dalvikvm( 2156): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3478:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3478
,D/PMS     (  911): acquireWL(423aaad0): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(423aaad0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42386338): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2156): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2156): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2156): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2156): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2156): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2156): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2156): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2156): cleanUpNonGplusAccounts done.
,D/Process (  911): killProcessQuiet, pid=3871
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3871:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3871
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Icing   ( 2156): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/asset   ( 2156): Copying FileAsset 0x6e942e10 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Icing   ( 2156): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  911): releaseWL(42386338): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2156): Loading module APK com.google.android.play.games
I/ActivityManager(  911): Resuming delayed broadcast
,W/dalvikvm( 2156): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 2156): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 2156): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 2156): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2156): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  911): Resuming delayed broadcast
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/ActivityManager(  911): Killing 3507:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  911): killProcessQuiet, pid=3507
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:121, mTXpacketCount:57, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/AsyncTaskServiceImpl( 2156): Submit a task: k
,D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 2156): Processing package: com.example.hello
I/ActivityManager(  911): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/GassUtils( 2156): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 2156): Found info for package com.example.hello in db.
W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,W/BaseAppContext( 2156): Using Auth Proxy for data requests.
,I/ActivityManager(  911): Recipient 3507
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SQLiteConnectionPool( 2156): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  911): acquireWL(4266ed50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(4266ed50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
,D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/dalvikvm( 2156): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2156): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  911): Resuming delayed broadcast
,D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/TelephonyReceiver( 1246): bind: false
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,I/ActivityManager(  911): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4324 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  911): acquireWL(425d5120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
,D/Process (  911): killProcessQuiet, pid=4069
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 4069:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/PMS     (  911): releaseWL(425d5120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  911): Recipient 4069
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiService(  911): Client connection lost with reason: 4
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=72 rxSum=79} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  911): onDataStallAlarm: tag=19613 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  911): startDataStallAlarm: tag=19614 delay=15s
,I/ActivityManager(  911): Delaying start of: ServiceRecord{425e9140 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/RemoteViews( 1119): com.htc.updater (true,33751552)
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41eca6f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/NotificationService(  911): notification sound not played, stream=5 volume=0 always=false
I/RemoteViews.Performance( 1119): com.htc.updater 5 8 1 10
,I/RemoteViews( 1119): com.htc.updater (true,33751552)
,I/ActivityManager(  911): Resuming delayed broadcast
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ea3b28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.updater 0 8 0 10
,I/IcingCorporaProvider( 2904): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(4268c040): PARTIAL_WAKE_LOCK  AsyncService 0x1 4234 10160 null
,D/PMS     (  911): releaseWL(4268c040): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,W/dalvikvm( 4272): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/IcingCorporaProvider( 2904): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,D/PackageBroadcastService( 2156): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  911): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4351 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,V/AlarmManager(  911): sending alarm PendingIntent{426285e0: PendingIntentRecord{42622748 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452276629345, Int=0
,D/PMS     (  911): acquireWL(4257b398): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2156, uid=10029, userID:0
,D/PMS     (  911): releaseWL(4257b398): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427d3000): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4351): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  911): Delay finish: com.google.android.gm/.MailIntentReceiver
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4378 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  911): killProcessQuiet, pid=4103
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4103:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4103
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 4351): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4351): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4351): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4351): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel   ( 4378): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4378): MmsConfig.loadMmsSettings
,W/dalvikvm( 4378): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4378): VFY: unable to resolve instance field 36
,W/dalvikvm( 4378): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4378): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4406 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4378, uid=10111, userID:0
,W/Settings( 4378): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4378, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4378, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4378, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4378, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4378, uid=10111, userID:0
,D/PMS     (  911): acquireWL(42660f28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4378 10111 null
,D/MessageFrequencyProvider( 4406): onCreate
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4378): Installed default security provider GmsCore_OpenSSL
,V/GetPrviateResource( 4406): GetPrviateResource
,D/MmsCustomizationProvider( 4406): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4406): GetPrviateResource
,D/MmsCustomizationProvider( 4406): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4378): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4378): MmsConfig.loadFromDatabase
,D/Process (  911): killProcessQuiet, pid=3992
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  911): Killing 3992:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3992
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/Babel   ( 4378): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4378): MmsConfig.loadFromResources
E/Babel   ( 4378): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4378): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4406): sense_version=6.0
,D/BTAccessoryUtil( 4406): createReceiver
,D/BTAccessoryUtil( 4406): registerReceiver return intent = null
D/MessageCustFlag( 4406): sku_id=99
,W/SystemReader( 4406): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4406): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4406): networkCode: 
,D/MessageCustFlag( 4406): sku_id=99
D/MmsConfig( 4406): SIE smsPri: null
,D/MmsConfig( 4406): networkCode: 
D/HtcTelephonyCapability( 4406): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4406): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4406): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4406): Cannot find qct_8960_interface, use default value instead
D/PMS     (  911): releaseWL(42660f28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(427a0598): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4378 10111 null
,I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  911): releaseWL(427a0598): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(42707880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,I/SensorManager(  911): mEventCount = 450
,D/Process (  911): killProcessQuiet, pid=3951
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  911): Killing 3951:com.htc.mediamanager/u0a34 (adj 15): empty #17
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(42707880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): acquireWL(426f1370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(426f1370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4162): Thread[GAThread,5,main]: No campaign data found.
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
D/PMS     (  911): acquireWL(426bad50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(426b2c48): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(426bad50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,I/ActivityManager(  911): Recipient 3951
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(426b2c48): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  911): acquireWL(41d80c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(41d80c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(41cb7158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(41cb7158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(4268e528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(4268e528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(423ae200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(423ae200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2156): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2156): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  911): releaseWL(427d3000): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425940a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4442 uid=10041 gids={50041}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(425940a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4455 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=4027
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 4027:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4027
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(4261e0d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4455 10071 null
,D/PMS     (  911): acquireWL(426a9520): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4455 10071 null
,D/Process (  911): killProcessQuiet, pid=3969
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3969:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/PMS     (  911): acquireWL(427133b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4378 10111 null
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,E/TodoTaskNotifyService( 4455): java.lang.NullPointerException
,D/PMS     (  911): releaseWL(4261e0d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/System.err( 4455): java.lang.NullPointerException
W/System.err( 4455): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4455): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4455): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4455): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4455): stopSelfResult true
D/PMS     (  911): releaseWL(427133b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  911): releaseWL(426a9520): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
D/PMS     (  911): acquireWL(4276f730): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4455 10071 null
D/PMS     (  911): acquireWL(42793b38): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4455 10071 null
,D/PMS     (  911): releaseWL(4276f730): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4455): java.lang.NullPointerException
W/System.err( 4455): java.lang.NullPointerException
W/System.err( 4455): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4455): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4455): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4455): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4455): stopSelfResult true
D/PMS     (  911): releaseWL(42793b38): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  911): Done.
D/ConnectivityService(  911): Setting timer for 720seconds
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/LocationInitializer( 2156): Restart initialization of location
,E/MDM     ( 1225): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  911): acquireWL(426f0b30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(426f0b30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  911): Resuming delayed broadcast
E/TodoTaskNotifyService( 4455): java.lang.NullPointerException
W/System.err( 4455): java.lang.NullPointerException
,W/System.err( 4455): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4455): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4455): 	at android.os.Looper.loop(Looper.java:157)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
D/PMS     (  911): acquireWL(42623d98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4455 10071 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
D/PMS     (  911): acquireWL(426c5c50): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4455 10071 null
D/PMS     (  911): releaseWL(42623d98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/System.err( 4455): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4455): stopSelfResult true
D/PMS     (  911): releaseWL(426c5c50): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  911): acquireWL(426a30b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4378 10111 null
,I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/PMS     (  911): releaseWL(426a30b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3969
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
D/MediaRouterService(  911): Client com.google.android.music (pid 3969): Died!
,I/IcingCorporaProvider( 2904): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(42648d98): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424c5e58): PARTIAL_WAKE_LOCK  AsyncService 0x1 4234 10160 null
,D/PMS     (  911): releaseWL(424c5e58): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PackageBroadcastService( 2156): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/WSP     ( 1322): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1322): Weather sync is On
,I/PackageBroadcastService( 2156): Null package name or gms related package.  Ignoreing.
,I/WSP     ( 1322): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 08 20:10:30 CET 2016
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1322/10055)
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.ads.jams.SystemEventReceiver
,D/PMS     (  911): acquireWL(426ae878): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1322 10055 null
,I/Icing   ( 2156): updateResources: need to parse f{com.google.android.gms}
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 7 times.
,I/IcingCorporaProvider( 2904): UpdateCorporaTask done [took 386 ms] updated apps [took 386 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2156/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  911): Delay finish: com.htc.task/.TodoReceiver
,V/AlarmManager(  911): sending alarm PendingIntent{4241f610: PendingIntentRecord{4241f5d8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452276631102, Int=0
,D/TodoTaskshortcut( 4455): update TASK shortcut>
,I/iu.UploadsManager( 2156): End new media; added: 0, uploading: 0, time: 45 ms
,V/AlarmManager(  911): sending alarm PendingIntent{4250f430: PendingIntentRecord{425219b8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452276631170, Int=0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Icing   ( 2156): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Messaging( 4406): mNeedToUpdateDate2 start
,D/MmsConfig( 4406): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4406): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4406): 
D/MmsAsyncWorkHandler( 4406): HM tk = 20001
,D/ReportIndicatorCache( 4406): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4406): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41afc688
,I/Messaging( 4406): mccmnc> 
D/DraftCache( 4406): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4406): [DraftCache/1] refresh
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 4406): networkCode: 
,D/Messaging( 4406): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4406): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4406): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4406): createReceiver
,D/MessageCustFlag( 4406): sense_version=6.0
,D/Jerry   ( 4406): start to preload cursor >>>>>>>
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1246): sku_id=99
,D/Messaging( 4406): mNeedToUpdateDate2: false
D/TelephUtils( 1246): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1246): Update uri=content://mms, match=0
,V/MmsProvider( 1246): selection=st=129 AND m_type!=134
,D/Messaging( 4406): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4406): TransactionService is going to be woken up.
,D/DraftCache( 4406): [DraftCache/442] rebuildCache
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1246):  phoneType = -1
,I/ActivityManager(  911): Delaying start of: ServiceRecord{4265a3c0 u0 com.htc.sense.mms/.transaction.TransactionService}
I/Icing   ( 2156): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/Jerry   ( 1246): URI_DRAFT
D/Messaging( 4406): ViewCache CreatePreload
D/Messaging( 4406): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 4406): _has_set_default_values_2=true
D/DraftCache( 4406): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4406): [DraftCache/442] rebuildCache time: 1
D/MmsAsyncWorkHandler( 4406): 
D/MmsAsyncWorkHandler( 4406): HM tk = 20002
D/MsgPreferenceUtils( 4406): def_index: 0
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MsgPreferenceUtils( 4406): globalIndex = 1
,D/PMS     (  911): releaseWL(42648d98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/MsgPreferenceUtils( 4406): phone state: true
D/MsgPreferenceUtils( 4406): sd state: false
D/MsgPreferenceUtils( 4406): vIndex = 0
D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/AccFlag ( 1246): sku_id=99
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1246):  phoneType = -1
,D/MmsSmsV2Provider( 1246): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4406): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1246): sku_id=99
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/CheckinService( 2156): Done disabling old GoogleServicesFramework version
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2156, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/Prism.ItemManager( 4185): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4185): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,I/Launcher( 1273): Deferring update until onResume
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
,D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/PackageManager(  911): Unable to load service info ResolveInfo{426dfbe0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(42842378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42842378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  911): applying state to connected service
,D/PMS     (  911): acquireWL(4281e090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4281e090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427fe1d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427fe1d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427c5580): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427c5580): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/GAV2    ( 4351): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4378): Thread[GAThread,5,main]: No campaign data found.
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b7ec68 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Prism.ItemManager( 4185): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4185): loadItems() com.htc.launcher.pageview.WidgetManager@41b5cd68 +
,I/Prism.WidgetManager( 4185): onLoadItems() +
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b7ec68 -
,I/Prism.WidgetManager( 4185): onLoadItems() -
,I/Prism.ItemManager( 4185): loadItems() com.htc.launcher.pageview.WidgetManager@41b5cd68 -
,D/PhoneApp( 1246): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1246): -- N1 =0
,D/PhoneApp( 1246): -- N2 =0
,D/PhoneApp( 1246): -- N3 =0
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 8 times.
,I/CalendarProvider2( 1496): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1496): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/TransactionService( 4406): 1-Creating TransactionService
,V/TransactionService( 4406): onStartCommand: 1
,D/MmsSystemEventReceiver( 4406): unRegisterForConnectionStateChanges
V/TransactionService( 4406): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4406): Loading previous transactions.
,D/TelephUtils( 1246): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1246): device_type: 1
,D/TransactionService( 4406): Force set service start id to 1
,V/TransactionService( 4406): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4406): unRegisterForConnectionStateChanges
,V/TransactionService( 4406): Destroying TransactionService
,D/TransactionService( 4406): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(4279c500): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(42791de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/PMS     (  911): releaseWL(4279c500): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  911): releaseWL(42791de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/TransactionService( 4406): 4-Handling incoming message: { when=-30ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=4530 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 4530): Database version: 95
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4530): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4530): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4530): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4530, uid=10154, userID:0
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/MediaRouterService(  911): Client com.google.android.music (pid 4530): Registered
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
I/MediaRouter( 4530): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PMS     (  911): acquireWL(42340978): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4530 10154 null
,I/ActivityManager(  911): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/NetworkMonitor( 4530): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (4530/10154)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 4530): getSelectedRoute
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/NetworkMonitor( 4530): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (4530/10154)
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4530, uid=10154, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4530, uid=10154, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(42686db0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,I/MusicLeanback( 4530): Conditions not met for autocaching.
,I/MusicLeanback( 4530): Stop autocaching.
D/PMS     (  911): releaseWL(42340978): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  911): releaseWL(42686db0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/ConfigStore( 4530): Config Database version: 1
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/MusicLeanback( 4530): Stop autocaching.
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/MusicLeanback( 4530): Stop autocaching.
I/MusicLeanback( 4530): Stop autocaching.
,I/MusicLeanback( 4530): Stop autocaching.
,I/MusicLeanback( 4530): Stop autocaching.
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4553 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/Process (  911): killProcessQuiet, pid=4131
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4131:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4131
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 4553): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4576 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/Process (  911): killProcessQuiet, pid=4162
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4162:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/SyncApplication( 4576): Loading default preferences
,W/Resources( 4576): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  911): New client listening to asynchronous messages
,D/SyncApplication( 4576): Overriding preferences with custom values
,D/SyncApplication( 4576): Updating preferences succeeded
,E/SyncApplication( 4576): Application created.
D/VolumeInfo( 4576): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4576): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4576): Found 0 mount point(s)
,V/VolumeInfo( 4576): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4576): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4576): getNewCalendarAuthority()...
,D/VolumeInfo( 4576): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4576): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4576): enableAppOperation()+
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4576, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4576, uid=10008, userID:0
,W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4576): enableAppOperation()-
D/HTCUtilities( 4576): isNeorSinged() + 
,D/HTCUtilities( 4576): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4576): isNeorSinged() return false
,I/ActivityManager(  911): Recipient 4162
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CDMountReceiver( 4576): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4576): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4576): enable CD Auto-mount: true
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/ActivityManager(  911): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4576): enable auto-mount
D/HTCUtilities( 4576): enable auto-mount
,I/RemoteViews( 1119): com.nero.android.htc.sync (false,0)
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): releaseWL(426b5918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e2c380 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.nero.android.htc.sync 2 12 3 11
,I/RemoteViews( 1119): com.nero.android.htc.sync (false,0)
I/ActivityManager(  911): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=4185
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ed6c38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  911): Killing 4185:com.htc.sense.news/u0a76 (adj 15): empty #17
I/RemoteViews.Performance( 1119): com.nero.android.htc.sync 1 9 3 16
,D/PMS     (  911): acquireWL(425bedd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(425bedd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(426ab000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): acquireWL(427d66d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4378 10111 null
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4185
D/PMS     (  911): releaseWL(426ab000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(427d66d8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2904): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  911): acquireWL(427c3fe8): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427c3fe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426d5b58): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426d5b58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42672598): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42672598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4267ef68): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(4267ef68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42677728): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
,D/PMS     (  911): releaseWL(42677728): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4266d840): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4266d840): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(426ac678): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426ac678): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4261f640): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4261f640): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2904): UpdateCorporaTask done [took 281 ms] updated apps [took 281 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(42773768): PARTIAL_WAKE_LOCK  AsyncService 0x1 4234 10160 null
,D/PMS     (  911): releaseWL(42773768): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PackageBroadcastService( 2156): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2156): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{426fd758 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  911): acquireWL(4281e090): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2156): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4609 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4609): onCreate
D/ProviderChangeReceiver( 4609): ---------------------------------------------------
,D/ProviderChangeReceiver( 4609): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4609): start to updateAlertNotification!
,I/ActivityManager(  911): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4623 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=4201
,I/ActivityManager(  911): Killing 4201:com.htc.backup/1000 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4609): No fired or scheduled alerts
,D/HtcAlertUtils( 4609): -- cancelReminderNotification --
,D/HtcAlertUtils( 4609): broadcastExistReminder!
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  911): Recipient 4201
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4623): [4623/4623] onCreate()
W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=4149
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  911): Killing 4149:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4149
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(426fd3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): releaseWL(426fd3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  911): mEventCount = 600
,I/Icing   ( 2156): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2156): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  911): releaseWL(4281e090): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/PMS     (  911): releaseWL(426ae878): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 9 times.
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  911): acquireWL(426a34c8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4530 10154 null
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4530): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4530, uid=10154, userID:0
,I/MusicLeanback( 4530): Conditions not met for autocaching.
,I/MusicLeanback( 4530): Stop autocaching.
D/PMS     (  911): releaseWL(426a34c8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  911): acquireWL(42683718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{42624698: PendingIntentRecord{424f6568 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452276641883, Int=0
,D/PMS     (  911): releaseWL(42683718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Finsky  ( 4272): [449] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4272): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Finsky  ( 4272): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4272): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  911): acquireWL(424b7a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
V/AlarmManager(  911): sending alarm PendingIntent{42747da0: PendingIntentRecord{427d3468 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452276642380, Int=0
D/PMS     (  911): releaseWL(424b7a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (4272/10074)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4272): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4272): [NET] getaddrinfo-,err=8
D/libc    ( 4272): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4272): [NET] getaddrinfo-, 1
D/libc    ( 4272): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =63ce +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4272): [NET] getaddrinfo_proxy-, success
I/global  ( 4272): call createSocket() return a new socket.
D/libc    ( 4272): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4272): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4272): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4272): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4272): untagSocket(69) failed with errno -22
,D/Finsky  ( 4272): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4272): untagSocket(69) failed with errno -22
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=21 [19][4][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 102
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:144, mTXpacketCount:121, avgLinkspeed:20,mAvgTxRate54
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=91 rxSum=95} preTxRxSum={txSum=72 rxSum=79}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=19614 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=19615 delay=15s
D/PMS     (  911): acquireWL(41bd8468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{42614658: PendingIntentRecord{42598e38 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=77193, Int=0
D/PMS     (  911): releaseWL(41bd8468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/NetworkManagementSocketTagger( 4272): untagSocket(69) failed with errno -22
,D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.android.vending (4272/10074)
,D/Finsky  ( 4272): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  911): acquireWL(42813f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074},
,V/AlarmManager(  911): sending alarm PendingIntent{425ccab8: PendingIntentRecord{428fa348 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1452276644588, Int=0
,D/PMS     (  911): acquireWL(42673558): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4272 10074 null
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/Finsky  ( 4272): [459] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1225): client connected with version: 8296000
D/PMS     (  911): releaseWL(42813f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4272): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4272): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/libc    ( 4272): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4272): [NET] getaddrinfo-,err=8
D/libc    ( 4272): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4272): [NET] getaddrinfo-, 1
,D/libc    ( 4272): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =f2d5 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 172
D/libc    (  362): [NET]res_nsend:resplen=87
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4272): [NET] getaddrinfo_proxy-, success
,D/PMS     (  911): releaseWL(42673558): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 10 times.
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=21 [51][11][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 6
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  911): mEventCount = 750
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1322): service - mHandler: update timezone
,D/AutoSetting( 1322): service - handleMessage() stop self
,D/AutoSetting( 1322): service - handleMessage() quit looper
,D/AutoSetting( 1322): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=4219
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4219:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 4219
,D/AutoSetting( 1496): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1496): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1496): service - onCreate()
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1496): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1496): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1496): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1496): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1496): service - mHandler: update timezone
,D/AutoSetting( 1496): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1496): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1496): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1496): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1552): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41f14250 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 10 2 11
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 12
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 11 times.
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 18
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 24
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 12 times.
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  911): acquireWL(42681cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42681cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 30
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:207, mTXpacketCount:144, avgLinkspeed:6,mAvgTxRate54
,D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=141 rxSum=142} preTxRxSum={txSum=91 rxSum=95}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=19615 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=19616 delay=15s
D/PMS     (  911): acquireWL(4273e250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{423cb368: PendingIntentRecord{42598e38 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=92198, Int=0
D/PMS     (  911): releaseWL(4273e250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42708a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41b00f68: PendingIntentRecord{41fca1e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=93181, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42708a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1119): now=1452276660050 next=59950
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1496): Don't start project servcice
,D/HtcModeClient( 1496): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1496): connectState: CONNECTION_READY = false
,D/SilentMusic( 1496): call stop
,D/HtcModeClient( 1496): close connection
,W/HtcModeClient( 1496): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1496): read the terminate packet, so break
,I/SensorManager(  911): mEventCount = 900
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/PMS     (  911): acquireWL(4273b200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{425bd2a8: PendingIntentRecord{424f6568 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452276658783, Int=0
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4659 uid=10078 gids={50078}
,V/AlarmManager(  911): sending alarm PendingIntent{4258efb8: PendingIntentRecord{425af4e0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452276661944, Int=60000
,D/PMS     (  911): releaseWL(4273b200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4659): SMSBackupAgentService started
,D/SMSBackup( 4659): Checking restore status
D/SMSBackup( 4659): Restore complete
,D/SMSBackup( 4659): cancelCheckAlarm
,D/SMSBackup( 4659): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/Finsky  ( 4272): [449] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4272): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  911): killProcessQuiet, pid=3742
,I/ActivityManager(  911): Killing 3742:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3742
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4261a7f8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 30
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,V/LightsService(  911): setLight #0: color=#26
,V/LightsService(  911): setLight #0: color=#23
,V/LightsService(  911): setLight #0: color=#1c
,V/LightsService(  911): setLight #0: color=#16
,V/LightsService(  911): setLight #0: color=#14
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 36
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/SensorManager(  911): mEventCount = 1050
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 42
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4220c338
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4220c338, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42083580
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@41e9da88
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  911): mWirelessDisplayManager is null
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 342ms
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
,D/NfcService( 1259): applyRouting -2
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4280dd48)
I/InputMethodManagerService(  911): Disable input method client, pid=3596
D/PMS     (  911): acquireWL(4280d398): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMN     (  911): wakingUp
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  911): releaseWL(4280d398): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  911): No lock screen! windowToken=null
D/PMN     (  911): onScreenOn
,D/MtpService( 2377): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2377): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting - 0
,D/AutoSetting( 1322): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1259): applyRouting -2
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  911): acquireWL(4282bce0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  911): releaseWL(4282bce0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  911): startDataStallAlarm: tag=19617 delay=15s
,D/AutoSetting( 1322): service - onCreate()
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
I/wpa_supplicant( 1160): SET_SCREEN_ON:On
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): BG scan when screen On
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): Match BG scan, scan!
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  911):    returned true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1322): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1322): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  911): request 42477550 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/TetherSettings( 4257): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4257): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4257): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4257): Cust_ConnectToPC   : spcsc>false
D/        ( 4257): Cust_ConnectToPC   : IPT>true
D/        ( 4257): Cust_ConnectToPC   : Singel_USB>false
D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
V/SRS_Proc(  369): ParamSet string: screen_state=on
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/Settings( 4257): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4257): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4257): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4257): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4257): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1119): stop update clock
W/ContextImpl( 4257): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  911): updateScreenOn: false
I/SmartNS_PSService( 4257): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4257): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4257):  defaultType:0
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4683 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  911): acquireWL(42749e98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42749e98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4274b830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOn: 1452276672636
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOn: 1452276672636
D/PMS     (  911): releaseWL(4274b830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42083580
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42083580, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@41e9da88
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): acquireWL(427df6a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=19617 mDataStallAlarmIntent=PendingIntent{4254eb68: PendingIntentRecord{42598e38 android broadcastIntent}}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
D/PMS     (  911): releaseWL(427df6a0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): acquireWL(428dbc68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(428dc548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4683 1000 null
,D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
D/PMS     (  911): releaseWL(428dc548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 6
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:Off
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 48
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:210, mTXpacketCount:207, avgLinkspeed:9,mAvgTxRate54
D/WifiStateMachine(  911): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  369): ParamSet string: screen_state=off
,D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1246): start background delete task...
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
D/WifiService(  911): New client listening to asynchronous messages
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e9da88
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e9da88, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e9da88, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e9da88
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425cb8f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425cb8f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
,E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
,E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	,at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method),
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): acquireWL(428f0e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(428f0e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(42932db0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42932db0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOff
,D/AutoSetting( 1322): service - mHandler: cancel location update
,D/AutoSetting( 1322): service -           changes count: 0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(428dbc68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1160): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1160): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1160): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1160): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_,ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1160): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1160): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1160): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1160): Add randomness: count=16 entropy=9
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA s,ubelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (665) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000021560114
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000107836536
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000107836548
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-87
I/wpa_supplicant( 1160): tsf=0000000107836558
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000107836568
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 21560114, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4271d118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4271d118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4271d118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 107836536, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 107836548, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 107836558, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 107836568, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-87], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/AutoSetting( 1496): service - handleMessage() stop self
,D/AutoSetting( 1496): service - onDestroy() END
,D/AutoSetting( 1496): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4324
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4324:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4324
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  911): killProcessQuiet, pid=4006
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4006:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4006
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42810a78 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=17 entropy=10
D/wpa_supplicant( 1160): Add randomness: count=18 entropy=11
D/wpa_supplicant( 1160): Add randomness: count=19 entropy=12
D/wpa_supplicant( 1160): Add randomness: count=20 entropy=13
D/wpa_supplicant( 1160): Add randomness: count=21 entropy=14
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: U,pdating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=22 entropy=15
D/wpa_supplicant( 1160): Add randomness: count=23 entropy=16
D/wpa_supplicant( 1160): Add randomness: count=24 entropy=17
D/wpa_supplicant( 1160): Add randomness: count=25 entropy=18
D/wpa_supplicant( 1160): Add randomness: count=26 entropy=19
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (665) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000021560114
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000125244580
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-78
I/wpa_supplicant( 1160): tsf=0000000125244592
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-86
I/wpa_supplicant( 1160): tsf=0000000125244601
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000107836568
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 21560114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 125244580, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 125244592, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 125244601, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 107836568, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (5) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4275fc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4275fc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1552): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1552): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(427659f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{4264c3c0: PendingIntentRecord{425ac780 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123524, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{425c10b8: PendingIntentRecord{41f1f278 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136586, Int=0
,D/PMS     (  911): acquireWL(427ac898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(427b2c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1322): service - handleMessage() stop self
,D/PMS     (  911): releaseWL(427b2c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 1322): service - handleMessage() quit looper
,D/AutoSetting( 1322): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=4442
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4442:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/PMS     (  911): releaseWL(427ac898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(427bb128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(427659f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  911): Recipient 4442
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(427bb128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(428666c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): acquireWL(4286f7f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42845ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(428666c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4286f7f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(428e6e60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(428e6e60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(428e3bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
I/VacuumService( 1225): Vacuum at: now=1452276703777 tag=VacuumService
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(428e3bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42845ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42825100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(42825100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42822cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(42822cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42804290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(427ebe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427ebe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427ea318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42804290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427e5ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(427e5ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 1770 seconds from now (1452276704360)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
D/libc    ( 1225): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =eb99 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=45 [11][5][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(427ea318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42520588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(42520588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41ee3030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=100 [2][2][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023715
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023866
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023949
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023953
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360023959
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025425
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360028196
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029610
,D/PMS     (  911): releaseWL(41ee3030): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/PMS     (  911): acquireWL(426aae98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  911): sending alarm PendingIntent{424b09f0: PendingIntentRecord{424b0ea0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141167, Int=0
D/PMS     (  911): acquireWL(4265cfe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(426aae98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =83d8 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=27 entropy=20
D/wpa_supplicant( 1160): Add randomness: count=28 entropy=21
D/wpa_supplicant( 1160): Add randomness: count=29 entropy=22
D/wpa_supplicant( 1160): Add randomness: count=30 entropy=23
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): sen,d_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=31 entropy=24
D/wpa_supplicant( 1160): Add randomness: count=32 entropy=25
D/wpa_supplicant( 1160): Add randomness: count=33 entropy=26
D/wpa_supplicant( 1160): Add randomness: count=34 entropy=27
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (665) for get BSS: id=0,
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000142352263
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====,
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000142352289
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-78
I/wpa_supplicant( 1160): tsf=0000000142352300,
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
,I/wpa_supplicant( 1160): level=-86
I/wpa_supplicant( 1160): tsf=0000000125244601
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e,
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000107836568
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 142352263, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 142352289, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 142352300, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 125244601, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  911): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 107836568, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 5 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (5) end of scan result ==
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
,I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  911): releaseWL(4265cfe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(42359758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{41b00f68: PendingIntentRecord{41fca1e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=153180, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42359758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=35 entropy=28
D/wpa_supplicant( 1160): Add randomness: count=36 entropy=29
D/wpa_supplicant( 1160): Add randomness: count=37 entropy=30
D/wpa_supplicant( 1160): Add randomness: count=38 entropy=31
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 l,evel=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=39 entropy=32
D/wpa_supplicant( 1160): Add randomness: count=40 entropy=33
D/wpa_supplicant( 1160): Add randomness: count=41 entropy=34
D/wpa_supplicant( 1160): Add randomness: count=42 entropy=35
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  911): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (523) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000159736127
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56,
I/wpa_supplicant( 1160): tsf=0000000159736152
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-78
I/wpa_supplicant( 1160): tsf=0000000159736163
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000107836568
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000),
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 159736127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 159736152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 159736163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 107836568, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 4 to mScanResults
D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
,D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (4) end of scan result ==
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(426bc3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(426bc3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  911): acquireWL(4272db18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{4260bba8: PendingIntentRecord{42788758 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172768, Int=0
,D/PMS     (  911): releaseWL(4272db18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=43 entropy=36
D/wpa_supplicant( 1160): Add randomness: count=44 entropy=37
D/wpa_supplicant( 1160): Add randomness: count=45 entropy=38
D/wpa_supplicant( 1160): Add randomness: count=46 entropy=39
D/wpa_supplicant( 1160): Add randomness: count=47 entropy=40
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
,I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=48 entropy=41
,D/wpa_supplicant( 1160): Add randomness: count=49 entropy=42
D/wpa_supplicant( 1160): Add randomness: count=50 entropy=43
D/wpa_supplicant( 1160): Add randomness: count=51 entropy=44
D/wpa_supplicant( 1160): Add randomness: count=52 entropy=45
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1160): reply (778) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000177125155
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000177125192
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
,I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-78
I/wpa_supplicant( 1160): tsf=0000000177125203
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000107836568
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000177125181
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-86
I/wpa_supplicant( 1160): tsf=0000000177125212
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
,D/WirelessDisplayService(  911): getDiscoveryDongleList
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 177125155, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 177125192, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 177125203, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  911): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 107836568, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 177125181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 5: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 177125212, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 6 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
,V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(425d9e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(425d9e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=53 entropy=46
D/wpa_supplicant( 1160): Add randomness: count=54 entropy=47
D/wpa_supplicant( 1160): Add randomness: count=55 entropy=48
D/wpa_supplicant( 1160): Add randomness: count=56 entropy=49
D/wpa_supplicant( 1160): Add randomness: count=57 entropy=50
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Receive,d scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=58 entropy=51
D/wpa_supplicant( 1160): Add randomness: count=59 entropy=52
D/wpa_supplicant( 1160): Add randomness: count=60 entropy=53
D/wpa_supplicant( 1160): Add randomness: count=61 entropy=54
D/wpa_supplicant( 1160): Add randomness: count=62 entropy=55
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1160): reply (778) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000194514656
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000194514693
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-77
I/wpa_supplicant( 1160): tsf=0000000194514704
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000194514713
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412,
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000194514683
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-86
I/wpa_supplicant( 1160): tsf=0000000177125212
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 194514656, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 194514693, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 194514704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 194514713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 194514683, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 5: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 177125212, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): add 6 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  911): == (6) end of scan result ==
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==
,D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=63 entropy=56
D/wpa_supplicant( 1160): Add randomness: count=64 entropy=57
D/wpa_supplicant( 1160): Add randomness: count=65 entropy=58
D/wpa_supplicant( 1160): Add randomness: count=66 entropy=59
D/wpa_supplicant( 1160): Add randomness: count=67 entropy=60
D/wpa_supplicant( 1160): Add randomness: count=68 entropy=61
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=,24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=69 entropy=62
D/wpa_supplicant( 1160): Add randomness: count=70 entropy=63
D/wpa_supplicant( 1160): Add randomness: count=71 entropy=64
D/wpa_supplicant( 1160): Add randomness: count=72 entropy=65
D/wpa_supplicant( 1160): Add randomness: count=73 entropy=66
D/wpa_supplicant( 1160): Add randomness: count=74 entropy=67
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1160): reply (778) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000211914931
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000211914968
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-77
I/wpa_supplicant( 1160): tsf=0000000194514704
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-92
I/wpa_supplicant( 1160): tsf=0000000211914998
,I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-56
I/wpa_supplicant( 1160): tsf=0000000211914957
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-88
I/wpa_supplicant( 1160): tsf=0000000211914987,
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiP2pService(  911): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 211914931, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 211914968, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  911): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 194514704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 211914998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 211914957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 5: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -88, frequency: 2437, timestamp: 211914987, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 6 to mScanResults
,V/ScoreHelper(  911): Only print Top 10 in ApScanList
V/ScoreHelper(  911):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  911):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  911):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  911):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-88], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  911):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  911):  + computeScore(NG700): 1
,D/WifiStateMachine(  911): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
,D/WifiStateMachine(  911): == (6) end of scan result ==,
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4730): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4730): ====startRecUseTime====
D/htc.customization.log.level( 4730):  is 
W/CustomizationLogLevel( 4730): Level value is invalid, use default level 2
D/CustomizationManager( 4730):  Read ACC file spent 0.117 (s)
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4730): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4730): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4730): Parsing tag category name = system
I/CustomizationCIDLoader( 4730): Parsing tag category name = application
I/CustomizationCIDLoader( 4730): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4730): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4730): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4730): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4730): Parsing tag category name = Settings
D/CustomizationManager( 4730):  Read CID file spent 0.169 (s)
D/CustomizationManager( 4730):  All configurations done spent 0.169 (s)
W/HtcNativeFlag( 4730): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4730): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4730): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4730): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.example.hello, pid=4730, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=3596
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/asset   (  911): Copying FileAsset 0x67221168 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  911): Killing 3596:com.example.hello/u0a397 (adj 0): stop com.example.hello
I/ActivityManager(  911):   Force finishing activity ActivityRecord{42376968 u0 com.example.hello/.MainActivity t2}
W/PackageSettings(  911): Skipping PackageSetting{421acba0 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  911): Force stopping com.example.hello appid=10397 user=0: pkg removed
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1211): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 3596 uid 10397
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1552): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1552): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/InputDispatcher(  911): channel '4262bab0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  911): channel '4262bab0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  911): channel '426e3f80 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  911): channel '426e3f80 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
W/InputDispatcher(  911): Attempted to unregister already unregistered input channel '4262bab0 com.example.hello.MainActivity (s)'
D/PMS     (  911): acquireWL(42946e10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42946e10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/WindowManager(  911): WINDOW DIED Window{4262bab0 u0 com.example.hello/com.example.hello.MainActivity}
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/InputDispatcher(  911): Attempted to unregister already unregistered input channel '426e3f80 com.example.hello.MainActivity (s)'
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
W/WindowManager(  911): Failed looking up window
W/WindowManager(  911): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42710108 does not exist
W/WindowManager(  911): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  911): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  911): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  911): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  911): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  911): WIN DEATH: null
I/WindowState(  911): WIN DEATH: Window{426e3f80 u0 com.example.hello/com.example.hello.MainActivity}
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.example.hello
I/WindowManager(  911): WINDOW DIED Window{426e3f80 u0 com.example.hello/com.example.hello.MainActivity}
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1322): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
D/PMS     (  911): acquireWL(4294f2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{41b00f68: PendingIntentRecord{41fca1e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=213181, Int=0
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/[PluginManager]RegisterService( 1322): handle notify Blinkfeed plugin client changed
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/IcingCorporaProvider( 2904): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4746 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  911): acquireWL(41f862b8): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(41f862b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(41e60150): PARTIAL_WAKE_LOCK  Icing 0x1 2156 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2904): UpdateCorporaTask done [took 258 ms] updated apps [took 258 ms] 
E/SQLiteDatabase( 4746): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4746): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4746): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4746): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4746): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4746): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4746): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4746): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4746): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4746): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4746): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4746): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4746): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4746): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4746): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4746): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4746): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4746): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4746): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4746): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4746): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4746): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4746): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4746): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4746): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4746): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4746): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4746): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4746): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4746): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4746): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4746): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4746): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4746): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4746): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4746): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4746): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4746): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4746): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4746): threadid=11: thread exiting with uncaught exception (group=0x416bbe30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4746): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4746): Process: com.google.android.apps.docs, PID: 4746
E/AndroidRuntime( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4746): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4746): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4746): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4746): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4746): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
E/SQLiteDatabase( 4746): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4746): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4746): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4746): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4746): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4746): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4746): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4746): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4746): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4746): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4746): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4746): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4746): Opened ClientFlag.db in read-only mode
D/Process ( 4746): killProcess, pid=4746
D/Process ( 4746): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4764 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  911): Recipient 4746
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4746) has died.
W/ContextImpl( 4764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4777 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4764): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4764): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4764): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4764): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4764): threadid=10: thread exiting with uncaught exception (group=0x416bbe30)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4764): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4764): Process: com.android.keychain, PID: 4764
E/AndroidRuntime( 4764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4764): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4764): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4764): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4777): getInstance(Context context)
D/Process ( 4764): killProcess, pid=4764
D/Process ( 4764): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4777): getInstance(Context context)
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452276781112.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
D/AppTag  ( 4777): onCreate()
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4764
I/ActivityManager(  911): Process com.android.keychain (pid 4764) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  911): acquireWL(425dc020): PARTIAL_WAKE_LOCK  AsyncService 0x1 4234 10160 null
D/PMS     (  911): releaseWL(425dc020): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  911): killProcessQuiet, pid=4455
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4455:com.htc.task/u0a71 (adj 15): empty #17
W/dalvikvm( 4272): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2156): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 2156): Clearing selected account for com.example.hello
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4455
D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2156): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2156): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2156): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2156): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d6a2010
E/SQLiteLog( 2156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2156): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6d05c138
W/dalvikvm( 2156): threadid=45: thread exiting with uncaught exception (group=0x416bbe30)
E/DriveAsyncService( 2156): disk I/O error (code 3850)
E/DriveAsyncService( 2156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2156): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2156): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2156): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2156): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2156): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2156): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2156): 	at java.lang.Thread.run(Thread.java:864)
I/LocationSettingsChecker( 2156): Removing dialog suppression flag for package com.example.hello
W/PackageManager(  911): Unable to load service info ResolveInfo{4258fc30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2156): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2156): Process: com.google.android.gms, PID: 2156
E/AndroidRuntime( 2156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2156): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2156): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2156): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2156): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2156): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2156): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2156): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2156): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2156): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2156): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2156): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
D/Process ( 2156): killProcess, pid=2156
D/Process ( 2156): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b7ec68 +
I/Prism.WidgetManager( 1273): onLoadItems() +
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 2156
I/ActivityManager(  911): Process com.google.android.gms (pid 2156) has died.
D/WifiService(  911): Client connection lost with reason: 4
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20997ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30997ms
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): handleWLDeath(41e60150): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30993ms
E/SQLiteLog( 1372): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1372): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f43c10
W/dalvikvm( 1372): threadid=1: thread exiting with uncaught exception (group=0x416bbe30)
E/AndroidRuntime( 1372): FATAL EXCEPTION: main
E/AndroidRuntime( 1372): Process: com.google.process.gapps, PID: 1372
E/AndroidRuntime( 1372): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1372): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1372): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1372): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1372): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1372): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1372): 	... 10 more
E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 1372): killProcess, pid=1372
D/Process ( 1372): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4809 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4809): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4809 dbg=false s=true
I/DeviceManagement( 4809): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4809): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/ActivityManager(  911): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4809): WorkflowService: Starting workflow service
I/DeviceManagement( 4809): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b18d68] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4809): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4809): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4809): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4809): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4809): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4809): SessionStateController: Checking invariants...
I/ActivityManager(  911): Recipient 1372
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.process.gapps (pid 1372) has died.
D/WifiService(  911): Client connection lost with reason: 4
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40844ms
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
D/RemoteDisplayProvider(  911): start

```
