#### Test 61432979f791f6f_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  944): acquireWL(b9c238e): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072}
V/AlarmManager(  944): sending alarm PendingIntent{122497af: PendingIntentRecord{202617bc com.android.vending startService}}, i=null, t=0, cnt=1, w=1457078749790, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{22db9345: PendingIntentRecord{2cc56adf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=93820, Int=0
D/PMS     (  944): acquireWL(2abaea9a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(b9c238e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
--------- beginning of main
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1893): [NET] android_getaddrinfo_proxy+
D/libc    ( 1893): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1893): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  944): releaseWL(2abaea9a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  944): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5727 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ResourcesManager( 5727): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Finsky  ( 5438): [562] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5438): [1] 5.onFinished: Installation state replication succeeded.
I/Babel_SMS( 5727): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5727): MmsConfig.loadMmsSettings
I/ActivityManager(  944): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5758 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
E/cutils-trace( 5748): Error opening trace file: Permission denied (13)
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5727, uid=10112, userID:0
W/HtcWrapAdjustableCursorFactory( 5758): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 5758): onCreate
D/MmsCustomizationProvider( 5758): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 5758): GetPrviateResource
V/GetPrviateResource( 5758): GetPrviateResource
W/Settings( 5727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5727): startup - clean
D/MmsCustomizationProvider( 5758): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel_SMS( 5727): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 5727): MmsConfig.loadFromDatabase
D/MessageCustFlag( 5758): sense_version=6.0
D/BTAccessoryUtil( 5758): createReceiver
D/BTAccessoryUtil( 5758): registerReceiver return intent = null
D/MessageCustFlag( 5758): sku_id=118
D/HtcBuildUtils( 5758): getRATByHtcTelephonyCapability:1
I/Babel   ( 5727): deleted: false for 0
W/SystemReader( 5758): Cannot find qct_8960_interface, use default value instead
E/Babel_SMS( 5727): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5727): MmsConfig.loadFromResources
E/Babel_SMS( 5727): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5727): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
D/CustomizationManager( 5748): ====startRecUseTime====
D/htc.customization.log.level( 5748):  is 
W/CustomizationLogLevel( 5748): Level value is invalid, use default level 2
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5727, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5727, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5727, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5727, uid=10112, userID:0
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5727, uid=10112, userID:0
W/VideoCapabilities( 5727): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5727): Unsupported mime video/x-ms-wmv
W/Utils   ( 5727): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 5727): Unsupported mime audio/qcelp
W/AudioCapabilities( 5727): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5727): Unsupported mime audio/qcelp
W/VideoCapabilities( 5727): Unsupported mime video/x-ms-wmv
D/CustomizationManager( 5748):  Read ACC file spent 0.039 (s)
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5748): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5748): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5748): Parsing tag category name = system
I/CustomizationCIDLoader( 5748): Parsing tag category name = application
I/CustomizationCIDLoader( 5748): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5748): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5748): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5748): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5748): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5748): add string-array item, value = 42507
I/CustomizationCIDLoader( 5748): add string-array item, value = 21902
I/CustomizationCIDLoader( 5748): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5748): add string-array item, value = 23420
I/CustomizationCIDLoader( 5748): add string-array item, value = 22299
I/CustomizationCIDLoader( 5748): add string-array item, value = 24002
I/CustomizationCIDLoader( 5748): add string-array item, value = 23210
I/CustomizationCIDLoader( 5748): add string-array item, value = 23205
I/CustomizationCIDLoader( 5748): add string-array item, value = 23806
I/CustomizationCIDLoader( 5748): add string-array item, value = 23430
I/CustomizationCIDLoader( 5748): add string-array item, value = 23408
I/CustomizationCIDLoader( 5748): add string-array item, value = 27205
I/CustomizationCIDLoader( 5748): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5748): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5748):  Read CID file spent 0.084 (s)
D/CustomizationManager( 5748):  All configurations done spent 0.084 (s)
I/VideoCapabilities( 5727): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5727): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5727): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5727): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5727): Unrecognized profile 2130706433 for video/avc
D/Process (  944): killProcessQuiet, pid=5554
I/ActivityManager(  944): Killing 5554:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  944): Recipient 5554
D/WifiService(  944): Client connection lost with reason: 4
I/HtcModeClient( 3161): handler message = 4011
E/HtcModeClient( 3161): Check connection and retry 11 times.
D/Process (  944): killProcessQuiet, pid=5479
I/ActivityManager(  944): Killing 5479:com.google.android.gms:car/u0a24 (adj 15): empty #18
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  944): Recipient 5479
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5748 on display 0
D/PMS     (  944): acquireHCC(396171bb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(10c696d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
W/asset   (  944): Copying FileAsset 0x55a12f2160 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  944): acquireWL(1ab6e97): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
I/vclib   ( 5727): onServiceConnected
W/Babel   ( 5727): Attempted to change video mute state without an active call.
I/FeedHostManager( 1538): [onPause]
I/FeedProviderManager( 1538): onPause
I/FeedHostManager( 1538): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@199d66c
I/SocialFeedProvider( 1538): +onPause
I/SocialFeedProvider( 1538): -onPause
I/AnimationUtil(  944): isHTCRecent(ThaliTest/Recent screens.)/11
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  944): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5801 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/asset   ( 5801): Copying FileAsset 0xac639960 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  944): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
I/TrimMemoryManager( 1538): [trimMemory] 20
,I/WebViewFactory( 5801): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5801): Time to load native libraries: 9 ms (timestamps 5077-5086)
,I/LibraryLoader( 5801): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5801): Binding Chromium to main looper Looper (main, tid 1) {12e3563e}
,I/LibraryLoader( 5801): Expected native library version number "",actual native library version number ""
,I/chromium( 5801): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5801): Initializing chromium process, singleProcess=true
W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5801): ApplicationContext is null in ApplicationStatus
,W/chromium( 5801): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5801): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5801): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5801): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5801): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5801): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5801): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5801): Local Branch: 
I/Adreno-EGL( 5801): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5801): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5801):                  d74aa161a12b9c6fc6332151
,W/System.err(  944): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c48f923:true
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 5801): 146446410: getState() :  mService = null. Returning STATE_OFF
,D/PMS     (  944): acquireWL(1e4f814d): PARTIAL_WAKE_LOCK  Icing 0x1 4236 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1e4f814d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(2fa7113): PARTIAL_WAKE_LOCK  Icing 0x1 4236 10024 WorkSource{10024 com.google.android.gms}
,I/art     (  944): Explicit concurrent mark sweep GC freed 24856(1317KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.411ms total 180.083ms,
,D/PMS     (  944): releaseWL(2fa7113): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): acquireWL(19788d05): PARTIAL_WAKE_LOCK  Icing 0x1 4236 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(19788d05): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5801): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 5801): CordovaWebView is running on device made by: HTC,
,W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5801): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 5801): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 5801): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1f0249c6, mServedView=org.apache.cordova.engine.SystemWebView{3b97ed87 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@277974b4,
I/InputMethodManagerService(  944): Disable input method client, pid=1538,
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=5801
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,D/PMS     (  944): releaseWL(1ab6e97): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  944): Displayed com.test.thalitest/.MainActivity: +955ms,
,W/XT9_C   ( 1360): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1360): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1360): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1360): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5801): Cannot call determinedVisibility() - never saw a connection for the pid: 5801
,D/JsMessageQueue( 5801): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5801): JniHelper::setJavaVM(0xab4cd8f8), pthread_self() = -1400945608
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@276d9711 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b03934d added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5801): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  944): New client listening to asynchronous messages,
E/WifiTrafficPoller(  944): ADD_CLIENT: 6
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5801): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5801): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5801): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5801): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5801): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Messaging( 5758): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5758): networkCode: 
D/MessageCustFlag( 5758): sku_id=118
D/MmsConfig( 5758): SIE smsPri: null
D/MmsConfig( 5758): networkCode: 
,D/MmsConfig( 5758): packageName: com.htc.vvm.att does not exist,
D/Messaging( 5758): mNeedToUpdateDate2 start,
,D/ReportIndicatorCache( 5758): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5758): 
D/MmsAsyncWorkHandler( 5758): HM tk = 20001
D/ReportIndicatorCache( 5758): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5758): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@12e3563e
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 5758): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5758): [DraftCache/1] refresh
,D/MmsConfig( 5758): networkCode: 
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1478): sku_id=118
D/DraftCache( 5758): [DraftCache/136] rebuildCache
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,I/Messaging( 5758): mccmnc> 
,D/Messaging( 5758): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
,D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5758): mNeedToUpdateDate2: false
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1478):  slotId = -1000
D/MmsSmsV2Provider( 1478): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5758): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
,D/Jerry   ( 1478): URI_DRAFT
,D/PhoneStorageUtil( 5758): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5758): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5758): createReceiver
,D/DraftCache( 5758): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5758): [DraftCache/136] rebuildCache time: 8
D/MmsAsyncWorkHandler( 5758): 
D/MmsAsyncWorkHandler( 5758): HM tk = 20002
,D/MessageCustFlag( 5758): sense_version=6.0
D/Jerry   ( 5758): start to preload cursor >>>>>>>
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1478): sku_id=118
,D/TelephUtils( 1478): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1478): Update uri=content://mms, match=0
V/MmsProvider( 1478): selection=st=129 AND m_type!=134
D/Messaging( 5758): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5758): TransactionService is going to be woken up.
D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1478):  slotId = -1000
,V/TransactionService( 5758): 1-Creating TransactionService
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,D/AccFlag ( 1478): sku_id=118
,D/Messaging( 5758): ViewCache CreatePreload
D/Messaging( 5758): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 5758): onStartCommand: 1
D/MmsSystemEventReceiver( 5758): unRegisterForConnectionStateChanges
V/TransactionService( 5758): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5758): Loading previous transactions.
,D/TelephUtils( 1478): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1478): device_type: 1
,D/Cust_MMSMS( 5758): _has_set_default_values_2=true
,D/TransactionService( 5758): Force clearing mTransactionList
,D/TransactionService( 5758): Force set service start id to 1
V/TransactionService( 5758): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5758): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 5758): def_index: 0
,D/TransactionService( 5758): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5758): Destroying TransactionService
,V/TransactionService( 5758): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 5758): globalIndex = 1
,D/MsgPreferenceUtils( 5758): phone state: true
D/MsgPreferenceUtils( 5758): sd state: false
D/MsgPreferenceUtils( 5758): vIndex = 0
,D/PMS     (  944): releaseHCC(396171bb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  944): releaseHCC(10c696d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5801): Initializing JXcore engine
,W/jxcore-log( 5801): JXcore engine is ready
,W/jxcore-log( 5801): Starting JXcore engine,
,W/jxcore-log( 5801): Platform android
W/jxcore-log( 5801): 
W/jxcore-log( 5801): Process ARCH arm,
W/jxcore-log( 5801): 
,I/jxcore-log( 5801): JXcore Cordova bridge is ready!,
I/jxcore-log( 5801): 
W/jxcore-log( 5801): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5801): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 5801): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5801): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5801): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/PMS     (  944): acquireWL(5ae00e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 944 1000 null
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/PluginManager( 5801): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 54ms. Plugin should use CordovaInterface.getThreadPool().,
,I/FeedHostManager( 1538): [onResume]
I/FeedProviderManager( 1538): onResume,
I/SocialFeedProvider( 1538): +onResume
I/SocialFeedProvider( 1538): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1538): -onResume
I/ConnectivityHelper( 1538): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  944): setSystemUiVisibility(0x8700)
D/FindExtension( 1538): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,I/ThreadedRenderer( 1538): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/InputMethodManagerService(  944): Disable input method client, pid=5801
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  944): Enable input method client, pid=1538
W/IInputConnectionWrapper( 5801): reportFullscreenMode on inactive InputConnection
,D/PMS     (  944): releaseWL(5ae00e3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  944): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,D/Process (  944): killProcessQuiet, pid=4939
I/ActivityManager(  944): Killing 4939:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
I/ActivityManager(  944): Recipient 4939
D/MediaRouterService(  944): Client com.google.android.music (pid 4939): Died!
W/OpenGLRenderer( 1538): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
D/PMS     (  944): acquireWL(15204ad1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=98257, Int=0
D/PMS     (  944): releaseWL(15204ad1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
I/ClockController( 1223): schedule update now=1457078760061 next=59939
I/Clock   ( 1223): updateClock:09:06 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:06 Europe/Warsaw
I/Clock   ( 1223): updateClock:09:06 Europe/Warsaw
W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3161): handler message = 4011,
E/HtcModeClient( 3161): Check connection and retry 12 times.
,I/HtcModeClient( 3161): handler message = 4011,
,E/HtcModeClient( 3161): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3161): Don't start project servcice,
,D/HtcModeClient( 3161): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3161): connectState: CONNECTION_READY = false
,D/SilentMusic( 3161): call stop
D/HtcModeClient( 3161): close connection
W/HtcModeClient( 3161): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3161): read the terminate packet, so break
,D/Process (  944): killProcessQuiet, pid=3161,
I/ActivityManager(  944): Killing 3161:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 3161,
,I/ActivityManager(  944): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5887 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  944): acquireWL(431b936): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10076}
V/AlarmManager(  944): sending alarm PendingIntent{255e8037: PendingIntentRecord{15d789a4 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457078767269, Int=60000
D/PMS     (  944): releaseWL(431b936): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,D/SMSBackup( 5887): SMSBackupAgentService started,
D/SMSBackup( 5887): Checking restore status,
,D/SMSBackup( 5887): Restore complete,
D/SMSBackup( 5887): cancelCheckAlarm
,D/SMSBackup( 5887): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  944): killProcessQuiet, pid=5226
I/ActivityManager(  944): Killing 5226:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5226
,I/PMS     (  944): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@30770d18
D/ActivityManager(  944): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{13d832c2 #9 A=.Prism U=0 sz=1}
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  944): mWirelessDisplayManager is null
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
W/PMS     (  944): mWirelessDisplayManager is still null
W/SensorService(  944): pid=944, uid=1000
W/PMN     (  944): goingToSleep
W/SensorService(  944): Active sensors: size = 4
D/PMS     (  944): acquireWL(1690e8d3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 944 1000 null
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@30770d18, eanble = 0, strlen(mName) = 91
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@5f6f928
W/SensorService(  944): Listener[1] = com.htc.smartdim.sensor_eye@255e7512
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  944): Sleeping (uid 1000)...
D/XAN-DPS (  944): prepareColorFade 1
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMN     (  944): goingToSleep done
I/FeedHostManager( 1538): [onPause]
I/FeedProviderManager( 1538): onPause
I/FeedHostManager( 1538): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@199d66c
I/SocialFeedProvider( 1538): +onPause
I/SocialFeedProvider( 1538): -onPause
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  944): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  944): Build Date: 03/09/15 Mon
I/Adreno-EGL(  944): Local Branch: 
I/Adreno-EGL(  944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  944): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  944):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  944): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5910 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,D/AlarmManager(  944): ACTION_SCREEN_ON
I/AlarmManager(  944): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done recovering
I/AlarmManager(  944): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  944): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  944): releaseWL(1690e8d3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
,D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled
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
E/WifiStateMachine(  944): handleMessage: E msg.what=131129
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  944): handleMessage: X
V/SRS_Proc(  438): ParamSet string: screen_state=on
E/audio_a2dp_hw(  438): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiController(  944): handleMessage: E msg.what=155650
,D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/NetworkPolicy(  944): updateScreenOn: false
V/NetworkPolicy(  944): updateIfacesLocked()
,D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 5910): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
I/CalendarProvider2( 5910): Created com.android.providers.calendar.CalendarAlarmManager@172196f9(com.htc.providers.calendar.HtcCalendarProvider@12e3563e)
,I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false),
D/CalendarProvider2( 5910): wait start:true
,D/PMS     (  944): acquireWL(1f02a3d4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(c02897d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  944): prepareColorFade done
D/PMS     (  944): releaseWL(1f02a3d4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/XAN-DPS (  944): setBrightness to 0
,D/PMS     (  944): releaseWL(c02897d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@5f6f928
I/DisplayManagerService(  944): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM32181 Light sensor
,V/ActivityManager(  944): Display changed displayId=0
W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@5f6f928, eanble = 0, strlen(mName) = 66
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@255e7512
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/AlarmManager(  944): ACTION_SCREEN_OFF
,I/AlarmManager(  944): [AlarmQueuing] screen off now: 
I/AlarmManager(  944): [AlarmQueuing] data connection: true
I/AlarmManager(  944): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  944): stopDataStallAlarm 
,E/WifiDataStallTracker(  944): ENABLE_DATA_MONITOR_POLL false Token 0
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
E/WifiStateMachine(  944): handleMessage: E msg.what=131167
E/WifiStateMachine(  944): processMsg: InitialState
E/WifiStateMachine(  944):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  944): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  944): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false,
E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
V/SRS_Proc(  438): ParamSet string: screen_state=off
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: InitialState
E/audio_a2dp_hw(  438): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  944):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
D/WifiController(  944): handleMessage: E msg.what=155651
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/NetworkPolicy(  944): updateScreenOn: false
D/GpsLocationProvider(  944): receive broadcast intent, action: android.intent.action.SCREEN_OFF
V/NetworkPolicy(  944): updateIfacesLocked()
D/NetworkManagementService(  944): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 5910): wait end:false
,I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3e26ec1e, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): enable: get sensor name = hTC Gesture Motion HIDI
,I/ActivityManager(  944): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,W/SensorService(  944): pid=1223, uid=10041
,W/SensorService(  944): Active sensors: size = 4
W/SensorService(  944): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3e26ec1e, eanble = 1, strlen(mName) = 57
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  944): Listener[0] = com.htc.smartdim.sensor_eye@255e7512
,W/SensorService(  944): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3e26ec1e
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1478): start background delete task...
,I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1478): size: 0 , 0
D/ContactMessageStore( 1478): Background delete complete
,D/PMS     (  944): acquireWL(13b34079): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(13b34079): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(178d81be): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(178d81be): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1223): apply : com.htc.updater 1 13 1 36,
,W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/PowerUsageList:PowerUsageHelper( 5940): MY_DEBUG = false
,D/PMS     (  944): acquireWL(131e6b35): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5940 1000 null
,D/SmartSyncUtils( 5940): isEpsOn(), nState = 0,
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  944): Init customizeScreenOffDelayClass error
D/PMS     (  944): releaseWL(131e6b35): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PMS     (  944): Setting HAL interactive mode to false
D/SurfaceControl(  944): Excessive delay in setPowerMode(): 304ms
D/PMS     (  944): Setting HAL interactive mode to false done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  944): Setting HAL auto-suspend mode to true
D/PMS     (  944): Setting HAL auto-suspend mode done
,I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  944): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/InputMethodManagerService(  944): screenObserver, isScreenOn=false
W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
I/InputMethodManagerService(  944): Disable input method client, pid=1538
D/HABCtrl (  944): TPE algorithm. remove timeout.
D/NfcService( 1498): ScreenObserver: OFF
D/PMS     (  944): OOBE c monitor 11
,D/NfcService( 1498): applyRouting - 0
W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/PMS     (  944): acquireWL(89bfbca): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1498 1027 null
,W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/NfcService( 1498): applyRouting -2
,D/PMS     (  944): acquireWL(1b21e058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(1b21e058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NfcService( 1498): applyRouting
D/NfcService( 1498): Ignore this applyRouting...
,D/PMS     (  944): releaseWL(89bfbca): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
,D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): updateBatteryInfo
D/WifiController(  944): handleMessage: E msg.what=155652
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: ApStaDisabledState
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/SmartSyncUtils( 5940): isEpsOn(), nState = 0
D/SmartSyncUtils( 5940): isEpsOn(), nState = 0
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@255e7512,
,W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  944): disable: get sensor name = Accelerometer Sensor
I/ClockController( 1223): stop clock update:screen off
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 3
W/SensorService(  944): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@255e7512, eanble = 0, strlen(mName) = 36
W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3e26ec1e
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  944): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  944): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  944): pid=944, uid=1000
W/SensorService(  944): Active sensors: size = 2
W/SensorService(  944): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  944): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  944): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@255e7512, eanble = 0, strlen(mName) = 36
,W/SensorService(  944): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  944): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3e26ec1e
W/SensorService(  944): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/TetherSettings( 5412): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5412): Cust_ConnectToPC   : Internet_Sharing>true
E/ActivityThread(  944): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@ecf84e3 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  944): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@ecf84e3 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/        ( 5412): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5412): Cust_ConnectToPC   : spcsc>false
D/        ( 5412): Cust_ConnectToPC   : IPT>true
D/        ( 5412): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5412): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5412): Index of the first 1 = -1
I/SensorManager(  944): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@255e7512
I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
I/PowerUsageList:PowerUsageHelper( 5940): PowerProfile::POWER_SCREEN_FULL = 154.8
W/ContextImpl( 5412): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
W/ContextImpl( 5412): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 5412): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5412): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5412): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5412): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/ActivityManager(  944): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5975 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/PowerUsageList:BatterySipperExt( 5940): gen(), null == sipper.uidObj, userId = 0,
,D/SmartNS_Utility( 5412): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5412): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PowerUsageService( 5940): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5940): MY_DEBUG = false
,D/SmartSyncUtils( 5940): getMobilePolicyEnabled, result = true,
D/Process (  944): killProcessQuiet, pid=5390
I/ActivityManager(  944): Killing 5390:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7
D/WifiService(  944): New client listening to asynchronous messages
,I/ActivityManager(  944): Recipient 5390
,I/ActivityManager(  944): Killing 5618:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5618
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5618
,I/CalendarProvider2( 5910): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5910): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  944): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5999 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  944): killProcessQuiet, pid=5640
I/ActivityManager(  944): Killing 5640:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5640
,W/ResourcesManager( 5999): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5999): onCreate,
,D/ProviderChangeReceiver( 5999): ---------------------------------------------------,
D/ProviderChangeReceiver( 5999): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  944): killProcessQuiet, pid=4582
,I/ActivityManager(  944): Killing 4582:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 5999): start to updateAlertNotification!
,D/PMS     (  944): releaseWL(3267d0b3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  944): Recipient 4582,
,D/HtcAlertService( 5999): No fired or scheduled alerts
D/HtcAlertUtils( 5999): -- cancelReminderNotification --
,D/HtcAlertUtils( 5999): broadcastExistReminder!
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  944): killProcessQuiet, pid=5040
I/ActivityManager(  944): Killing 5040:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5040,
,D/PMS     (  944): acquireWL(3d660a96): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1b06617: PendingIntentRecord{400aa04 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457078784185, Int=0
D/PMS     (  944): acquireWL(2b2dcbed): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
,D/PMS     (  944): releaseWL(3d660a96): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  944): releaseWL(2b2dcbed): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1478): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  944): acquireWL(3cf03a22): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{3c4b4cb3: PendingIntentRecord{22e06270 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140680, Int=0,
D/PMS     (  944): releaseWL(3cf03a22): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,D/PMS     (  944): acquireWL(a2839e9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(a2839e9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: ApStaDisabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  944): acquireWL(7fbd66e): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{32c1b953: PendingIntentRecord{c256290 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=144879, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158256, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{28a4010f: PendingIntentRecord{2cc56adf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=163797, Int=0,
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/PMS     (  944): acquireWL(26c1359c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1893): [NET] android_getaddrinfo_proxy+
D/libc    ( 1893): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1893): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(26c1359c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(7fbd66e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/TelephonyReceiver( 1478): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  944): acquireWL(31418ba5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/BatteryService(  944): n_update end
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): releaseWL(31418ba5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
D/PowerUI ( 1223): closing low battery warning: level=100
,D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: ApStaDisabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1440): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@27f35598
,D/Process (  944): killProcessQuiet, pid=5672
,I/ActivityManager(  944): Killing 5672:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5672
,D/PMS     (  944): acquireWL(1812eb7a): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1000},
V/AlarmManager(  944): sending alarm PendingIntent{1e299f2b: PendingIntentRecord{c7a0f88 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=195347, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218257, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  944): sending alarm PendingIntent{32c1b953: PendingIntentRecord{c256290 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=223811, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  944): sending alarm PendingIntent{be43d21: PendingIntentRecord{3544546 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=182714, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): acquireWL(32210307): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(1812eb7a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
D/PMS     (  944): releaseWL(32210307): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  944): acquireWL(5649c34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(5649c34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  944): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): runPSCheck
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1223): closing low battery warning: level=100
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: ApStaDisabledState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): << updateStatus
,D/WifiController(  944): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  944): acquireWL(37a68a5d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278256, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{10ff6fd2: PendingIntentRecord{2cc56adf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=303724, Int=0
D/PMS     (  944): acquireWL(1cc947a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  944): sending alarm PendingIntent{1b466f59: PendingIntentRecord{ac0b71e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457079001504, Int=0
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1893): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1893): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1893): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(1cc947a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(37a68a5d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1893): Explicit concurrent mark sweep GC freed 16012(890KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.276ms total 72.967ms
,I/GLSUser ( 1893): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1893): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1893): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1893): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1893): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/GLSActivity( 1893): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1893): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1893): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1893): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/PlayEventLogger( 5438): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5438): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5438): 	at android.os.Binder.execTransact(Binder.java:454)
,W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): apply : com.google.android.gms 0 23 8 40
,W/System  ( 5438): Ignoring header User-Agent because its value was null.
,D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5438): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5438): [NET] android_getaddrinfo_proxy+
D/libc    ( 5438): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5438): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  944): acquireWL(3f0dd8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): releaseWL(3f0dd8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): runPSCheck
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  944): >> updateStatus
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  944): acquireWL(11d4e0c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398256, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{189723ce: PendingIntentRecord{2cc56adf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=619594, Int=0,
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     (  944): Explicit concurrent mark sweep GC freed 23592(1327KB) AllocSpace objects, 5(496KB) LOS objects, 33% free, 18MB/27MB, paused 1.511ms total 177.191ms
D/PMS     (  944): acquireWL(49732ef): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/PMS     (  944): releaseWL(11d4e0c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/libc    ( 1893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1893): [NET] android_getaddrinfo_proxy+
D/libc    ( 1893): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1893): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(49732ef): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/ContactMessageStore( 1478): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1478): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1478): sku_id=118
D/ContactMessageStore( 1478): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1478): start background delete task...
,D/ContactMessageStore( 1478): size: 0 , 0
,D/ContactMessageStore( 1478): Background delete complete
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1893): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1893): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1893): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1893): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1893): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1893): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1893): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1893): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5438): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5438): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5438): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5438): Ignoring header User-Agent because its value was null.
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5438): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5438): [NET] android_getaddrinfo_proxy+
D/libc    ( 5438): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5438): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/PMS     (  944): acquireWL(385a8e39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
,D/PMS     (  944): releaseWL(385a8e39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/UsbnetService(  944): onReceive BATTERY_CHANGED
,D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/WifiController(  944): battery changed pluggedType: 2
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  944): acquireWL(efa1c7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638257, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{cbfe824: PendingIntentRecord{1648ff8d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804512, Int=0
,I/ActivityManager(  944): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6040 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  944): sending alarm PendingIntent{1ca0b5df: PendingIntentRecord{3151922c com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457079316293, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{144cd4f5: PendingIntentRecord{379ab983 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457079620590, Int=0
W/ContextImpl( 5940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  944): releaseWL(efa1c7e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/PowerUsageList:PowerUsageHelper( 5940): MY_DEBUG = false
,D/PowerUsageService( 5940): repeat time = 1457080520661
,D/WeatherUtility( 1223): Weather sync is On
,I/art     (  455): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 384us total 52.755ms
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 405us total 27.980ms
,I/art     (  455): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 304us total 20.768ms
,I/PowerUsageList:PowerUsageHelper( 5940): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5940): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5940): calcPower(), no data,
,E/cutils-trace( 6062): Error opening trace file: Permission denied (13),
I/dex2oat ( 6062): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6062): dex2oat: override thread count:4
,I/dex2oat ( 6062): dex2oat took 695.255ms (threads: 4)
,I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6040): ApplicationMonitor {251593bb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6040): PnsModel {8ba984a}: update(): Update registration caused by: alarm
,I/PushClient( 6040): PnsConfigModel {23193069}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6040): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6040): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6040): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6040): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  944): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6070 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6070): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6070 dbg=false s=true,
,I/DeviceManagement( 6070): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6070): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6070): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6070): WorkflowService: Starting workflow service
,I/DeviceManagement( 6070): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8ba984a] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6070): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6070): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6070): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6070): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6070): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6070): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6070): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6070): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@8ba984a]
,I/DeviceManagement( 6070): WorkflowService: Stopping workflow service
,D/Process (  944): killProcessQuiet, pid=5507
I/ActivityManager(  944): Killing 5507:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5507
,I/PushClient( 6040): PnsModel {8ba984a}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  944): killProcessQuiet, pid=5364
I/ActivityManager(  944): Killing 5364:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5364
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1893): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1893): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1893): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1893): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1893): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1893): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1893): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1893): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5438): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5438): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5438): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5438): Ignoring header User-Agent because its value was null.
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    ( 5438): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5438): [NET] android_getaddrinfo_proxy+
D/libc    ( 5438): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5438): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1223): reapply : com.google.android.gms 4 40
,D/PMS     (  944): acquireWL(45f9460): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998256, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{1e279d19: PendingIntentRecord{311b1de com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457079672659, Int=0
,D/SmartSyncUtils( 5940): isEpsOn(), nState = 0
,D/PMS     (  944): releaseWL(45f9460): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  944): acquireWL(226e8fbf): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5940 1000 null,
,D/SmartSyncScreenOnOffTimeReceiver( 5940): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 5940): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
D/SmartSyncScreenOnOffTimeReceiver( 5940): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5940): SettingOnTime = 1457157600000, randomSettingOnTime = 1457155581000
,D/SmartSyncScreenOnOffTimeReceiver( 5940): SettingOffTime = 1457136000000, randomSettingOffTime = 1457136884000
D/SmartSyncScreenOnOffTimeReceiver( 5940): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5940): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5940): bNightModeTurnOffOnce = false
,D/PMS     (  944): releaseWL(226e8fbf): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  944): acquireWL(599968c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{935644b: PendingIntentRecord{d4cbe28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058256, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{2a8bf1d5: PendingIntentRecord{2cc56adf com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1179408, Int=0
,D/PMS     (  944): acquireWL(21030dea): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1893 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(599968c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On,
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1893): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1893): [NET] android_getaddrinfo_proxy+
D/libc    ( 1893): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
,D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/PMS     (  944): releaseWL(21030dea): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1893): [NET] android_getaddrinfo_proxy-, NODATA
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  944): User[0] Flushing usage stats to disk
,V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1893): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1893): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1893): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1893): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1893): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1893): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1893): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1893): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1893): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1893): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
E/PlayEventLogger( 5438): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5438): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5438): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5438): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5438): Ignoring header User-Agent because its value was null.
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5438): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5438): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5438): [NET] android_getaddrinfo_proxy+
D/libc    ( 5438): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5438): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1223): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,TIME-OUT KILL (timeout was 1200000ms)
```
