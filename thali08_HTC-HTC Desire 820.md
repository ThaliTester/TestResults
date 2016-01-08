#### Test 5024228542a63d7_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/MusicStore( 3454): Database version: 95
W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
--------- beginning of /dev/log/system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3454, uid=10154, userID:0
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/MediaRouterService(  903): Client com.google.android.music (pid 3454): Registered
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/SensorManager(  903): mEventCount = 300
I/MediaRouter( 3454): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3454/10154)
I/NetworkMonitor( 3454): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2467/10021)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3481 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/MediaRouter( 3454): getSelectedRoute
I/NetworkMonitor( 3454): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3454/10154)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3454, uid=10154, userID:0
D/Process (  903): killProcessQuiet, pid=3176
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Killing 3176:com.zoodles.kidmode/u0a149 (adj 15): empty #17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3176
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/ACRA    ( 3481): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 3481): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 3481): Looking for error files in /data/data/com.facebook.katana/app_minidumps
W/SystemClassLoaderAdder( 3481): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 3481): Preparing secondary program dexes.
V/DexLibLoader( 3481): Loaded 4 raw lines of metadata.
V/DexLibLoader( 3481): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3481): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3481): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 3481): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3481): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3481): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3481): Dex already copied
D/OdexVerifier( 3481): Odex verification is skipped.
V/DexLibLoader( 3481): Creating class loader
V/DexLibLoader( 3481): Finished creating class loader
V/DexLibLoader( 3481): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3481): Dex already copied
D/OdexVerifier( 3481): Odex verification is skipped.
V/DexLibLoader( 3481): Creating class loader
V/DexLibLoader( 3481): Finished creating class loader
V/DexLibLoader( 3481): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3481): Dex already copied
D/OdexVerifier( 3481): Odex verification is skipped.
V/DexLibLoader( 3481): Creating class loader
V/DexLibLoader( 3481): Finished creating class loader
V/DexLibLoader( 3481): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3481): Dex already copied
D/OdexVerifier( 3481): Odex verification is skipped.
V/DexLibLoader( 3481): Creating class loader
V/DexLibLoader( 3481): Finished creating class loader
V/DexLibLoader( 3481): Verifying classes from secondary dexes.
E/cutils-trace( 3477): Error opening trace file: No such file or directory (2)
D/DexLibLoader( 3481): DexLibLoader.ensureDexLoaded took 105 ms
D/CustomizationManager( 3477): ====startRecUseTime====
D/htc.customization.log.level( 3477):  is 
W/CustomizationLogLevel( 3477): Level value is invalid, use default level 2
D/CustomizationManager( 3477):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3477): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3477): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3477): Parsing tag category name = system
I/CustomizationCIDLoader( 3477): Parsing tag category name = application
I/CustomizationCIDLoader( 3477): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3477): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3477): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3477): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3477): Parsing tag category name = Settings
D/CustomizationManager( 3477):  Read CID file spent 0.120 (s)
D/CustomizationManager( 3477):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 3477): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3477): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3477): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3477): Fail to get flag for type 'language', use default value: -1
D/Process (  903): killProcessQuiet, pid=3217
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3217:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3217
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  903): Copying FileAsset 0x6bf07cd0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1111670744
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3477
D/PMS     (  903): acquireHCC(4240c920): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(4238ee18): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
D/PMS     (  903): acquireWL(41e40a88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420fed00
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3504 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
W/asset   ( 3504): Copying FileAsset 0x5d888ff8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1267): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3504): Binding Chromium to main looper Looper (main, tid 1) {41b1fe00}
I/LibraryLoader( 3504): Expected native library version number "",actual native library version number ""
I/chromium( 3504): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3504): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4239ca20:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3504): 1102272504: getState(). Returning 12
D/PMS     (  903): acquireWL(423276a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(4244d9d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(423276a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3504): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3504): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3504): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3504): Local Branch: 
I/Adreno-EGL( 3504): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3504): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3504):                  aa63bbd948f41d15fc72f585e
W/chromium( 3504): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3504): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3504): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3504): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3504): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3504): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3504): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3504): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3504): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3504): CordovaWebView is running on device made by: HTC
,W/AwContents( 3504): nativeOnDraw failed; clearing to background color.
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
W/ResourceType( 3504): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3504): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b66c68, mServedView=org.apache.cordova.engine.SystemWebView{41b2cb18 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  903): Disable input method client, pid=1267
I/InputMethodManagerService(  903): Enable input method client, pid=3504
W/AwContents( 3504): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +258ms
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  903): releaseWL(41e40a88): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/chromium( 3504): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3504): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3504): Set native->JS mode to OnlineEventsBridgeMode
W/dalvikvm( 3481): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/jxcore_app_log( 3504): JniHelper::setJavaVM(0x415f3048), pthread_self() = 1658087584
D/JX-Cordova( 3504): jxcore cordova android initializing
W/jxcore-log( 3504): Initializing JXcore engine
W/jxcore-log( 3504): JXcore engine is ready
W/jxcore-log( 3504): Starting JXcore engine
W/jxcore-log( 3504): Platform android
W/jxcore-log( 3504): 
W/jxcore-log( 3504): Process ARCH arm
W/jxcore-log( 3504): 
I/jxcore-log( 3504): JXcore Cordova bridge is ready!
I/jxcore-log( 3504): 
W/jxcore-log( 3504): JXcore engine is started
E/jxcore  ( 3504): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3504): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:267:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
W/dalvikvm( 3481): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WIFI_ICON( 1112): WifiActivity: 0
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/dalvikvm( 3481): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/FbInjectorInitializer( 3481): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
W/fb4a(:<default>):StaticBindingVerifier( 3481): Verify
D/WifiService(  903): New client listening to asynchronous messages
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3481/10026)
W/fb4a(:<default>):BaseAnalyticsConfig( 3481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
W/fb4a(:<default>):BaseAnalyticsConfig( 3481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
I/dalvikvm-heap( 3481): Grow heap (frag case) to 9.510MB for 73240-byte allocation
D/Process (  903): killProcessQuiet, pid=3234
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3234:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/PMS     (  903): acquireWL(4252d370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2232 10028 null
I/ActivityManager(  903): Recipient 3234
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): acquireWL(426755f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2232 10028 null
D/PMS     (  903): releaseWL(4252d370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
D/GCM     ( 1361): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): releaseWL(426755f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/AutoSetting( 1390): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3560 uid=10078 gids={50078, 3003, 5012}
D/AutoSetting( 1390): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1390): Util - check NLP state, Allowned:false, Enabled:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1390/10053)
D/AutoSetting( 1390): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1390): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1390): service - handleMessage() setting current location null
D/AutoSetting( 1390): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1390): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1390/10053)
,W/fb4a(:<default>):UserScope( 3481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3481): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 3481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 3560): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3560): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3560): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3560): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3575 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3248
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3248:com.android.smith/u0a163 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3560/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3560/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (3560/10078)
D/PMS     (  903): acquireWL(424e43a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2232 10028 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/PMS     (  903): acquireWL(42767b20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2232 10028 null
D/PMS     (  903): releaseWL(424e43a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,I/CheckinService( 2232): Preparing to send checkin request
,I/EventLogService( 2232): Accumulating logs since 1452275680644
,W/EventLogAggregator( 2232): Unknown tag: install_package_attempt
W/EventLogAggregator( 2232): Unknown tag: snet
,W/EventLogAggregator( 2232): Unknown tag: snet_gcore
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3593 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3261
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3261:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3248
,I/GoogleHttpClient( 2232): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2232): Using GMS GoogleHttpClient
,I/dalvikvm-heap( 3481): Grow heap (frag case) to 9.961MB for 84664-byte allocation
E/dalvikvm( 3481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3481): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3481): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3481): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/WifiService(  903): New client listening to asynchronous messages
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 3593): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 3593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  903): Recipient 3261
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.youtube (pid 3261): Died!
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 3481): Grow heap (frag case) to 9.979MB for 28144-byte allocation
E/dalvikvm( 3481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3481): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3481): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3481): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3481): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3481): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2232/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=50 [2][1][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2232/10028)
,I/dalvikvm-heap( 3481): Grow heap (frag case) to 10.018MB for 39954-byte allocation
,I/dalvikvm-heap( 3481): Grow heap (frag case) to 10.094MB for 79892-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3593/10151)
,V/WebViewChromiumFactoryProvider( 3593): Binding Chromium to main looper Looper (main, tid 1) {41b22d18}
,I/LibraryLoader( 3593): Expected native library version number "",actual native library version number ""
,I/chromium( 3593): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3593): Initializing chromium process, renderers=0
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,E/AudioManagerAndroid( 3593): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(42693570): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(42693570): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3593): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3593): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3593): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3593): Local Branch: 
I/Adreno-EGL( 3593): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3593): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3593):                  aa63bbd948f41d15fc72f585e
,I/GoogleHttpClient( 1361): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1361): Using GMS GoogleHttpClient
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NSApplication( 3593): Starting up...
I/NotificationStore( 1361): System rebooted after Notification storage file was last written
,I/NotificationStore( 1361): Deleting the file
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3593/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (3593/10151)
,I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3631 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3205
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3205:com.android.settings/1000 (adj 15): empty #17
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2232): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b5ea88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/dalvikvm-heap( 3481): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 7 4 12
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3481/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42554610 u0 ReceiverList{424670a8 3481 com.facebook.katana/10026/u0 remote:423ddd58}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42554610 u0 ReceiverList{424670a8 3481 com.facebook.katana/10026/u0 remote:423ddd58}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{428030e8 u0 ReceiverList{42803088 3481 com.facebook.katana/10026/u0 remote:426e0428}}
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3644 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3481/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3481/10026)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (3481/10026)
,I/ActivityManager(  903): Recipient 3205
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(4240c920): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(4238ee18): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/PMS     (  903): acquireWL(42639440): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): releaseWL(42639440): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1420): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(42672cb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
D/PMS     (  903): releaseWL(42672cb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MultiDex( 3644): install
,I/MultiDex( 3644): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 3644): loading existing secondary dex files
,I/MultiDex( 3644): load found 1 secondary dex files
,I/MultiDex( 3644): install done
,I/ProviderInstaller( 3644): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(427d88c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3631 10160 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/PMS     (  903): acquireWL(427d8670): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3631 10160 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/PMS     (  903): releaseWL(427d88c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/AlertReceiver( 3394): beginStartingService
,I/GoogleHttpClient( 3644): Falling back to old SSLCertificateSocketFactory
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(427b1558): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3394 10013 null
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(427b06e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2232 10028 null
D/PMS     (  903): releaseWL(427b06e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 3394): start to updateAlertNotification!
,I/SocialFeedProvider( 1267): +disConnect socialManager
,I/SocialFeedProvider( 1267): disconnect socialManager
,I/SocialFeedProvider( 1267): -disConnect socialManager
,D/AlertService( 3394): No fired or scheduled alerts
,D/HtcAlertUtils( 3394): -- cancelReminderNotification --
,D/HtcAlertUtils( 3394): broadcastExistReminder!
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(427d8670): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
D/PMS     (  903): releaseWL(427b1558): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 3394): stopSelfResult true
,D/Process (  903): killProcessQuiet, pid=3314
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 3314:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/libc    ( 3644): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3644): [NET] getaddrinfo-,err=8
D/libc    ( 3644): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3644): [NET] getaddrinfo-, 1
D/libc    ( 3644): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b273 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,W/WeatherUtility( 3439): can't get weather sync account
I/ActivityManager(  903): Recipient 3314
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3682 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 1112): request cur loc, but there is no sys cur
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 229
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3644): [NET] getaddrinfo_proxy-, success
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/dalvikvm-heap( 3631): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
,W/WeatherRequest( 3439): request cur loc, but there is no sys cur
,W/Settings( 3439): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1267): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1267): com.htc.widget.weatherclock 0 6 17
,D/PMS     (  903): acquireWL(425a7d30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3682 10070 null
,D/PMS     (  903): acquireWL(425a6fe0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3682 10070 null
,D/PMS     (  903): releaseWL(425a7d30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3697 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3682): update TASK shortcut>
,I/TodoTaskNotifyService( 3682): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    ( 3644): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3644): [NET] getaddrinfo-,err=8
,I/TodoTaskNotifyService( 3682): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3682): stopSelfResult true
D/PMS     (  903): releaseWL(425a6fe0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WorldClock.Global( 3697): isHtcDevice = true
,I/WorldClock.Global( 3697): isHtcDevice = true
W/ContextImpl( 3190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3697): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3697): Cancel any alarm from alarm manager
,I/ActivityManager(  903): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3712 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 3697): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1112): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/PMS     (  903): acquireWL(4207ade8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  903): releaseWL(4207ade8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/Process (  903): killProcessQuiet, pid=3027
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3027:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,D/TimeService( 3712): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452276633948
,I/ActivityManager(  903): Recipient 3027
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3333
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3333:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3333
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3727 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3727): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3727): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3727): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(423a41d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3682 10070 null
,D/PMS     (  903): acquireWL(42554b20): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3682 10070 null
,D/PMS     (  903): releaseWL(423a41d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3682): update TASK shortcut>
,I/TodoTaskNotifyService( 3682): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(42554b20): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,W/NotifyReceiver( 3682): stopSelfResult true
,D/Process (  903): killProcessQuiet, pid=3366
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3744 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  903): Killing 3366:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3366
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3756 uid=10081 gids={50081, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=3412
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  903): killProcessQuiet, pid=3378
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 2232): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2232): Unauthorized to start the main service
I/ActivityManager(  903): Killing 3412:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
I/ActivityManager(  903): Killing 3378:com.htc.contacts/u0a41 (adj 15): empty #18
,I/ActivityManager(  903): Recipient 3412
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  903): Schedule to resend BroadcastRecord{425a0428 u0 com.htc.mms.DB_CHANGE callingPid=1241 callingUid=1001} for ResolveInfo{425a02c0 com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent m=0x108000} of com.htc.widget.hmsproc1
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3768 uid=10038 gids={50038}
,D/SMSBackup( 3425): Got a database change event
,D/Process (  903): killProcessQuiet, pid=3454
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3781 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  903): Killing 3454:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3454
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.music (pid 3454): Died!
,I/ActivityManager(  903): Recipient 3378
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3781): create image Cache, size: 31457280.
I/ImageRamCache( 3781): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3781): create image Cache, size: 12582912.
,D/PMS     (  903): releaseWL(4244d9d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/FeedSettings( 3781): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3781): GroupBudget 0.500000 0.380000
I/FeedSettings( 3781): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3781): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3781): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3781): loadGridSize() with Alternative
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/CustomHighlightReceiver( 3781): [custom highlight] onReceive
,W/ContextImpl( 3481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/CustomHighlightService( 3781): [custom highlight] onHandleIntent
,D/NewsDB  ( 3781): set custom highlight []
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/CustomHighlightService( 3781): [custom highlight] set tags 
,D/Process (  903): killProcessQuiet, pid=3481
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 3481:com.facebook.katana/u0a26 (adj 15): empty #17
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/MessagingShortcutReceiver( 2799): keep hiding shortcut bubble
D/MessagingShortcut( 2799): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2799): After query: 0
D/MessagingShortcut( 2799): mPresentUnreadCount: -1
,D/MessagingShortcut( 2799): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2799): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderNotification, total:0
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3682): update TASK shortcut>
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1241): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3800 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  903): Recipient 3481
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(4257a780): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): acquireWL(4264fcf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): releaseWL(4257a780): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(4264fcf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/Adreno-EGL( 3644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3644): Local Branch: 
I/Adreno-EGL( 3644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3644):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=7 [27][2][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3815 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  903): sending alarm PendingIntent{41be6198: PendingIntentRecord{425b80e8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452276634506, Int=0
,D/MessagingNotification( 2799): New incoming message, can't cancel notification now
I/SocialManager[SocialBiLogHelper]( 3781): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3781): last commit ulog time 1452231060566
,I/SocialManager[SocialBiLogHelper]( 3781): skip commit this time
,D/MessagingNotification( 2799): newMsgCnt: 0, false
,V/AlarmManager(  903): sending alarm PendingIntent{41de02a0: PendingIntentRecord{424b5920 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58181, Int=0
,D/MdScBoot( 3800): [758.1.] 40@-191029
,D/Process (  903): killProcessQuiet, pid=3560
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 3560:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  903): killProcessQuiet, pid=3575
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  903): Killing 3575:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3575
,D/MtpReceiver( 2467): [MTP][MtpReceiver][onReceive]+
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpReceiver( 2467): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2467): [MTP][handleMessage][startService]
D/MtpReceiver( 2467): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2467): [MTP][handleMessage]-
,D/MtpService( 2467): [MTP] startForeground
,I/RemoteViews( 1112): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1112): com.android.providers.media 1 1 10
,D/Process (  903): killProcessQuiet, pid=3593
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3831 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  903): Killing 3593:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/RemoteViews( 1112): com.android.providers.media (false,0)
D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1112): com.android.providers.media 4 1 15
D/MtpService( 2467): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2467): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  903): acquireWL(423dd128): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3631 10160 null
,I/ActivityManager(  903): Recipient 3593
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpService( 2467): [isMtpConnected] connected: true
,I/ActivityManager(  903): Recipient 3560
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3831): Loading default preferences
,W/Resources( 3831): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 3831): Overriding preferences with custom values
,D/SyncApplication( 3831): Updating preferences succeeded
,E/SyncApplication( 3831): Application created.
D/VolumeInfo( 3831): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3831): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3831): Found 0 mount point(s)
,V/VolumeInfo( 3831): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3831): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3831): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3831): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3831): getNewCalendarAuthority()...
,D/SyncApplication( 3831): enableAppOperation()+
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3831, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3831, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 3831): enableAppOperation()-
,D/HTCUtilities( 3831): isNeorSinged() + 
,D/HTCUtilities( 3831): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3831): isNeorSinged() return false
D/CDMountReceiver( 3831): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3831): USB connected to PC
D/PMS     (  903): releaseWL(423dd128): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/FOTAReceiver( 3831): onReceive() enter 
,D/FOTAReceiver( 3831): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3854 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=3394
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3394:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3394
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3854): -onCreate()
,V/Settings:HtcSettingsApplication( 3854): [3854/3854] onCreate()
,D/TetherSettings( 3854): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3854): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3854): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3854): Cust_ConnectToPC   : spcsc>false
D/        ( 3854): Cust_ConnectToPC   : IPT>true
,D/        ( 3854): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3854): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3854): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3854): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3854): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3854): Cust_ConnectToPC   : spcsc>false
D/        ( 3854): Cust_ConnectToPC   : IPT>true
D/        ( 3854): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3854): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3854): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3854): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3854): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3854): usb_cable_connect = 1
D/SmartNS_Utility( 3854): usb_denied = 0
I/SmartNS_NSReceiver( 3854): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3854): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3854): onReceive:com.htc.intent.action.USB_CONNECT2PC
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (3644/10028)
,W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3854): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3854): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3854):  defaultType:0
I/SmartNS_PSService( 3854): fail notificaiton:false
D/SmartNS_Utility( 3854): usb_cable_connect = 1
D/SmartNS_Utility( 3854): usb_denied = 0
I/SmartNS_PSService( 3854): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3854/1000)
,D/SmartNS_Utility( 3854): usb_cable_connect = 1
D/SmartNS_Utility( 3854): usb_denied = 0
,I/SmartNS_PSService( 3854): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  903): bSetPropertyMultiRAB:false
,I/RemoteViews( 1112): com.android.settings (true,33751552)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3854/1000)
,I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews.Performance( 1112): com.android.settings 2 1 10
I/Adreno-EGL( 3644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3644): Local Branch: 
I/Adreno-EGL( 3644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3644):                  aa63bbd948f41d15fc72f585e
I/HtcModeClient( 1487): handler message = 4011
E/HtcModeClient( 1487): Check connection and retry 6 times.
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 3854): usb_cable_connect = 1
,D/SmartNS_Utility( 3854): usb_denied = 0
,I/ActivityManager(  903): Resuming delayed broadcast
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherUtility( 3439): can't get weather sync account
I/SmartNS_PSService( 3854): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3854): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews( 1112): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1112): com.android.settings 1 2 10
,I/ActivityManager(  903): Resuming delayed broadcast
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1267): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1267): com.google.android.googlequicksearchbox 0 0 5
,I/Adreno-EGL( 3644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3644): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3644): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3644): Local Branch: 
I/Adreno-EGL( 3644): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3644): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3644):                  aa63bbd948f41d15fc72f585e
,W/WeatherRequest( 3439): request cur loc, but there is no sys cur
,I/ActivityManager(  903): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
W/Settings( 3439): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1267): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1267): pl.k2.droidoaudioteka 1 1 8
,I/ActivityManager(  903): Resuming delayed broadcast
,D/SMSBackup( 3425): Got a database change event
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1267): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  903): acquireWL(4235d218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,I/RemoteViews.Performance( 1267): com.htc.widget.weatherclock 1 7 17
D/PMS     (  903): releaseWL(4235d218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  903): acquireWL(41e06500): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1487 10014 null
I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/WIFI_ICON( 1112): WifiActivity: 1
,W/Settings( 3644): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): releaseWL(41e06500): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=65 rxSum=72} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19185 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19186 delay=15s
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  903): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  903): Resuming delayed broadcast
,I/CheckinTask( 2232): Sending checkin request (9074 bytes)
W/ActivityThread( 2232): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/libc    ( 2232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2232): [NET] getaddrinfo-,err=8
D/libc    ( 2232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2232): [NET] getaddrinfo-, 1
,D/libc    ( 2232): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =918b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,D/PMS     (  903): acquireWL(41ed3470): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2232 10028 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 159
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2232): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2232): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2232): [NET] getaddrinfo-,err=8
,D/PMS     (  903): releaseWL(41ed3470): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  903): sending alarm PendingIntent{423912d8: PendingIntentRecord{425b56f0 com.google.android.gms startService}}, i=null, t=0, cnt=17102, w=84918423, Int=84918423
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,I/AdsMeasurementBroadcastReceiver( 2232): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2232): Unauthorized to start the main service
,D/SnetService( 2232): snet destroyed
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3889 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3889): call getInstance()
I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3889): MY_DEBUG = false
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42823050 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42637de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3889 1000 null
,W/WeatherUtility( 1112): can't get weather sync account
,D/WeatherUtility( 1390): Weather sync is On
,D/WSP     ( 1390): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  903): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3906 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3439): can't get weather sync account
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/PMS     (  903): acquireWL(424dbd20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  903): releaseWL(424dbd20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/WeatherRequest( 3439): request cur loc, but there is no sys cur
,W/Settings( 3439): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1267): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1267): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1267): com.htc.widget.weatherclock 2 7 17
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2232/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=13 [15][2][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2232/10028)
,W/BatSI   (  903): Couldn't get kernel wake lock stats
W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BatSI   (  903): Couldn't get kernel wake lock stats
,I/RemoteViews( 1112): com.google.android.gms (false,0)
D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 3 12
,W/CheckinRequestBuilder( 2232): awaiting user notification for token
,I/CheckinTask( 2232): Sending checkin request (2419 bytes)
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3924 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3697
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3697:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/WIFI_ICON( 1112): WifiActivity: 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/MusicStore( 3924): Database version: 95
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  903): Recipient 3697
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3924): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3924): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3924): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3924, uid=10154, userID:0
,D/PMS     (  903): acquireWL(42650760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  903): releaseWL(42650760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2232/10028)
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2232/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [5][0][0]
D/MediaRouterService(  903): Client com.google.android.music (pid 3924): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/MediaRouter( 3924): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 3924): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (3924/10154)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1152): Change stage from stage0 to stage3
I/wpa_supplicant( 1152): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1361): GoogleAccountDataService.getToken()
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/MediaRouter( 3924): getSelectedRoute
D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2232): awaiting user notification for token
,I/NetworkMonitor( 3924): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,I/RemoteViews( 1112): com.google.android.gms (false,0)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3924/10154)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/RemoteViews.Performance( 1112): com.google.android.gms 1 3 12
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/ActivityManager(  903): Resuming delayed broadcast
,D/DFPI.PIReciver( 3727): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3727): onHandleIntent
,I/DFPI.ApkInstallService( 3727): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3727): check CID = HTC__032
,I/DFPI.ApkInstallService( 3727): There is no Demo.apk in sd card or phone storage
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3924, uid=10154, userID:0
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3190
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3190:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3190
,I/ActivityManager(  903): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3947 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/CheckinTask( 2232): Checkin success: https://android.clients.google.com/checkin (2 requests sent)
,W/GoogleHttpClient( 2232): Unable to close GMS GoogleHttpClient
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,I/ActivityManager(  903): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/PMS     (  903): releaseWL(42767b20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2232): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e36fa8 that was originally bound here
E/ActivityThread( 2232): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e36fa8 that was originally bound here
E/ActivityThread( 2232): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2232): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2232): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2232): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2232): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2232): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2232): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2232): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2232): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2232): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2232): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2232): 	at bks.a(SourceFile:298)
E/ActivityThread( 2232): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2232): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2232): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3947/10051)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3947/10051)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{427efed8 u0 ReceiverList{427efe78 3947 com.htc.musicenhancer/10051/u0 remote:427efb80}}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3947): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,V/AlarmManager(  903): sending alarm PendingIntent{423aa8d8: PendingIntentRecord{423bf0f0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452276636862, Int=0
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3966 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3712
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3712:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/ActivityManager(  903): Recipient 3712
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  903): mEventCount = 450
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,D/AutoSetting( 1390): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1390): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1390): service - requestNLP() NetworkLocationProvider not enabled
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/Process (  903): killProcessQuiet, pid=3744
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3744:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3744
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2232): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  903): acquireWL(427b0078): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(427b0078): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 2232): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2232, uid=10028, userID:0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:121, mTXpacketCount:60, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3987 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3756
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3756:com.htc.stock:remote/u0a81 (adj 15): empty #17
,D/Process (  903): killProcessQuiet, pid=2799
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1390): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1390): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Killing 2799:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3756
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4003 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/PMS     (  903): releaseWL(42637de0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4003, uid=10073, userID:0
,I/ActivityManager(  903): Recipient 2799
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4003): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4003/10073)
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4003/10073)
,D/Finsky  ( 4003): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4003): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4003): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4003, uid=10073, userID:0
,D/Process (  903): killProcessQuiet, pid=3682
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_ADDED
,D/Finsky  ( 4003): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4003): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  903): Killing 3682:com.htc.task/u0a70 (adj 15): empty #17
,I/IcingCorporaProvider( 2919): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4036 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  903): acquireWL(4249b3f0): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/Finsky  ( 4003): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  903): Delaying start of: ServiceRecord{42610428 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/DeviceManagement( 4036): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4036 dbg=false s=true
,I/DeviceManagement( 4036): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  903): killProcessQuiet, pid=3800
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/ActivityManager(  903): Killing 3800:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3800
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3682
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): releaseWL(4249b3f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Finsky  ( 4003): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  903): acquireWL(42574e28): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(42574e28): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4053 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  903): acquireWL(42595c40): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(42595c40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42519b30): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): releaseWL(42519b30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(426a3d78): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(426a3d78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(426f1e68): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(426f1e68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(426731b0): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(426731b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(425d65c8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(425d65c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42367808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42367808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,D/PMS     (  903): acquireWL(424c48d8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(424c48d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/PMS     (  903): acquireWL(4259e790): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(4259e790): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(426e8fa0): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(426e8fa0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2919): Copying FileAsset 0x5c7a7f38 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2919): UpdateCorporaTask done [took 456 ms] updated apps [took 456 ms] 
,I/ActivityManager(  903): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4070 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4053/10100)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4053/10100)
,W/GAV2    ( 4053): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/htcbackup-core( 4070): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4070): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4070): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 4036): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4036): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.usage, com.android.keychain, com.android.location.fused, com.htc.checkinprovider, com.htc.drive.activator, com.htc.htcpowermanager, com.htc.android.htcsetupwizard, com.htc.lockscreen, com.htc.backupreset, com.android.CSDFunctionG, com.qualcomm.privinit, com.htc.backup, com.android.providers.settings, com.htc.android.htcloglevel, com.htc.home.personalize, com.qualcomm.timeservice, com.android.settings, com.htc.feedback, com.htc.smartdim, com.htc.cirmodule, com.android.inputdevices, com.htc.guide, com.htc.autobot.cargps.provider, android, com.htc.mirrorlinkserver]
,I/DeviceManagement( 4036): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4094 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=3781
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3781:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/DeviceManagement( 4036): WorkflowService: Starting workflow service
I/DeviceManagement( 4036): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b5a7c0] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4036): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4036): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  903): Recipient 3781
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4036): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4036): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 4094):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  903): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,V/AlarmManager(  903): sending alarm PendingIntent{4241f480: PendingIntentRecord{426f3480 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452276638887, Int=0
,W/GAV2    ( 4053): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(4267a840): PARTIAL_WAKE_LOCK  AsyncService 0x1 3631 10160 null
I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
D/PMS     (  903): releaseWL(4267a840): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DeviceManagement( 4036): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4003): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4003): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 4036): SessionStateController: Checking invariants...
,D/Settings:HtcWirelessFeatureFlags( 3854): id/is att sku: 99/false
,W/SystemReader( 3854): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3854): Cannot find support_harman, use default value instead
,W/SystemReader( 3854): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3854): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3854): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3854): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3854): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]support         :false
,W/FingerprintManager( 3854): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3854): isSupportVoWifi: null
,I/DeviceManagement( 4036): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4036): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b5a7c0]
E/ActivityThread( 3854): Failed to find provider info for com.htc.vowifi
,I/DeviceManagement( 4036): WorkflowService: Stopping workflow service
,D/DFPI.PIReciver( 3727): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3727): onHandleIntent
I/DFPI.ApkInstallService( 3727): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3727): check CID = HTC__032
,I/DFPI.ApkInstallService( 3727): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Resuming delayed broadcast
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3854): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3854): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3854): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportRecentAppsButton]support         :false
I/ActivityManager(  903): Resuming delayed broadcast
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3854): [supportHomeButton]support         :false
W/FingerprintManager( 3854): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 3854): isSupportVoWifi: null
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  903): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3854): Failed to find provider info for com.htc.vowifi
D/DFPI.PIReciver( 3727): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3727): onHandleIntent
I/DFPI.ApkInstallService( 3727): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3727): check CID = HTC__032
I/DFPI.ApkInstallService( 3727): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4003): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4003): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4003): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,I/MediaStoreImporter( 3924): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4128 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3815
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3815:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3815
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  903): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4141 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3831
,I/ActivityManager(  903): Killing 3831:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  903): Recipient 3831
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,I/EASAppSvc( 4141): [ NA ]- onCreate()
,I/EASAppSvc( 4141): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 4128): put()
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (4141/10063)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (4141/10063)
,I/ActivityManager(  903): Resuming delayed broadcast
,D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (4141/10063)
,I/EASAppSvc( 4141): [ NA ]- onDestroy()
,I/EASAppSvc( 4141): [ NA ]> uninitEASService
,I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/EASRequestController( 4141): [ NA ]release
,D/TelephonyReceiver( 1241): bind: true
,D/DFPI.PIReciver( 3727): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/EASAppSvc( 4141): [ NA ]< uninitEASService
I/EASAppSvc( 4141): [ NA ]- onCreate()
,I/ActivityManager(  903): Resuming delayed broadcast
,I/EASAppSvc( 4141): [ NA ]> onUpgrade: version = 63
I/ActivityManager(  903): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=4171 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
I/DFPI.ApkInstallService( 3727): onHandleIntent
,I/DFPI.ApkInstallService( 3727): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3727): check CID = HTC__032
,I/DFPI.ApkInstallService( 3727): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.android.mail (4141/10063)
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.htc.android.mail (4141/10063)
,D/Process (  903): killProcessQuiet, pid=3768
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ORMLib  ( 4128): put()
D/ConnectivityService(  903): getNetworkInfo networkType=55 called by com.htc.android.mail (4141/10063)
I/ActivityManager(  903): Killing 3768:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  903): Recipient 3768
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/EASAppSvc( 4141): [ NA ]- onDestroy()
,I/EASAppSvc( 4141): [ NA ]> uninitEASService
D/MessageFrequencyProvider( 4171): onCreate
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/EASRequestController( 4141): [ NA ]release
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/EASAppSvc( 4141): [ NA ]< uninitEASService
,I/ActivityManager(  903): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4192 uid=10067 gids={50067, 3003, 5012},
D/GenericMessagesProvider( 4171): query uri: content://htc-messages/wappush/count
V/GetPrviateResource( 4171): GetPrviateResource
V/GetPrviateResource( 4171): GetPrviateResource
E/SQLiteLog( 4171): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 4171): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4171): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 4171): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 4171): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 4171): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 4171): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4171): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4171): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4171): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 4171): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 4171): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 4171): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
W/System.err( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,W/System.err( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 4171): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4171): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4171): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4171): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 4171): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 4171): 	at dalvik.system.NativeStart.run(Native Method)
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3425
,I/ActivityManager(  903): Killing 3425:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  903): Recipient 3425
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 4128): put()
,D/MessageCustFlag( 4171): sense_version=6.0
,D/BTAccessoryUtil( 4171): createReceiver
,D/BTAccessoryUtil( 4171): registerReceiver return intent = null
D/MessageCustFlag( 4171): sku_id=99
,W/SystemReader( 4171): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4171): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4171): networkCode: 
,D/MessageCustFlag( 4171): sku_id=99
D/MmsConfig( 4171): SIE smsPri: null
,D/MmsConfig( 4171): networkCode: 
,D/HtcTelephonyCapability( 4171): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4171): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4171): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4171): Cannot find qct_8960_interface, use default value instead
,I/MediaStoreImporter( 3924): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3889
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3889:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  903): acquireWL(424ba340): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1487 10014 null
I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  903): releaseWL(424ba340): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  903): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4212 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  903): killProcessQuiet, pid=3439
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/TelephonyReceiver( 1241): bind: false
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
I/ActivityManager(  903): Killing 3439:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3439
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4225 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3889
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 7 times.
,W/GAV2    ( 4225): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  903): acquireWL(427de718): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(427de718): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/PMS     (  903): acquireWL(426a84f8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/Process (  903): killProcessQuiet, pid=3987
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3987:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3987
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): releaseWL(426a84f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/Gmail   ( 4225): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4225): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4225): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4225): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1112): com.htc.updater (true,33751552)
D/NotificationService(  903): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41f0eb58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.updater 1 9 1 10
I/ActivityManager(  903): Resuming delayed broadcast
,I/RemoteViews( 1112): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b24948 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.updater 2 8 0 10
I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.GmailReceiver
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/NotifUtils( 4225): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 4225): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4266 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  903): Killing 4053:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4053
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4053
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,E/dalvikvm( 4266): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4266): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/Babel   ( 4266): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4266): MmsConfig.loadMmsSettings
,E/dalvikvm( 4266): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4266): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4266): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 4171): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4171): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4266): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4266): MmsConfig.loadFromDatabase
,E/Babel   ( 4266): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4266): MmsConfig.loadFromResources
,E/Babel   ( 4266): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4266): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4266, uid=10111, userID:0
,W/Settings( 4266): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4266, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4266, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4266, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4266, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4266, uid=10111, userID:0
D/PMS     (  903): acquireWL(42314bc0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4266 10111 null
I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4266): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  903): releaseWL(42314bc0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42439f28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4266 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  903): releaseWL(42439f28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(41ea24c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4266 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  903): releaseWL(41ea24c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4266/10111)
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4266): UserRecoverableAuthException.
,E/Babel   ( 4266): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4266): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4266): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4266): Error getting auth token
,E/Babel   ( 4266): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4266): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4266): Account registration failedRedacted-21
E/Babel   ( 4266): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4266): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4266): Account setup failed with error state:106 account:Redacted-21,
,I/Babel   ( 4266): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.talk (4266/10111)
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Babel   ( 4266): Unexpected exception while authenticating.
,E/Babel   ( 4266): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4266): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4266): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4266): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4266): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4266): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4266): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4266): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4266): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41de5800 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 6 3 12
,D/Messaging( 4171): mNeedToUpdateDate2 start
,D/MmsConfig( 4171): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4171): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4171): 
D/MmsAsyncWorkHandler( 4171): HM tk = 20001
,D/ReportIndicatorCache( 4171): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4171): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b27430
,I/Messaging( 4171): mccmnc> 
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4171): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4171): [DraftCache/1] refresh
,D/MmsConfig( 4171): networkCode: 
,D/Messaging( 4171): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4171): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4171): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4171): createReceiver
,D/MessageCustFlag( 4171): sense_version=6.0
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/Jerry   ( 4171): start to preload cursor >>>>>>>
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4171): mNeedToUpdateDate2: false
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 4171): Reset downloading state: 0
V/MmsSystemEventReceiver( 4171): TransactionService is going to be woken up.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
I/ActivityManager(  903): Delaying start of: ServiceRecord{42489de0 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/DraftCache( 4171): [DraftCache/427] rebuildCache
,D/MmsSmsV2Provider( 1241):  phoneType = -1
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4171): ViewCache CreatePreload
,D/Messaging( 4171): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4171): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Cust_MMSMS( 4171): _has_set_default_values_2=true
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1241): URI_DRAFT
,D/DraftCache( 4171): hasDraft() = false mNeedNotifyChange = true
D/MsgPreferenceUtils( 4171): def_index: 0
D/DraftCache( 4171): [DraftCache/427] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4171): 
D/MmsAsyncWorkHandler( 4171): HM tk = 20002
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1241): sku_id=99
,D/MsgPreferenceUtils( 4171): globalIndex = 1
D/MsgPreferenceUtils( 4171): phone state: true
D/MsgPreferenceUtils( 4171): sd state: false
,D/MsgPreferenceUtils( 4171): vIndex = 0
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1241): sku_id=99
,V/AlarmManager(  903): sending alarm PendingIntent{42689730: PendingIntentRecord{427cba88 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452276642807, Int=0
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,V/TransactionService( 4171): 1-Creating TransactionService
V/TransactionService( 4171): onStartCommand: 1
,D/MmsSystemEventReceiver( 4171): unRegisterForConnectionStateChanges
V/TransactionService( 4171): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4171): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1241): device_type: 1
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1152): Change stage from stage3 to stage0
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/TransactionService( 4171): Force set service start id to 1
V/TransactionService( 4171): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4171): unRegisterForConnectionStateChanges
,D/TransactionService( 4171): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/TransactionService( 4171): Destroying TransactionService
,D/Process (  903): killProcessQuiet, pid=4070
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/TransactionService( 4171): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/PackageBroadcastService( 2232): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  903): Killing 4070:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/ConnectivityService(  903): Done.
D/ConnectivityService(  903): Setting timer for 720seconds
,I/PeopleContactsSync( 2232): CP2 sync disabled
I/ActivityManager(  903): Recipient 4070
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2232, uid=10028, userID:0
D/PMS     (  903): acquireWL(42318dd8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
D/PMS     (  903): releaseWL(42318dd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1390): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1390): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/IcingCorporaProvider( 2919): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2919): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(41fb4058): PARTIAL_WAKE_LOCK  AsyncService 0x1 3631 10160 null
,D/PMS     (  903): releaseWL(41fb4058): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(426b02b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4128 10070 null
,D/PMS     (  903): acquireWL(4231c3f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4128 10070 null
D/PMS     (  903): releaseWL(426b02b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4128): java.lang.NullPointerException
,W/System.err( 4128): java.lang.NullPointerException
W/System.err( 4128): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
I/ActivityManager(  903): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
W/System.err( 4128): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4128): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4128): stopSelfResult true
D/PMS     (  903): releaseWL(4231c3f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(426b0910): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4128 10070 null
D/PMS     (  903): acquireWL(42393380): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4128 10070 null
I/ActivityManager(  903): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 4128): java.lang.NullPointerException
,W/System.err( 4128): java.lang.NullPointerException
W/System.err( 4128): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4128): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4128): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4128): stopSelfResult true
D/PMS     (  903): releaseWL(426b0910): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): releaseWL(42393380): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(426ab860): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4128 10070 null
D/PMS     (  903): acquireWL(4274c898): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4128 10070 null
E/TodoTaskNotifyService( 4128): java.lang.NullPointerException
W/System.err( 4128): java.lang.NullPointerException
W/System.err( 4128): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4128): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4128): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4128): stopSelfResult true
I/ActivityManager(  903): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  903): releaseWL(426ab860): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): releaseWL(4274c898): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): acquireWL(423ac038): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(425475d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(423ac038): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  903): releaseWL(425475d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GCM     ( 1361): GCM config loaded
,I/WSP     ( 1390): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1390): Weather sync is On
,I/WSP     ( 1390): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 08 20:10:43 CET 2016
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1390/10053)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1390/10053)
,D/PMS     (  903): acquireWL(42117c88): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1390 10053 null
,I/SensorManager(  903): mEventCount = 600
,W/MediaManager( 3906): [DualLensScanUtil]	mmpCursor count is 0
,V/AlarmManager(  903): sending alarm PendingIntent{42380200: PendingIntentRecord{42808418 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452276644661, Int=0
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 8 times.
,I/GAV2    ( 4225): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4266): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 4128): update TASK shortcut>
,D/Process (  903): killProcessQuiet, pid=4036
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4036:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4036
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/PMS     (  903): acquireWL(426efe58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/PMS     (  903): releaseWL(426efe58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 9 times.
,V/AlarmManager(  903): sending alarm PendingIntent{41b4bd88: PendingIntentRecord{42485e68 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=73836, Int=0
,D/HABCtrl (  903): TPE algorithm. remove timeout.
,D/HABCtrl (  903): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
,I/CalendarProvider2( 1487): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1487): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(425353e0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3924 10154 null
,I/ActivityManager(  903): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3924, uid=10154, userID:0
,I/MusicLeanback( 3924): Conditions not met for autocaching.
,I/MusicLeanback( 3924): Stop autocaching.
D/PMS     (  903): releaseWL(425353e0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4367 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4367): Loading default preferences
,W/Resources( 4367): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 4367): Overriding preferences with custom values
,D/SyncApplication( 4367): Updating preferences succeeded
,E/SyncApplication( 4367): Application created.
D/VolumeInfo( 4367): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4367): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4367): Found 0 mount point(s)
,V/VolumeInfo( 4367): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4367): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4367): getNewCalendarAuthority()...
D/VolumeInfo( 4367): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4367): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4367): enableAppOperation()+
,D/SyncApplication( 4367): enableAppOperation()-
,D/HTCUtilities( 4367): isNeorSinged() + 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4367, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4367, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4367): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4367): isNeorSinged() return false
,D/CDMountReceiver( 4367): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4367): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4367): enable CD Auto-mount: true
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4367): enable auto-mount
,D/HTCUtilities( 4367): enable auto-mount
,I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
I/ActivityManager(  903): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  903): Resuming delayed broadcast
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41f1e6b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 1 17 5 11
,I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b151c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 1 11 3 16
,W/MediaManager( 3906): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 4094:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4094
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/ActivityManager(  903): Recipient 4094
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4389 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=84 rxSum=86} preTxRxSum={txSum=65 rxSum=72}
,D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19186 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19187 delay=15s
D/PMS     (  903): releaseWL(4260f518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CalendarApplication( 4389): onCreate
D/ProviderChangeReceiver( 4389): ---------------------------------------------------
,D/ProviderChangeReceiver( 4389): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4389): start to updateAlertNotification!
,D/Process (  903): killProcessQuiet, pid=4141
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4404 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 4141:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
I/ActivityManager(  903): Waited long enough for: ServiceRecord{42767608 u0 com.htc.musicenhancer/.EnhancerService}
,D/AlertService( 4389): No fired or scheduled alerts
,D/HtcAlertUtils( 4389): -- cancelReminderNotification --
,I/ActivityManager(  903): Recipient 4141
,D/HtcAlertUtils( 4389): broadcastExistReminder!
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4404): [4404/4404] onCreate()
W/ContextImpl( 4404): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  903): killProcessQuiet, pid=3727
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3727:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3727
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:121, mTXpacketCount:121, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  903): mEventCount = 750
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): releaseWL(42117c88): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/PMS     (  903): acquireWL(425cba30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{421d29a8: PendingIntentRecord{42376008 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452276654026, Int=0
,D/PMS     (  903): releaseWL(425cba30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4003): [1] 5.onFinished: Installation state replication succeeded.
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 10 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  903): acquireWL(425b5270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b86ae8: PendingIntentRecord{42388648 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=83644, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425b5270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 11 times.
,I/ClockThread( 1112): now=1452276660357 next=59643
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  903): mEventCount = 900
,D/AutoSetting( 1390): service - mHandler: update timezone
,D/AutoSetting( 1390): service - handleMessage() stop self
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1487): service - onCreate()
D/AutoSetting( 1390): service - handleMessage() quit looper
,D/AutoSetting( 1390): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=3966
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3966:com.htc.sdm/u0a80 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1487): service - mHandler: update timezone
I/ActivityManager(  903): Recipient 3966
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1487): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1487): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41fd21c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 1 8 3 11
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 12 times.
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  903): acquireWL(427e1ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{425dc670: PendingIntentRecord{42485e68 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=90245, Int=0
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=85 rxSum=87} preTxRxSum={txSum=84 rxSum=86}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19187 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19188 delay=15s
D/PMS     (  903): releaseWL(427e1ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:127, mTXpacketCount:121, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1487): handler message = 4011
,E/HtcModeClient( 1487): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1487): Don't start project servcice
,D/HtcModeClient( 1487): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1487): connectState: CONNECTION_READY = false
,D/SilentMusic( 1487): call stop
,D/HtcModeClient( 1487): close connection
,W/HtcModeClient( 1487): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1487): read the terminate packet, so break
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42693118 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(4245c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4245c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  903): mEventCount = 1050
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4424 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(427f0cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{420954a0: PendingIntentRecord{426fe080 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452276680302, Int=60000
,D/PMS     (  903): releaseWL(427f0cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4424): SMSBackupAgentService started
,D/SMSBackup( 4424): Checking restore status
D/SMSBackup( 4424): Restore complete
,D/SMSBackup( 4424): cancelCheckAlarm
,D/SMSBackup( 4424): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=4192
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4192:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4192
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): acquireWL(4267dac8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(4267dac8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42673f48): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(42673f48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42790df8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(42790df8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(426a6ab8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
,D/PMS     (  903): releaseWL(426a6ab8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  903): acquireWL(427d6da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{425c19d0: PendingIntentRecord{42485e68 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105252, Int=0
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=86 rxSum=88} preTxRxSum={txSum=85 rxSum=87}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19188 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19189 delay=15s
D/PMS     (  903): releaseWL(427d6da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:127, mTXpacketCount:127, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/HABCtrl (  903): TPE algorithm. schedule timeout.
,D/HABCtrl (  903): ALG=2, lsvalue=40(1th)->10(0th), last_level=1, lValue=64->64
,D/HABCtrl (  903): mTPEAlgorithmTimeoutTask: TPE algorithm. restore.
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  903): setLight #0: color=#0
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4210de60
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4210de60, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e7a90
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@4254cb10
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 376ms
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=3504
D/PMS     (  903): acquireWL(42632c60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): releaseWL(42632c60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4277cf78)
D/PMN     (  903): wakingUp
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  903): No lock screen! windowToken=null
D/PMN     (  903): onScreenOn
D/AlarmManager(  903): ACTION_SCREEN_ON
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19190 delay=15s
,D/MtpService( 2467): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2467): [MTP][onReceive]-
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
D/PMS     (  903): acquireWL(42783330): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): releaseWL(42783330): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
,D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1112): stop update clock
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): SET_SCREEN_ON:On
I/wpa_supplicant( 1152): htc_wext_set_keepalive +
I/wpa_supplicant( 1152): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1152): getPrivFuncNum +	
I/wpa_supplicant( 1152): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1152): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1152): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4447 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  903): updateScreenOn: false
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  903): acquireWL(426d2848): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4447 1000 null
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1822): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): onScreenOn: 1452276688592
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1822): onScreenOn: 1452276688592
D/PMS     (  903): acquireWL(4282e240): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
D/PMS     (  903): releaseWL(4282e240): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e7a90
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421e7a90, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@4254cb10
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): releaseWL(426d2848): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  903): acquireWL(42748a08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42748a08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19190 mDataStallAlarmIntent=PendingIntent{41e1c078: PendingIntentRecord{42485e68 android broadcastIntent}}
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/PMS     (  903): acquireWL(42351fa8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): SET_SCREEN_ON:Off
I/wpa_supplicant( 1152): htc_wext_set_keepalive +
I/wpa_supplicant( 1152): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1152): getPrivFuncNum +	
I/wpa_supplicant( 1152): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1152): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1152): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1152): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1152): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4447): getMobilePolicyEnabled, result = true
,D/Process (  903): killProcessQuiet, pid=4212
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4212:com.htc.updater/u0a84 (adj 15): empty #17
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1390): receiver - intent: android.intent.action.USER_PRESENT
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/TetherSettings( 3854): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3854): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3854): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3854): Cust_ConnectToPC   : spcsc>false
D/        ( 3854): Cust_ConnectToPC   : IPT>true
D/        ( 3854): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3854): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3854): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3854): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3854): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1390): service - onCreate()
,I/PSReceiver( 3854): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  903): Recipient 4212
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  903): updateScreenOn: false
D/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1390): service - AddressCache: using context: com.htc.Weather
,I/SmartNS_PSService( 3854): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3854): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3854):  defaultType:0
,D/PMS     (  903): releaseWL(42351fa8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/AutoSetting( 1390): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  903): request 425486f0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4447): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4447): isEpsOn(), nState = 0
D/WifiService(  903): New client listening to asynchronous messages
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4254cb10
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4254cb10, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4254cb10, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4254cb10
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4257aa28 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4257aa28 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1822): onScreenOff.
D/PMS     (  903): acquireWL(426eca50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
,D/PMS     (  903): releaseWL(426eca50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1822): onScreenOff
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1487): service - handleMessage() stop self
,D/AutoSetting( 1487): service - onDestroy() END
,D/AutoSetting( 1487): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3947
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3947:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3947
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1390): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1390): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1390): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{426573a0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  903): acquireWL(426bfd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(426bfd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42764140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{425043b8: PendingIntentRecord{41fc0c20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140822, Int=0
,D/AutoSetting( 1390): service - handleMessage() stop self
V/AlarmManager(  903): sending alarm PendingIntent{423e6230: PendingIntentRecord{423c5718 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142424, Int=0
,D/AutoSetting( 1390): service - handleMessage() quit looper
,D/AutoSetting( 1390): service - onDestroy() END
,I/ActivityManager(  903): Killing 3644:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3644
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3644
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(427b7e28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): releaseWL(42764140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  903): acquireWL(427bbde8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  903): releaseWL(427bbde8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7877 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): acquireWL(427bed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b86ae8: PendingIntentRecord{42388648 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143643, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427bed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(427b7e28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2232/10028)
,D/PMS     (  903): acquireWL(428ace68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428ace68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(428ae108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{42372818: PendingIntentRecord{42588110 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176856, Int=0
,D/PMS     (  903): releaseWL(428ae108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(428b02d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428b02d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(428b1b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b86ae8: PendingIntentRecord{42388648 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203643, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428b1b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4477): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4477): ====startRecUseTime====
D/htc.customization.log.level( 4477):  is 
W/CustomizationLogLevel( 4477): Level value is invalid, use default level 2
D/CustomizationManager( 4477):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4477): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4477): Parsing tag category name = system
I/CustomizationCIDLoader( 4477): Parsing tag category name = application
I/CustomizationCIDLoader( 4477): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4477): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4477): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4477): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4477): Parsing tag category name = Settings
D/CustomizationManager( 4477):  Read CID file spent 0.172 (s)
D/CustomizationManager( 4477):  All configurations done spent 0.172 (s)
W/HtcNativeFlag( 4477): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4477): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4477): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4477): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=4477, uid=2000 user=0
D/Process (  903): killProcessQuiet, pid=3504
W/asset   (  903): Copying FileAsset 0x6eab99e0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  903): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
I/ActivityManager(  903): Killing 3504:com.example.hello/u0a356 (adj 0): stop com.example.hello
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903):   Force finishing activity ActivityRecord{421164d8 u0 com.example.hello/.MainActivity t2}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  903): WIN DEATH: Window{4209df48 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher(  903): channel '41ec7e00 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  903): channel '41ec7e00 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 3504 uid 10356
W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '41ec7e00 com.example.hello.MainActivity (s)'
I/WindowState(  903): WIN DEATH: Window{41ec7e00 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowManager(  903): WINDOW DIED Window{41ec7e00 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  903): Skipping PackageSetting{422d7000 com.test.thalitest/10348} due to missing metadata
I/ActivityManager(  903): Force stopping com.example.hello appid=10356 user=0: pkg removed
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/acms    ( 1905): Unregistering com.example.hello
E/acms    ( 1905): Could not unregister removed application com.example.hello
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
W/GeofencerStateMachine( 1420): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
D/VoicemailCleanupService( 1293): Cleaning up data for package: com.example.hello
D/PMS     (  903): acquireWL(42825b68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
D/PMS     (  903): releaseWL(42825b68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
D/PackageBroadcastService( 2232): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4492 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/MultiDex( 4492): install
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/ActivityManager(  903): Delaying start of: ServiceRecord{4275ce98 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4492): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4492): loading existing secondary dex files
I/MultiDex( 4492): load found 1 secondary dex files
I/MultiDex( 4492): install done
I/PeopleContactsSync( 2232): CP2 sync disabled
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2232, uid=10028, userID:0
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4510 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PMS     (  903): acquireWL(4238d9a8): PARTIAL_WAKE_LOCK  Icing 0x1 2232 10028 null
I/ProviderInstaller( 4492): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 2232): doRemovePackageData com.example.hello
D/PMS     (  903): releaseWL(4238d9a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4510): install
I/MultiDex( 4510): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4510): loading existing secondary dex files
I/MultiDex( 4510): load found 1 secondary dex files
I/MultiDex( 4510): install done
I/ActivityManager(  903): Resuming delayed broadcast
I/ProviderInstaller( 4510): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1390): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1390): handle notify Blinkfeed plugin client changed
D/Process (  903): killProcessQuiet, pid=4266
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4266:com.google.android.talk/u0a111 (adj 15): empty #17
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2919): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4532 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4492): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4492): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4492): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4492): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4492): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4492): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4492): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4492): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4492): threadid=12: thread exiting with uncaught exception (group=0x416ebe30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
D/Process ( 4492): killProcess, pid=4492
I/ActivityManager(  903): Recipient 4266
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 4492): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4492): Process: com.google.android.gms.drive, PID: 4492
E/AndroidRuntime( 4492): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4492): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4492): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4492): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4492): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4492): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4492): 	at ctn.run(SourceFile:985)
D/Process ( 4492): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2919): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2919): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64508b00
W/dalvikvm( 2919): threadid=16: thread exiting with uncaught exception (group=0x416ebe30)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2919): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2919): Process: com.google.android.googlequicksearchbox:search, PID: 2919
E/AndroidRuntime( 2919): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2919): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2919): 	at cid.d(PG:186)
E/AndroidRuntime( 2919): 	at clo.g(PG:594)
E/AndroidRuntime( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2919): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2919): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2919): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2919): 	at clr.tL(PG:827)
E/AndroidRuntime( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2919): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2919): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2919): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2919): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2919): killProcess, pid=2919
D/Process ( 2919): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
W/PackageManager(  903): Unable to load service info ResolveInfo{41ffe9f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2919): Died!
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Recipient 2919
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2919) has died.
I/ActivityManager(  903): Recipient 4492
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4492) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10993ms
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4532): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4532): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4532): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4532): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4532): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4532): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4532): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4532): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4532): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4532): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4532): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4532): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4532): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4532): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4532): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4532): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4532): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4532): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4532): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4532): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4532): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4532): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4532): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4532): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4532): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4532): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4532): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4532): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4532): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4532): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4532): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4532): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4532): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4532): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4532): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4532): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4532): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4532): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4532): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4532): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4532): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4532): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4532): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4532): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4532): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4532): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4532): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4532): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4532): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4532): threadid=11: thread exiting with uncaught exception (group=0x416ebe30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4532): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4532): Process: com.google.android.apps.docs, PID: 4532
E/AndroidRuntime( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4532): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4532): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4532): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4532): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4532): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4532): killProcess, pid=4532
D/Process ( 4532): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4550 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 4532
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  903): killProcessQuiet, pid=4171
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4171:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4532) has died.
I/ActivityManager(  903): Recipient 4171
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4550): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4550): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4550): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4550): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4550): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4550): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4550): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4550): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4550): threadid=10: thread exiting with uncaught exception (group=0x416ebe30)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4563 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4550): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4550): Process: com.android.keychain, PID: 4550
E/AndroidRuntime( 4550): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4550): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4550): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4550): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4550): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4550): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4550): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4550): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4550): killProcess, pid=4550
D/Process ( 4550): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452276794903.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Recipient 4550
I/ActivityManager(  903): Process com.android.keychain (pid 4550) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10631ms
D/AppTag  ( 4563): getInstance(Context context)
D/AppTag  ( 4563): getInstance(Context context)
D/AppTag  ( 4563): onCreate()
D/PMS     (  903): acquireWL(42765248): PARTIAL_WAKE_LOCK  AsyncService 0x1 3631 10160 null
D/PMS     (  903): releaseWL(42765248): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4581 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4581): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4581 dbg=false s=true
I/DeviceManagement( 4581): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4581): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4581): WorkflowService: Starting workflow service
I/DeviceManagement( 4581): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b51360] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4581): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4581): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4581): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4581): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  903): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4595 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4581): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4581): SessionStateController: Checking invariants...
D/Documents( 4595): Loading roots for com.android.providers.downloads.documents
D/Documents( 4595): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4595): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4595): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4595): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4595): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4595): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4595): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4595): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4595): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4595): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4595): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4595): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4595): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4595): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4595): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4595): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4595): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4595): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4595): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4595): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4595): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4595): threadid=1: thread exiting with uncaught exception (group=0x416ebe30)
E/AndroidRuntime( 4595): FATAL EXCEPTION: main
E/AndroidRuntime( 4595): Process: com.android.documentsui, PID: 4595
E/AndroidRuntime( 4595): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4595): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4595): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4595): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4595): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4595): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4595): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4595): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4595): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4595): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4595): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4595): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4595): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4595): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4595): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4595): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4595): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4595): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4595): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4595): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4595): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4595): 	... 10 more
I/ActivityManager(  903): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4609 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  903): killProcessQuiet, pid=4128
I/ActivityManager(  903): Killing 4128:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  903): App crashed! Process: com.android.documentsui
D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process (  903): killProcessQuiet, pid=3924
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452276795208.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Killing 3924:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process ( 4595): killProcess, pid=4595
D/Process ( 4595): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  903): Recipient 4595
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.documentsui (pid 4595) has died.
I/ActivityManager(  903): Resuming delayed broadcast
D/ExternalStorage( 4609): After updating volumes, found 1 active roots

```
