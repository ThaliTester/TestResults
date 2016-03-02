#### Test 613623660556c10_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Messaging( 5724): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5724): networkCode: 
D/MessageCustFlag( 5724): sku_id=118
D/MmsConfig( 5724): SIE smsPri: null
D/MmsConfig( 5724): networkCode: 
D/MmsConfig( 5724): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 5724): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5724): 
D/MmsAsyncWorkHandler( 5724): HM tk = 20001
D/ReportIndicatorCache( 5724): MSG_QUERY_REPORTS >>
D/Messaging( 5724): mNeedToUpdateDate2 start
D/SettingsManager( 5724): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@ca46ec1
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1460): sku_id=118
D/DraftCache( 5724): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5724): [DraftCache/1] refresh
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1460):  slotId = -1000
D/MmsSmsV2Provider( 1460): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/DraftCache( 5724): [DraftCache/132] rebuildCache
I/Messaging( 5724): mccmnc> 
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/MmsSmsV2Provider( 1460):  slotId = -1000
D/MmsSmsV2Provider( 1460): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 5724): networkCode: 
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1460):  slotId = -1000
D/MmsSmsV2Provider( 1460): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1460):  slotId = -1000
D/MmsSmsV2Provider( 1460): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 5724): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 5724): ViewCache CreatePreloadOnlyConversationList
I/art     (  956): Explicit concurrent mark sweep GC freed 21620(1149KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.619ms total 165.046ms
D/Messaging( 5724): mNeedToUpdateDate2: false
D/PhoneStorageUtil( 5724): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5724): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5724): createReceiver
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/Jerry   ( 1460): URI_DRAFT
D/MessageCustFlag( 5724): sense_version=6.0
D/Jerry   ( 5724): start to preload cursor >>>>>>>
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1460):  slotId = -1000
D/DraftCache( 5724): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5724): [DraftCache/132] rebuildCache time: 17
D/MmsAsyncWorkHandler( 5724): 
D/MmsAsyncWorkHandler( 5724): HM tk = 20002
D/TelephUtils( 1460): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1460): Update uri=content://mms, match=0
V/MmsProvider( 1460): selection=st=129 AND m_type!=134
D/Messaging( 5724): Reset downloading state: 0
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/AccFlag ( 1460): sku_id=118
V/MmsSystemEventReceiver( 5724): TransactionService is going to be woken up.
D/Messaging( 5724): ViewCache CreatePreload
D/Messaging( 5724): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 5724): 1-Creating TransactionService
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1460): sku_id=118
D/Cust_MMSMS( 5724): _has_set_default_values_2=true
V/TransactionService( 5724): onStartCommand: 1
D/MmsSystemEventReceiver( 5724): unRegisterForConnectionStateChanges
V/TransactionService( 5724): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5724): Loading previous transactions.
D/MsgPreferenceUtils( 5724): def_index: 0
D/TelephUtils( 1460): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/AccFlag ( 1460): device_type: 1
D/MsgPreferenceUtils( 5724): globalIndex = 1
D/TransactionService( 5724): Force clearing mTransactionList
D/TransactionService( 5724): Force set service start id to 1
V/TransactionService( 5724): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5724): unRegisterForConnectionStateChanges
V/TransactionService( 5724): Destroying TransactionService
D/TransactionService( 5724): stopSelfResult: true, mLastHandledServiceId: 1
D/MsgPreferenceUtils( 5724): phone state: true
D/MsgPreferenceUtils( 5724): sd state: false
D/MsgPreferenceUtils( 5724): vIndex = 0
V/TransactionService( 5724): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/cutils-trace( 5783): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5783): ====startRecUseTime====
D/htc.customization.log.level( 5783):  is 
W/CustomizationLogLevel( 5783): Level value is invalid, use default level 2
D/CustomizationManager( 5783):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5783): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5783): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5783): Parsing tag category name = system
I/CustomizationCIDLoader( 5783): Parsing tag category name = application
I/CustomizationCIDLoader( 5783): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5783): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5783): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5783): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5783): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5783): add string-array item, value = 42507
I/CustomizationCIDLoader( 5783): add string-array item, value = 21902
I/CustomizationCIDLoader( 5783): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5783): add string-array item, value = 23420
I/CustomizationCIDLoader( 5783): add string-array item, value = 22299
I/CustomizationCIDLoader( 5783): add string-array item, value = 24002
I/CustomizationCIDLoader( 5783): add string-array item, value = 23210
I/CustomizationCIDLoader( 5783): add string-array item, value = 23205
I/CustomizationCIDLoader( 5783): add string-array item, value = 23806
I/CustomizationCIDLoader( 5783): add string-array item, value = 23430
I/CustomizationCIDLoader( 5783): add string-array item, value = 23408
I/CustomizationCIDLoader( 5783): add string-array item, value = 27205
I/CustomizationCIDLoader( 5783): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5783): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5783):  Read CID file spent 0.092 (s)
D/CustomizationManager( 5783):  All configurations done spent 0.092 (s)
--------- beginning of system
I/ActivityManager(  956): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5783 on display 0
D/PMS     (  956): acquireHCC(3c07e3fa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 956 1000 null
D/PMS     (  956): acquireHCC(42e6dab): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 956 1000 null
W/asset   (  956): Copying FileAsset 0x559f3f6060 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  956): acquireWL(e045c6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 956 1000 null
I/FeedHostManager( 1518): [onPause]
I/FeedProviderManager( 1518): onPause
I/FeedHostManager( 1518): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@485b141
I/AnimationUtil(  956): isHTCRecent(ThaliTest/Recent screens.)/7
I/SocialFeedProvider( 1518): +onPause
I/SocialFeedProvider( 1518): -onPause
W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  956): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5801 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/TrimMemoryManager( 1518): [trimMemory] 20
D/StatusBarManagerService(  956): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/asset   ( 5801): Copying FileAsset 0xac4a45d8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  956): hiding MENU key
,I/WebViewFactory( 5801): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5801): Time to load native libraries: 13 ms (timestamps 5532-5545),
,I/LibraryLoader( 5801): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5801): Binding Chromium to main looper Looper (main, tid 1) {ca46ec1}
I/LibraryLoader( 5801): Expected native library version number "",actual native library version number ""
,I/chromium( 5801): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5801): Initializing chromium process, singleProcess=true
,W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
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
,W/System.err(  956): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  956): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  956): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b29bf4d:true
W/System.err(  956): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  956): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  956): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  956): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 5801): 576733938: getState() :  mService = null. Returning STATE_OFF
,I/HtcModeClient( 3138): handler message = 4011
,E/HtcModeClient( 3138): Check connection and retry 11 times.
W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5801): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5801): CordovaWebView is running on device made by: HTC
,W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5801): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5801): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 5801): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5801): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@26024e69, mServedView=org.apache.cordova.engine.SystemWebView{311590ee VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3e6b698f
,I/InputMethodManagerService(  956): Disable input method client, pid=1518
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
I/InputMethodManagerService(  956): Enable input method client, pid=5801
,I/ActivityManager(  956): Displayed com.test.thalitest/.MainActivity: +807ms
D/PMS     (  956): releaseWL(e045c6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/XT9_C   ( 1354): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#0
,I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1354): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5801): Cannot call determinedVisibility() - never saw a connection for the pid: 5801
,D/JsMessageQueue( 5801): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5801): JniHelper::setJavaVM(0xab3388f8), pthread_self() = -1402631560
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Insecure RFCOMM socket port number: -1
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5801): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360ea3d9 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a65c4c added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5801): addListener: New listener added - the number of listeners is now 1
,E/WifiTrafficPoller(  956): ADD_CLIENT: 6,
D/WifiService(  956): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5801): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5801): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5801): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5801): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5801): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,D/PMS     (  956): acquireWL(1c415df1): PARTIAL_WAKE_LOCK  Icing 0x1 4211 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  956): releaseWL(1c415df1): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(11b09857): PARTIAL_WAKE_LOCK  Icing 0x1 4211 10024 WorkSource{10024 com.google.android.gms}
,I/chromium( 5801): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  956): releaseWL(11b09857): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseHCC(3c07e3fa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
,D/PMS     (  956): releaseHCC(42e6dab): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5801): Initializing JXcore engine,
W/jxcore-log( 5801): JXcore engine is ready
,W/jxcore-log( 5801): Starting JXcore engine,
,W/jxcore-log( 5801): Platform android,
W/jxcore-log( 5801): 
W/jxcore-log( 5801): Process ARCH arm
W/jxcore-log( 5801): 
,I/jxcore-log( 5801): JXcore Cordova bridge is ready!,
I/jxcore-log( 5801): 
W/jxcore-log( 5801): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5801): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 5801): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 5801): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5801): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 5801): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 50ms. Plugin should use CordovaInterface.getThreadPool().,
D/PMS     (  956): acquireWL(1b4e5bb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 956 1000 null
W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1518): [onResume]
I/FeedProviderManager( 1518): onResume
I/SocialFeedProvider( 1518): +onResume
I/SocialFeedProvider( 1518): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1518): -onResume
,I/ConnectivityHelper( 1518): [getCurrentConnectionType] no network connection
,D/StatusBarManagerService(  956): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  956): hiding MENU key
D/FindExtension( 1518): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1518): Defer allocateBuffers to drawing time
I/InputMethodManagerService(  956): Disable input method client, pid=5801
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
I/InputMethodManagerService(  956): Enable input method client, pid=1518
,W/IInputConnectionWrapper( 5801): reportFullscreenMode on inactive InputConnection
,D/PMS     (  956): releaseWL(1b4e5bb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  956): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  956): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  956): hiding MENU key
,D/Process (  956): killProcessQuiet, pid=4927
I/ActivityManager(  956): Killing 4927:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  956): Recipient 4927
,D/MediaRouterService(  956): Client com.google.android.music (pid 4927): Died!
,W/OpenGLRenderer( 1518): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/HtcModeClient( 3138): handler message = 4011,
E/HtcModeClient( 3138): Check connection and retry 12 times.,
,I/HtcModeClient( 3138): handler message = 4011,
,E/HtcModeClient( 3138): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3138): Don't start project servcice
,D/HtcModeClient( 3138): setEject: MEDIA_EJECT_STATE = true,
D/HtcModeClient( 3138): connectState: CONNECTION_READY = false
D/SilentMusic( 3138): call stop
D/HtcModeClient( 3138): close connection
W/HtcModeClient( 3138): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3138): read the terminate packet, so break
,D/Process (  956): killProcessQuiet, pid=3138
I/ActivityManager(  956): Killing 3138:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 3138,
,I/ActivityManager(  956): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5860 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,D/PMS     (  956): acquireWL(1ab42886): PARTIAL_WAKE_LOCK  *alarm* 0x1 956 1000 WorkSource{10076}
V/AlarmManager(  956): sending alarm PendingIntent{20b24547: PendingIntentRecord{18ed5174 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456908914616, Int=60000
D/PMS     (  956): releaseWL(1ab42886): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5860): SMSBackupAgentService started
D/SMSBackup( 5860): Checking restore status
,D/SMSBackup( 5860): Restore complete
,D/SMSBackup( 5860): cancelCheckAlarm
,D/SMSBackup( 5860): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  956): killProcessQuiet, pid=5172
I/ActivityManager(  956): Killing 5172:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5172
,I/PMS     (  956): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  956): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{39a4712 #9 A=.Prism U=0 sz=1}
I/SensorManager(  956): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@32fdcacd
W/PMS     (  956): mWirelessDisplayManager is null
W/SensorService(  956): Following SensorService logs are not warning, just make sure they are printed
,W/PMS     (  956): mWirelessDisplayManager is still null
W/SensorService(  956): disable: get sensor name = Accelerometer Sensor
W/PMN     (  956): goingToSleep
,W/SensorService(  956): pid=956, uid=1000
D/PMS     (  956): acquireWL(1443eee3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 956 1000 null
W/SensorService(  956): Active sensors: size = 4
I/PMS     (  956): Sleeping (uid 1000)...
W/SensorService(  956): Accelerometer Sensor (handle=0x00000000, connections=1)
D/XAN-DPS (  956): prepareColorFade 1
W/SensorService(  956): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  956): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  956): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  956): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@32fdcacd, eanble = 0, strlen(mName) = 91
W/SensorService(  956): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  956): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1714d4c2
W/SensorService(  956): Listener[1] = com.htc.smartdim.sensor_eye@199971d6
W/SensorService(  956): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1220): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,I/Adreno-EGL(  956): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  956): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  956): Build Date: 03/09/15 Mon
I/Adreno-EGL(  956): Local Branch: 
,I/Adreno-EGL(  956): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  956): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  956):                  d74aa161a12b9c6fc6332151
,I/FeedHostManager( 1518): [onPause],
W/PMN     (  956): goingToSleep done
I/FeedProviderManager( 1518): onPause
I/FeedHostManager( 1518): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@485b141
I/SocialFeedProvider( 1518): +onPause
I/SocialFeedProvider( 1518): -onPause
,W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/PMS     (  956): releaseWL(1443eee3): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  956): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5884 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  956): ACTION_SCREEN_ON
I/AlarmManager(  956): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  956): [AlarmQueuing] done recovering
I/AlarmManager(  956): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  956): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  956): handleMessage: E msg.what=131167,
E/WifiStateMachine(  956): processMsg: InitialState,
E/WifiStateMachine(  956):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  956):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  956): handleMessage: E msg.what=155650
D/NetworkPolicy(  956): updateScreenOn: false
D/WifiController(  956): processMsg: ApStaDisabledState
V/NetworkPolicy(  956): updateIfacesLocked()
D/WifiController(  956): processMsg: DefaultState
D/NetworkManagementService(  956): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  956): handleMessage: X
D/WifiStateMachine(  956): getWifiLinkLayerStats: WIFI is not enbled
D/WifiStateMachine(  956): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  956): handleScreenStateChanged Exit: true
E/WifiStateMachine(  956): handleMessage: X
E/WifiStateMachine(  956): handleMessage: E msg.what=131154
E/WifiStateMachine(  956): processMsg: InitialState
E/WifiStateMachine(  956):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  956): handleMessage: X
E/WifiStateMachine(  956): handleMessage: E msg.what=131127
E/WifiStateMachine(  956): processMsg: InitialState
E/WifiStateMachine(  956):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  956): handleMessage: X
E/WifiStateMachine(  956): handleMessage: E msg.what=131129
E/WifiStateMachine(  956): processMsg: InitialState
E/WifiStateMachine(  956):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  956): handleMessage: X
,W/ResourcesManager( 5884): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/GpsLocationProvider(  956): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/CalendarProvider2( 5884): Created com.android.providers.calendar.CalendarAlarmManager@d75cfcb(com.htc.providers.calendar.HtcCalendarProvider@227b83a8)
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/XAN-DPS (  956): prepareColorFade done
D/XAN-DPS (  956): setBrightness to 0
,D/CalendarProvider2( 5884): wait start:true
,I/IntentController( 1220): receive(android.intent.action.SCREEN_ON,1,false),
,I/SensorManager(  956): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1714d4c2
W/SensorService(  956): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  956): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  956): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  956): Display changed displayId=0
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
,W/SensorService(  956): pid=956, uid=1000,
W/SensorService(  956): Active sensors: size = 3
W/SensorService(  956): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  956): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  956): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  956): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1714d4c2, eanble = 0, strlen(mName) = 67
W/SensorService(  956): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  956): Listener[0] = com.htc.smartdim.sensor_eye@199971d6
W/SensorService(  956): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PMS     (  956): acquireWL(31d6010d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(97e98c2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(31d6010d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(97e98c2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/CalendarProvider2( 5884): wait end:false,
,D/AlarmManager(  956): ACTION_SCREEN_OFF,
,I/AlarmManager(  956): [AlarmQueuing] screen off now: 
I/AlarmManager(  956): [AlarmQueuing] data connection: true
I/AlarmManager(  956): [AlarmQueuing] wifi connection: false
,D/WifiDataStallTracker(  956): stopDataStallAlarm 
,I/SensorManager( 1220): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@289aaf34, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  956): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  956): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  956): pid=1220, uid=10041
,W/SensorService(  956): Active sensors: size = 4
W/SensorService(  956): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  956): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  956): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  956): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  956): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@289aaf34, eanble = 1, strlen(mName) = 57
W/SensorService(  956): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  956): Listener[0] = com.htc.smartdim.sensor_eye@199971d6
W/SensorService(  956): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@289aaf34
W/SensorService(  956): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  956): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5913 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/WifiDataStallTracker(  956): ENABLE_DATA_MONITOR_POLL false Token 0
,E/WifiStateMachine(  956): handleMessage: E msg.what=131167
E/WifiStateMachine(  956): processMsg: InitialState
,E/WifiStateMachine(  956):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  956):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  400): ParamSet string: screen_state=off
D/WifiStateMachine(  956): getWifiLinkLayerStats: WIFI is not enbled
D/WifiDisplayAdapter(  956): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  956):     Client/Owner: Client
D/WifiDisplayAdapter(  956):     GroupId: 
D/WifiDisplayAdapter(  956):     Passphrase: 
D/WifiDisplayAdapter(  956):     SessionId: 0
D/WifiDisplayAdapter(  956):     IP Address: }
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  956): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  956): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  956): handleScreenStateChanged Exit: false
E/WifiStateMachine(  956): handleMessage: X
E/WifiStateMachine(  956): handleMessage: E msg.what=131154
E/WifiStateMachine(  956): processMsg: InitialState
E/WifiStateMachine(  956):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  956): processMsg: DefaultState
E/WifiStateMachine(  956):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  956): handleMessage: X
D/WifiController(  956): handleMessage: E msg.what=155651
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
D/NetworkPolicy(  956): updateScreenOn: false
V/NetworkPolicy(  956): updateIfacesLocked()
D/NetworkManagementService(  956): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/GpsLocationProvider(  956): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1460): start background delete task...
,I/IntentController( 1220): receive(android.intent.action.SCREEN_OFF,1,false)
D/ContactMessageStore( 1460): size: 0 , 0
D/ContactMessageStore( 1460): Background delete complete
,D/PMS     (  956): acquireWL(2c6ea109): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1822 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  956): releaseWL(2c6ea109): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(36217f0e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1822 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  956): releaseWL(36217f0e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5913): MY_DEBUG = false
,I/RemoteViews( 1220): setHTCTheme(com.htc.updater,true,33751145)
,D/PMS     (  956): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  956): Setting HAL interactive mode to false done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  956): Setting HAL auto-suspend mode to true
D/SurfaceControl(  956): Excessive delay in setPowerMode(): 301ms
D/PMS     (  956): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  956): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputManager(  956): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/IntentController( 1220): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  956): screenObserver, isScreenOn=false
D/NfcService( 1478): ScreenObserver: OFF
D/StatusBarManagerService(  956): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  956): Disable input method client, pid=1518
D/HABCtrl (  956): TPE algorithm. remove timeout.
D/PMS     (  956): OOBE c monitor 11
,D/NfcService( 1478): applyRouting - 0
,D/SmartSyncUtils( 5913): isEpsOn(), nState = 0
D/PMS     (  956): acquireWL(fd744c5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1478 1027 null
D/NfcService( 1478): applyRouting -2
D/PMS     (  956): acquireWL(afa7e1a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5913 1000 null
,D/NfcService( 1478): applyRouting
D/NfcService( 1478): Ignore this applyRouting...
,D/PMS     (  956): releaseWL(fd744c5): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/RemoteViews( 1220): apply : com.htc.updater 1 19 1 36
,D/PMS     (  956): acquireWL(212fcd4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
,I/BatteryService(  956): n_update end
D/UsbnetService(  956): BroadcastReceiver::onReceive+
,D/PMS     (  956): releaseWL(212fcd4b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/PMS     (  956): runPSCheck
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  956): Checking...
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  956): << updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/PowerUI ( 1220): closing low battery warning: level=100
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  956): releaseWL(afa7e1a): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  956): Init customizeScreenOffDelayClass error,
,I/ClockController( 1220): stop clock update:screen off
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5913): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5913): isEpsOn(), nState = 0
,W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  956): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@199971d6
W/SensorService(  956): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  956): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  956): pid=956, uid=1000
W/SensorService(  956): Active sensors: size = 3
,W/SensorService(  956): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  956): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  956): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  956): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@199971d6, eanble = 0, strlen(mName) = 36
W/SensorService(  956): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  956): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@289aaf34
W/SensorService(  956): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  956): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  956): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  956): pid=956, uid=1000
W/SensorService(  956): Active sensors: size = 2
W/SensorService(  956): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  956): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  956): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@199971d6, eanble = 0, strlen(mName) = 36
W/SensorService(  956): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  956): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@289aaf34
W/SensorService(  956): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  956): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@199971d6
E/ActivityThread(  956): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@888dc57 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  956): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@888dc57 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  956): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003),
E/ActivityThread(  956): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  956): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  956): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  956): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  956): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  956): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  956): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  956): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  956): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  956): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  956): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  956): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  956): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  956): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PowerUsageList:PowerUsageHelper( 5913): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/ActivityManager(  956): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5945 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0,
D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5913): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5913): MY_DEBUG = false,
,D/Process (  956): killProcessQuiet, pid=5366,
I/ActivityManager(  956): Killing 5366:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/SmartSyncUtils( 5913): getMobilePolicyEnabled, result = true
,D/WifiService(  956): New client listening to asynchronous messages
E/WifiTrafficPoller(  956): ADD_CLIENT: 7
,I/ActivityManager(  956): Recipient 5366
,D/Process (  956): killProcessQuiet, pid=5591
,I/ActivityManager(  956): Killing 5591:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  956): releaseWL(174e2728): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  956): Recipient 5591
,I/CalendarProvider2( 5884): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5884): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  956): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5969 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  956): Killing 5613:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,D/Process (  956): killProcessQuiet, pid=5613
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5613
,W/ResourcesManager( 5969): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5969): onCreate
,D/ProviderChangeReceiver( 5969): ---------------------------------------------------
,D/ProviderChangeReceiver( 5969): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  956): Killing 5387:com.android.settings/1000 (adj 15): empty #17
D/Process (  956): killProcessQuiet, pid=5387
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 5969): start to updateAlertNotification!
,I/ActivityManager(  956): Recipient 5387
,D/HtcAlertService( 5969): No fired or scheduled alerts
D/HtcAlertUtils( 5969): -- cancelReminderNotification --
,D/HtcAlertUtils( 5969): broadcastExistReminder!,
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1220): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  956): Killing 5014:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  956): killProcessQuiet, pid=5014
,D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5014
,D/PMS     (  956): acquireWL(363261e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 956 1000 WorkSource{1000},
V/AlarmManager(  956): sending alarm PendingIntent{b2bf327: PendingIntentRecord{1cf699d4 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1456908930785, Int=0
D/PMS     (  956): acquireWL(5d6477d): PARTIAL_WAKE_LOCK  *backup* 0x1 956 1000 null
D/PMS     (  956): releaseWL(363261e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  956): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  956): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  956): releaseWL(5d6477d): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/ContactMessageStore( 1460): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1460): MSG_NOTIFY_CS_TO_SYNC <<,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  956): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  956): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  956): acquireWL(db2b672): PARTIAL_WAKE_LOCK  *alarm* 0x1 956 1000 WorkSource{10024},
V/AlarmManager(  956): sending alarm PendingIntent{16da9ac3: PendingIntentRecord{c0d7f40 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142233, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{2a04de79: PendingIntentRecord{1fe2462a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=150466, Int=0,
,D/libc    (  956): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  956): sending alarm PendingIntent{24c80419: PendingIntentRecord{1ebf8cde android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145936, Int=0
D/libc    (  956): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  956): acquireWL(2a71c7be): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1905 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  956): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  956): releaseWL(db2b672): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/libc    (  956): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  956): [NET] android_getaddrinfo_proxy+
D/libc    (  956): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  956): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1905): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1905): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1905): [NET] android_getaddrinfo_proxy+
D/libc    ( 1905): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1905): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  956): releaseWL(2a71c7be): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  956): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  956): acquireWL(3842201f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
D/UsbnetService(  956): BroadcastReceiver::onReceive+
I/BatteryService(  956): n_update end
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): releaseWL(3842201f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/WifiController(  956): handleMessage: E msg.what=155652
D/PMS     (  956): runPSCheck
D/WifiController(  956): processMsg: ApStaDisabledState
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): processMsg: DefaultState
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: X
D/PowerUI ( 1220): closing low battery warning: level=100
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  956): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1460): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  956): acquireWL(10eb4f6c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152490, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{3febe935: PendingIntentRecord{2c7ea1ca android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=198128, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{24c80419: PendingIntentRecord{1ebf8cde android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=210483, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{33729f3b: PendingIntentRecord{36f3f658 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=183807, Int=0
,D/libc    (  956): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  956): [NET] android_getaddrinfofornet-, err=8
D/libc    (  956): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  956): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  956): [NET] android_getaddrinfo_proxy+
D/libc    (  956): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  956): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  956): acquireWL(1afee3b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1905 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): releaseWL(1afee3b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  956): releaseWL(10eb4f6c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1424): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@30b31b2
,D/Process (  956): killProcessQuiet, pid=4560
I/ActivityManager(  956): Killing 4560:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 4560
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  956): acquireWL(33cd1096): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(33cd1096): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  956): updateBatteryInfo
D/NotificationService(  956): plugged=true pluggin=true
D/PMS     (  956): runPSCheck
D/HtcPowerSaver(  956): Checking...,
I/HtcPowerSaver(  956): >> updateStatus
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  956): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  956): << updateStatus
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  956): battery changed pluggedType: 2
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: ApStaDisabledState
,D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  956): acquireWL(3361f417): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000},
V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212491, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{19de2004: PendingIntentRecord{1fe2462a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=269689, Int=0
D/PMS     (  956): acquireWL(386d09ed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1905 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1905): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1905): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1905): [NET] android_getaddrinfo_proxy+
D/libc    ( 1905): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1905): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  956): releaseWL(3361f417): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/PMS     (  956): releaseWL(386d09ed): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  956): acquireWL(19c1a022): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(19c1a022): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  956): updateBatteryInfo
D/PMS     (  956): runPSCheck
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  956): >> updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): << updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  956): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  956): battery changed pluggedType: 2
,D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  956): acquireWL(3287bab3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): releaseWL(3287bab3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/NotificationService(  956): plugged=true pluggin=true
D/WifiController(  956): handleMessage: E msg.what=155652
D/PMS     (  956): runPSCheck
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): handleMessage: X
I/HtcPowerSaver(  956): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): << updateStatus
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
,D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1905): Explicit concurrent mark sweep GC freed 15446(850KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.294ms total 77.561ms,
,I/GLSUser ( 1905): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1905): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1905): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1905): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1905): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1220): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1220): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 1905): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1905): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1905): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1905): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5413): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5413): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5413): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): apply : com.google.android.gms 0 19 8 40,
,W/System  ( 5413): Ignoring header User-Agent because its value was null.
,D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5413): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5413): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5413): [NET] android_getaddrinfo_proxy+
D/libc    ( 5413): [NET] android_getaddrinfo_proxy get netid:0,
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5413): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  956): Explicit concurrent mark sweep GC freed 24924(1390KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 18MB/27MB, paused 1.932ms total 184.552ms,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  956): acquireWL(a31485d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(a31485d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  956): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): handleMessage: E msg.what=155652
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  956): handleMessage: X
I/HtcPowerSaver(  956): << updateStatus
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  956): acquireWL(2ff655d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(2ff655d2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  956): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/WifiController(  956): battery changed pluggedType: 2
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): runPSCheck
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  956): acquireWL(2c74b6a3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000},
,V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=272491, Int=0,
V/AlarmManager(  956): sending alarm PendingIntent{1ebf0d59: PendingIntentRecord{393ffd1e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1456909148798, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{29219ff: PendingIntentRecord{365af3cc com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1456909201942, Int=1800000
,V/AlarmManager(  956): sending alarm PendingIntent{36ca2615: PendingIntentRecord{1fe2462a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=508121, Int=0
,D/PMS     (  956): acquireWL(34eacd2a): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4211 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  956): acquireWL(302980b8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1905 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,D/PMS     (  956): acquireWL(2d340e91): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4211 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1905): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  956): releaseWL(34eacd2a): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1905): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1905): [NET] android_getaddrinfo_proxy+
D/libc    ( 1905): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1905): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  956): releaseWL(302980b8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  956): releaseWL(2c74b6a3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,I/EventLogService( 4211): Aggregate from 1456907401854 (log), 1456907401854 (data),
,D/PMS     (  956): releaseWL(2d340e91): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  956): acquireWL(f7a02cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(f7a02cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  956): handleMessage: X
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  956): acquireWL(3b5bd782): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000},
V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=512491, Int=0
,I/ActivityManager(  956): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6007 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  956): sending alarm PendingIntent{32508e93: PendingIntentRecord{106faed0 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1456909359938, Int=0
,D/WeatherUtility( 1220): Weather sync is On,
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
D/PMS     (  956): releaseWL(3b5bd782): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,E/cutils-trace( 6030): Error opening trace file: Permission denied (13),
I/dex2oat ( 6030): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6030): dex2oat: override thread count:4
,I/dex2oat ( 6030): dex2oat took 709.994ms (threads: 4)
,I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6007): ApplicationMonitor {226042f2}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6007): PnsModel {6c835fd}: update(): Update registration caused by: alarm
,I/PushClient( 6007): PnsConfigModel {1f6b26d8}: <init>(): Use dm-client for provisioning.
,W/System.err( 6007): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6007): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6007): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6007): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  956): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6037 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6037): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6037 dbg=false s=true,
,I/DeviceManagement( 6037): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6037): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6037): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6037): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6037): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2cd93254] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6037): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6037): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6037): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6037): SessionStateController: Checking invariants...
,I/DeviceManagement( 6037): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6037): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6037): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6037): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2cd93254]
,I/DeviceManagement( 6037): WorkflowService: Stopping workflow service,
,D/Process (  956): killProcessQuiet, pid=5644
I/ActivityManager(  956): Killing 5644:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5644
,I/PushClient( 6007): PnsModel {6c835fd}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  956): killProcessQuiet, pid=5483
I/ActivityManager(  956): Killing 5483:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
D/Process (  956): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  956): Recipient 5483
,D/PMS     (  956): acquireWL(205e393d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(205e393d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): handleMessage: E msg.what=155652
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): handleMessage: X
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  956): << updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1460): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1460): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1460): sku_id=118
D/ContactMessageStore( 1460): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1460): start background delete task...
,D/ContactMessageStore( 1460): size: 0 , 0
,D/ContactMessageStore( 1460): Background delete complete
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  956): acquireWL(3fbd2532): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  956): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  956): releaseWL(3fbd2532): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): runPSCheck
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: ApStaDisabledState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  956): processMsg: DefaultState
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1905): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1905): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1905): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1905): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1905): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1905): 	,at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196),
W/GLSActivity( 1905): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1905): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5413): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5413): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5413): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5413): Ignoring header User-Agent because its value was null.
,D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5413): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5413): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5413): [NET] android_getaddrinfo_proxy+
D/libc    ( 5413): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5413): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1220): reapply : com.google.android.gms 4 40
,D/PMS     (  956): acquireWL(263570c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(263570c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  956): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  956): runPSCheck
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  956): Checking...
D/WifiController(  956): handleMessage: E msg.what=155652
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): processMsg: DefaultState
D/PowerUI ( 1220): closing low battery warning: level=100
D/WifiController(  956): handleMessage: X
I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  956): << updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1905): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1905): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1905): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1905): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1905): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1905): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1905): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1905): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): reapply : com.google.android.gms 3 40,
E/PlayEventLogger( 5413): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 5413): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5413): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5413): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5413): Ignoring header User-Agent because its value was null.
D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5413): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5413): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5413): [NET] android_getaddrinfo_proxy+
D/libc    ( 5413): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5413): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  956): acquireWL(151e2e06): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000}
V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=572491, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{6086992: PendingIntentRecord{1aab9f63 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805571, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{e839cc7: PendingIntentRecord{1fe2462a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=984974, Int=0
V/AlarmManager(  956): sending alarm PendingIntent{10b892f4: PendingIntentRecord{38bb1ef7 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456909766966, Int=0
D/PMS     (  956): acquireWL(38151a1d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1905 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1220): Weather sync is On,
W/ContextImpl( 5913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  956): releaseWL(151e2e06): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/libc    ( 1905): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1905): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1905): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1905): [NET] android_getaddrinfo_proxy+
D/libc    ( 1905): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1905): [NET] android_getaddrinfo_proxy-, NODATA
,D/PowerUsageList:PowerUsageHelper( 5913): MY_DEBUG = false
,D/PMS     (  956): releaseWL(38151a1d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 5913): repeat time = 1456910692535
,I/PowerUsageList:PowerUsageHelper( 5913): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 5913): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5913): calcPower(), no data
,D/PMS     (  956): acquireWL(6933e63): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 956 1000 WorkSource{1000},
V/AlarmManager(  956): sending alarm PendingIntent{29ac9d7d: PendingIntentRecord{22295472 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992492, Int=0
,V/AlarmManager(  956): sending alarm PendingIntent{d45ea60: PendingIntentRecord{1a6e3b19 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456909819883, Int=0
,D/SmartSyncUtils( 5913): isEpsOn(), nState = 0,
,D/PMS     (  956): acquireWL(2546f7de): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5913 1000 null
,D/PMS     (  956): releaseWL(6933e63): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1220): Weather sync is On
W/WeatherTimeKeeper( 1220): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 5913): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5913): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5913): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 5913): SettingOnTime = 1456984800000, randomSettingOnTime = 1456982153000
D/SmartSyncScreenOnOffTimeReceiver( 5913): SettingOffTime = 1456963200000, randomSettingOffTime = 1456966282000
,D/SmartSyncScreenOnOffTimeReceiver( 5913): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5913): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5913): bNightModeTurnOffOnce = false
,D/PMS     (  956): releaseWL(2546f7de): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  956): acquireWL(12715dbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null,
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(12715dbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  956): updateBatteryInfo
D/UsbnetService(  956): BroadcastReceiver::onReceive-
D/PMS     (  956): runPSCheck
D/WifiController(  956): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  956): processMsg: ApStaDisabledState
D/HtcPowerSaver(  956): Checking...
I/HtcPowerSaver(  956): >> updateStatus
,D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): battery changed pluggedType: 2
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  956): acquireWL(258f4c8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 956 1000 null
I/BatteryService(  956): n_update end
D/PMS     (  956): releaseWL(258f4c8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  956): updateBatteryInfo
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  956): plugged=true pluggin=true
D/UsbnetService(  956): BroadcastReceiver::onReceive+
D/WifiController(  956): battery changed pluggedType: 2
D/UsbnetService(  956): onReceive BATTERY_CHANGED
D/PMS     (  956): runPSCheck
D/UsbnetService(  956):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  956): Checking...
D/UsbnetService(  956): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  956): >> updateStatus
D/WifiController(  956): handleMessage: E msg.what=155652
D/WifiController(  956): processMsg: ApStaDisabledState
D/WifiController(  956): processMsg: DefaultState
D/WifiController(  956): handleMessage: X
,I/HtcPowerSaver(  956): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  956): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  956): User[0] Flushing usage stats to disk
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1905): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1905): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1905): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1905): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1905): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1905): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1905): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1905): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1905): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1905): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5413): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5413): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5413): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5413): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5413): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5413): Ignoring header User-Agent because its value was null.
D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5413): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5413): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5413): [NET] android_getaddrinfo_proxy+
D/libc    ( 5413): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5413): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1220): reapply : com.google.android.gms 5 40
,TIME-OUT KILL (timeout was 1200000ms)
```
