#### Test 61432979123161a_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main,
D/Messaging( 5751): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5751): networkCode: 
D/MessageCustFlag( 5751): sku_id=118
D/MmsConfig( 5751): SIE smsPri: null
D/MmsConfig( 5751): networkCode: 
D/MmsConfig( 5751): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 5751): startAsyncQueryReports ---
D/SettingsManager( 5751): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1c96f93a
D/MmsAsyncWorkHandler( 5751): 
D/MmsAsyncWorkHandler( 5751): HM tk = 20001
D/ReportIndicatorCache( 5751): MSG_QUERY_REPORTS >>
D/Messaging( 5751): mNeedToUpdateDate2 start
D/DraftCache( 5751): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5751): [DraftCache/1] refresh
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1468):  slotId = -1000
D/MmsSmsV2Provider( 1468): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/Messaging( 5751): mccmnc> 
D/MmsConfig( 5751): networkCode: 
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1468): sku_id=118
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1468):  slotId = -1000
D/MmsSmsV2Provider( 1468): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/Messaging( 5751): ViewCache CreatePreloadOnlyConversationList
D/DraftCache( 5751): [DraftCache/131] rebuildCache
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1468):  slotId = -1000
D/MmsSmsV2Provider( 1468): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/PhoneStorageUtil( 5751): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5751): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5751): createReceiver
D/MessageCustFlag( 5751): sense_version=6.0
D/Jerry   ( 5751): start to preload cursor >>>>>>>
D/TelephUtils( 1468): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1468): Update uri=content://mms, match=0
V/MmsProvider( 1468): selection=st=129 AND m_type!=134
D/Messaging( 5751): Reset downloading state: 0
V/MmsSystemEventReceiver( 5751): TransactionService is going to be woken up.
V/TransactionService( 5751): 1-Creating TransactionService
V/TransactionService( 5751): onStartCommand: 1
D/MmsSystemEventReceiver( 5751): unRegisterForConnectionStateChanges
V/TransactionService( 5751): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5751): Loading previous transactions.
I/art     (  955): Explicit concurrent mark sweep GC freed 23553(1215KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.894ms total 165.576ms
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1468): device_type: 1
D/Messaging( 5751): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1468):  slotId = -1000
D/MmsSmsV2Provider( 1468): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TransactionService( 5751): Force clearing mTransactionList
D/TransactionService( 5751): Force set service start id to 1
V/TransactionService( 5751): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5751): unRegisterForConnectionStateChanges
D/TransactionService( 5751): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5751): Destroying TransactionService
V/TransactionService( 5751): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 5751): mNeedToUpdateDate2: false
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Jerry   ( 1468): URI_DRAFT
D/DraftCache( 5751): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1468):  slotId = -1000
D/DraftCache( 5751): [DraftCache/131] rebuildCache time: 12
D/MmsAsyncWorkHandler( 5751): 
D/MmsAsyncWorkHandler( 5751): HM tk = 20002
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1468): sku_id=118
D/Messaging( 5751): ViewCache CreatePreload
D/Messaging( 5751): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1468): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1468): sku_id=118
D/Cust_MMSMS( 5751): _has_set_default_values_2=true
D/MsgPreferenceUtils( 5751): def_index: 0
D/MsgPreferenceUtils( 5751): globalIndex = 1
D/MsgPreferenceUtils( 5751): phone state: true
D/MsgPreferenceUtils( 5751): sd state: false
D/MsgPreferenceUtils( 5751): vIndex = 0
E/cutils-trace( 5789): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5789): ====startRecUseTime====
D/htc.customization.log.level( 5789):  is 
W/CustomizationLogLevel( 5789): Level value is invalid, use default level 2
D/CustomizationManager( 5789):  Read ACC file spent 0.032 (s)
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5789): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5789): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5789): Parsing tag category name = system
I/CustomizationCIDLoader( 5789): Parsing tag category name = application
I/CustomizationCIDLoader( 5789): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5789): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5789): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5789): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5789): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5789): add string-array item, value = 42507
I/CustomizationCIDLoader( 5789): add string-array item, value = 21902
I/CustomizationCIDLoader( 5789): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5789): add string-array item, value = 23420
I/CustomizationCIDLoader( 5789): add string-array item, value = 22299
I/CustomizationCIDLoader( 5789): add string-array item, value = 24002
I/CustomizationCIDLoader( 5789): add string-array item, value = 23210
I/CustomizationCIDLoader( 5789): add string-array item, value = 23205
I/CustomizationCIDLoader( 5789): add string-array item, value = 23806
I/CustomizationCIDLoader( 5789): add string-array item, value = 23430
I/CustomizationCIDLoader( 5789): add string-array item, value = 23408
I/CustomizationCIDLoader( 5789): add string-array item, value = 27205
I/CustomizationCIDLoader( 5789): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5789): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5789):  Read CID file spent 0.071 (s)
D/CustomizationManager( 5789):  All configurations done spent 0.071 (s)
--------- beginning of system
I/ActivityManager(  955): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5789 on display 0
D/PMS     (  955): acquireHCC(1b4ccdfd): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 955 1000 null
D/PMS     (  955): acquireHCC(1524faf2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 955 1000 null
D/PMS     (  955): acquireWL(a9d4cf9): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 955 1000 null
I/AnimationUtil(  955): isHTCRecent(ThaliTest/Recent screens.)/6
I/FeedHostManager( 1521): [onPause]
I/FeedProviderManager( 1521): onPause
I/FeedHostManager( 1521): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3219a9e3
I/SocialFeedProvider( 1521): +onPause
I/SocialFeedProvider( 1521): -onPause
W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  955): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5825 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  955): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
I/TrimMemoryManager( 1521): [trimMemory] 20
,I/WebViewFactory( 5825): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5825): Time to load native libraries: 9 ms (timestamps 2817-2826),
,I/LibraryLoader( 5825): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5825): Binding Chromium to main looper Looper (main, tid 1) {1c96f93a},
I/LibraryLoader( 5825): Expected native library version number "",actual native library version number ""
,I/chromium( 5825): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5825): Initializing chromium process, singleProcess=true,
,W/art     ( 5825): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5825): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5825): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5825): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5825): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5825): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5825): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5825): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5825): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5825): Local Branch: 
I/Adreno-EGL( 5825): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5825): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5825):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  955): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  955): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fee6669:true
W/System.err(  955): java.lang.Throwable: stack dump
W/System.err(  955): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  955): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  955): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  955): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 5825): 627797766: getState() :  mService = null. Returning STATE_OFF,
,W/art     ( 5825): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5825): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 5825): CordovaWebView is running on device made by: HTC
,W/art     ( 5825): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 5825): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5825): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/FindExtension( 5825): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5825): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@f8c6742, mServedView=org.apache.cordova.engine.SystemWebView{54a4353 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@6542490,
,I/InputMethodManagerService(  955): Disable input method client, pid=1521
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  955): Enable input method client, pid=5825
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,D/PMS     (  955): releaseWL(a9d4cf9): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  955): Displayed com.test.thalitest/.MainActivity: +822ms,
,W/XT9_C   ( 1365): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1365): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1365): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1365): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 5825): Cannot call determinedVisibility() - never saw a connection for the pid: 5825
,D/JsMessageQueue( 5825): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5825): JniHelper::setJavaVM(0xab2188f8), pthread_self() = -1403789144,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5825): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c1124f2 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Advertise TX power level: 3
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@306efef9 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5825): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  955): New client listening to asynchronous messages,
E/WifiTrafficPoller(  955): ADD_CLIENT: 6
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5825): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5825): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5825): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5825): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5825): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5825): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  955): releaseHCC(1b4ccdfd): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  955): releaseHCC(1524faf2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5825): Initializing JXcore engine,
W/jxcore-log( 5825): JXcore engine is ready
,W/jxcore-log( 5825): Starting JXcore engine,
,W/jxcore-log( 5825): Platform android,
W/jxcore-log( 5825): 
W/jxcore-log( 5825): Process ARCH arm
W/jxcore-log( 5825): 
,I/jxcore-log( 5825): JXcore Cordova bridge is ready!,
I/jxcore-log( 5825): 
W/jxcore-log( 5825): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5825): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5825): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 5825): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5825): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/PMS     (  955): acquireWL(22b3e0e4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 955 1000 null
W/PluginManager( 5825): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1521): [onResume]
I/FeedProviderManager( 1521): onResume
I/SocialFeedProvider( 1521): +onResume
I/ConnectivityHelper( 1521): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1521): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1521): -onResume
,D/StatusBarManagerService(  955): setSystemUiVisibility(0x8700),
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
D/FindExtension( 1521): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1521): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  955): Disable input method client, pid=5825
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  955): Enable input method client, pid=1521
,W/IInputConnectionWrapper( 5825): reportFullscreenMode on inactive InputConnection
,D/PMS     (  955): releaseWL(22b3e0e4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  955): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  955): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  955): hiding MENU key
,I/ActivityManager(  955): Killing 5265:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=5265
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  955): Recipient 5265
,W/OpenGLRenderer( 1521): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 11 times.
,W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3157): handler message = 4011,
E/HtcModeClient( 3157): Check connection and retry 12 times.
,I/HtcModeClient( 3157): handler message = 4011,
,E/HtcModeClient( 3157): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3157): Don't start project servcice,
,D/HtcModeClient( 3157): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3157): connectState: CONNECTION_READY = false
D/SilentMusic( 3157): call stop,
D/HtcModeClient( 3157): close connection
W/HtcModeClient( 3157): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3157): read the terminate packet, so break
,D/Process (  955): killProcessQuiet, pid=3157
I/ActivityManager(  955): Killing 3157:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 3157
,I/ActivityManager(  955): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5882 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  955): acquireWL(34a1895a): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{10076}
V/AlarmManager(  955): sending alarm PendingIntent{363d178b: PendingIntentRecord{35b19068 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1456940267396, Int=60000
D/PMS     (  955): releaseWL(34a1895a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 5882): SMSBackupAgentService started,
D/SMSBackup( 5882): Checking restore status
,D/SMSBackup( 5882): Restore complete
D/SMSBackup( 5882): cancelCheckAlarm
,D/SMSBackup( 5882): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  955): killProcessQuiet, pid=5389,
I/ActivityManager(  955): Killing 5389:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5389,
,I/SensorManager(  955): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2fbf310f,
I/PMS     (  955): Going to sleep due to screen timeout (uid 1000)...
W/SensorService(  955): Following SensorService logs are not warning, just make sure they are printed
D/ActivityManager(  955): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1c5ee126 #9 A=.Prism U=0 sz=1}
W/SensorService(  955): disable: get sensor name = Accelerometer Sensor
W/PMS     (  955): mWirelessDisplayManager is null
W/SensorService(  955): pid=955, uid=1000
W/PMN     (  955): goingToSleep
W/SensorService(  955): Active sensors: size = 4
D/PMS     (  955): acquireWL(663a167): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 955 1000 null
W/SensorService(  955): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMS     (  955): mWirelessDisplayManager is still null
W/SensorService(  955): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  955): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  955): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  955): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2fbf310f, eanble = 0, strlen(mName) = 91
W/SensorService(  955): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  955): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1ea7e57
W/SensorService(  955): Listener[1] = com.htc.smartdim.sensor_eye@3c941d13
W/SensorService(  955): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  955): Sleeping (uid 1000)...
,D/XAN-DPS (  955): prepareColorFade 1
,W/HtcLockScreen( 1218): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMN     (  955): goingToSleep done
,I/FeedHostManager( 1521): [onPause]
I/FeedProviderManager( 1521): onPause
,I/FeedHostManager( 1521): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3219a9e3
I/SocialFeedProvider( 1521): +onPause
I/SocialFeedProvider( 1521): -onPause
,I/Adreno-EGL(  955): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL(  955): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  955): Build Date: 03/09/15 Mon
I/Adreno-EGL(  955): Local Branch: 
I/Adreno-EGL(  955): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  955): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  955):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  955): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5904 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/AlarmManager(  955): ACTION_SCREEN_ON
I/AlarmManager(  955): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  955): [AlarmQueuing] done recovering,
I/AlarmManager(  955): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  955): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  955): releaseWL(663a167): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/WifiStateMachine(  955): handleMessage: E msg.what=131167
E/WifiStateMachine(  955): processMsg: InitialState
E/WifiStateMachine(  955):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  955): processMsg: DefaultState
,E/WifiStateMachine(  955):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  955):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
,V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  955): handleMessage: E msg.what=155650
D/WifiController(  955): processMsg: ApStaDisabledState
D/NetworkPolicy(  955): updateScreenOn: false
D/WifiController(  955): processMsg: DefaultState
V/NetworkPolicy(  955): updateIfacesLocked()
D/WifiController(  955): handleMessage: X
D/NetworkManagementService(  955): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WifiStateMachine(  955): getWifiLinkLayerStats: WIFI is not enbled
W/ResourcesManager( 5904): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/WifiStateMachine(  955): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  955): handleScreenStateChanged Exit: true
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131154
E/WifiStateMachine(  955): processMsg: InitialState
E/WifiStateMachine(  955):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131127
E/WifiStateMachine(  955): processMsg: InitialState
E/WifiStateMachine(  955):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131129
E/WifiStateMachine(  955): processMsg: InitialState
E/WifiStateMachine(  955):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  955): handleMessage: X
D/GpsLocationProvider(  955): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1218): receive(android.intent.action.SCREEN_ON,1,false),
,I/CalendarProvider2( 5904): Created com.android.providers.calendar.CalendarAlarmManager@23b19d5c(com.htc.providers.calendar.HtcCalendarProvider@21ba3865),
,D/CalendarProvider2( 5904): wait start:true
D/PMS     (  955): acquireWL(399de398): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1796 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): acquireWL(32267f1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1796 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): releaseWL(399de398): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): releaseWL(32267f1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  955): prepareColorFade done,
D/XAN-DPS (  955): setBrightness to 0
,D/AlarmManager(  955): ACTION_SCREEN_OFF,
I/AlarmManager(  955): [AlarmQueuing] screen off now: 
I/AlarmManager(  955): [AlarmQueuing] data connection: true
I/AlarmManager(  955): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  955): stopDataStallAlarm 
,E/WifiDataStallTracker(  955): ENABLE_DATA_MONITOR_POLL false Token 0
,E/WifiStateMachine(  955): handleMessage: E msg.what=131167
,E/WifiStateMachine(  955): processMsg: InitialState
D/WifiDisplayAdapter(  955): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  955):     Client/Owner: Client
D/WifiDisplayAdapter(  955):     GroupId: 
D/WifiDisplayAdapter(  955):     Passphrase: 
D/WifiDisplayAdapter(  955):     SessionId: 0
D/WifiDisplayAdapter(  955):     IP Address: }
E/WifiStateMachine(  955):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
I/DisplayManagerService(  955): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/WifiStateMachine(  955): processMsg: DefaultState
V/ActivityManager(  955): Display changed displayId=0
I/SensorManager(  955): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@1ea7e57
E/WifiStateMachine(  955):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
W/SensorService(  955): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  955): disable: get sensor name = CM32181 Light sensor
E/WifiStateMachine(  955):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  955): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  955): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  955): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  955): handleScreenStateChanged Exit: false
E/WifiStateMachine(  955): handleMessage: X
E/WifiStateMachine(  955): handleMessage: E msg.what=131154
E/WifiStateMachine(  955): processMsg: InitialState
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/WifiStateMachine(  955):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  955): processMsg: DefaultState
E/WifiStateMachine(  955):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  955): handleMessage: X
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/WifiController(  955): handleMessage: E msg.what=155651
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
W/SensorService(  955): pid=955, uid=1000
W/SensorService(  955): Active sensors: size = 3
W/SensorService(  955): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  955): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  955): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  955): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@1ea7e57, eanble = 0, strlen(mName) = 66
W/SensorService(  955): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  955): Listener[0] = com.htc.smartdim.sensor_eye@3c941d13
W/SensorService(  955): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
D/NetworkPolicy(  955): updateScreenOn: false
V/NetworkPolicy(  955): updateIfacesLocked()
D/NetworkManagementService(  955): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 5904): wait end:false
,I/ActivityManager(  955): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5933 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/SensorManager( 1218): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3485e7c5, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
,W/SensorService(  955): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  955): enable: get sensor name = hTC Gesture Motion HIDI,
,W/SensorService(  955): pid=1218, uid=10041
W/SensorService(  955): Active sensors: size = 4
W/SensorService(  955): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  955): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  955): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  955): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  955): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3485e7c5, eanble = 1, strlen(mName) = 57
W/SensorService(  955): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  955): Listener[0] = com.htc.smartdim.sensor_eye@3c941d13
W/SensorService(  955): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3485e7c5
W/SensorService(  955): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GpsLocationProvider(  955): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1468): start background delete task...
,I/IntentController( 1218): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  955): acquireWL(1ae4922d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1796 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(1ae4922d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  955): acquireWL(13aa2362): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1796 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(13aa2362): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1468): size: 0 , 0
D/ContactMessageStore( 1468): Background delete complete
,W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5933): MY_DEBUG = false
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145),
,D/SmartSyncUtils( 5933): isEpsOn(), nState = 0
,I/RemoteViews( 1218): apply : com.htc.updater 0 11 1 36,
D/SurfaceControl(  955): Excessive delay in setPowerMode(): 297ms
D/PMS     (  955): Setting HAL interactive mode to false
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  955): Setting HAL interactive mode to false done
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node,
D/PMS     (  955): Setting HAL auto-suspend mode to true
I/IntentController( 1218): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  955): Setting HAL auto-suspend mode done
I/InputManager(  955): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
W/HtcSystemUPManager(  955): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  955): acquireWL(7252429): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5933 1000 null
I/InputMethodManagerService(  955): screenObserver, isScreenOn=false
D/StatusBarManagerService(  955): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  955): Disable input method client, pid=1521
,D/HABCtrl (  955): TPE algorithm. remove timeout.
D/NfcService( 1482): applyRouting - 0
D/PMS     (  955): OOBE c monitor 11
D/NfcService( 1482): ScreenObserver: OFF
,D/PMS     (  955): acquireWL(3c8b13ae): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1482 1027 null
D/NfcService( 1482): applyRouting -2
D/NfcService( 1482): applyRouting
D/NfcService( 1482): Ignore this applyRouting...
D/PMS     (  955): acquireWL(dca954f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
D/PMS     (  955): releaseWL(3c8b13ae): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  955): n_update end
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/PMS     (  955): releaseWL(dca954f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  955): updateBatteryInfo
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  955): Checking...
,D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  955): >> updateStatus
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  955): Init customizeScreenOffDelayClass error,
,D/PowerUI ( 1218): closing low battery warning: level=100
,D/PMS     (  955): releaseWL(7252429): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/ClockController( 1218): stop clock update:screen off
,W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
D/SmartSyncUtils( 5933): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5933): isEpsOn(), nState = 0
,W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  955): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3c941d13
W/SensorService(  955): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  955): disable: get sensor name = Accelerometer Sensor,
,W/SensorService(  955): pid=955, uid=1000,
W/SensorService(  955): Active sensors: size = 3
W/SensorService(  955): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  955): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  955): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  955): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3c941d13, eanble = 0, strlen(mName) = 36
W/SensorService(  955): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  955): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3485e7c5
W/SensorService(  955): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  955): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  955): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  955): pid=955, uid=1000
W/SensorService(  955): Active sensors: size = 2
W/SensorService(  955): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  955): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  955): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3c941d13, eanble = 0, strlen(mName) = 36
W/SensorService(  955): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  955): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3485e7c5,
W/SensorService(  955): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/ActivityThread(  955): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3b9e5b50 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  955): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3b9e5b50 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  955): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  955): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  955): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  955): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  955): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  955): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  955): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  955): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  955): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  955): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  955): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  955): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  955): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  955): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  955): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  955): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  955): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  955): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/SensorManager(  955): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3c941d13
,I/ActivityManager(  955): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5967 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/PowerUsageList:PowerUsageHelper( 5933): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5933): calcPower(), no data
,D/SmartSyncUtils( 5933): getMobilePolicyEnabled, result = true
I/ActivityManager(  955): Killing 5610:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=5610
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  955): ADD_CLIENT: 7
D/WifiService(  955): New client listening to asynchronous messages
,I/ActivityManager(  955): Recipient 5610,
,D/PowerUsageList:PowerUsageHelper( 5933): MY_DEBUG = false,
,D/Process (  955): killProcessQuiet, pid=5632
I/ActivityManager(  955): Killing 5632:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CalendarProvider2( 5904): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5904): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  955): Recipient 5632
,I/ActivityManager(  955): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5992 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  955): Killing 5478:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  955): killProcessQuiet, pid=5478
,D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  955): releaseWL(1778449d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  955): Recipient 5478
,W/ResourcesManager( 5992): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 5992): onCreate
,D/ProviderChangeReceiver( 5992): ---------------------------------------------------
,D/ProviderChangeReceiver( 5992): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  955): killProcessQuiet, pid=5412
,I/ActivityManager(  955): Killing 5412:com.android.settings/1000 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 5992): start to updateAlertNotification!
,I/ActivityManager(  955): Recipient 5412
,D/HtcAlertService( 5992): No fired or scheduled alerts
,D/HtcAlertUtils( 5992): -- cancelReminderNotification --
,D/HtcAlertUtils( 5992): broadcastExistReminder!
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcUPManager( 1218): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ContactMessageStore( 1468): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1468): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  955): acquireWL(1478bcba): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119827, Int=0
,V/AlarmManager(  955): sending alarm PendingIntent{32c5376b: PendingIntentRecord{3c9d62c8 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1456940283944, Int=0
D/PMS     (  955): acquireWL(31cc2f61): PARTIAL_WAKE_LOCK  *backup* 0x1 955 1000 null
W/BackupManagerService(  955): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  955): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  955): releaseWL(31cc2f61): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  955): releaseWL(1478bcba): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/Process (  955): killProcessQuiet, pid=5065
,I/ActivityManager(  955): Killing 5065:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5065
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  955): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  955): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  955): acquireWL(3065ea86): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{10024},
V/AlarmManager(  955): sending alarm PendingIntent{127ddf47: PendingIntentRecord{3189e374 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142315, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{3abb609d: PendingIntentRecord{16c66317 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=147575, Int=0
,V/AlarmManager(  955): sending alarm PendingIntent{16069c71: PendingIntentRecord{14e13a56 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146036, Int=0
D/PMS     (  955): acquireWL(2fa62912): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms},
D/libc    (  955): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  955): releaseWL(3065ea86): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  955): [NET] android_getaddrinfofornet-, err=8
D/libc    (  955): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  955): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  955): [NET] android_getaddrinfo_proxy+
D/libc    (  955): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  955): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): releaseWL(2fa62912): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  955): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  955): acquireWL(2f28e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(2f28e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  955): BroadcastReceiver::onReceive+,
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/WifiController(  955): battery changed pluggedType: 2
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  955): updateBatteryInfo
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  955): runPSCheck
D/HtcPowerSaver(  955): Checking...
,I/HtcPowerSaver(  955): >> updateStatus
D/PowerUI ( 1218): closing low battery warning: level=100
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1468): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  955): acquireWL(351bc2e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000}
V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179827, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{2b726999: PendingIntentRecord{2139c45e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=196781, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{16069c71: PendingIntentRecord{14e13a56 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=207595, Int=0
,V/AlarmManager(  955): sending alarm PendingIntent{3e21703f: PendingIntentRecord{342a2d0c com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185261, Int=0
,D/libc    (  955): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  955): acquireWL(32f70655): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  955): [NET] android_getaddrinfofornet-, err=8
D/libc    (  955): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  955): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  955): [NET] android_getaddrinfo_proxy+
D/libc    (  955): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  955): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): releaseWL(32f70655): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): releaseWL(351bc2e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1436): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@26ae9587
,D/Process (  955): killProcessQuiet, pid=4587,
I/ActivityManager(  955): Killing 4587:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 4587
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  955): acquireWL(31d9c86a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
,I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(31d9c86a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  955): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  955): runPSCheck
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  955): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  955): acquireWL(c6d15b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(c6d15b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  955): updateBatteryInfo
D/PMS     (  955): runPSCheck
D/HtcPowerSaver(  955): Checking...
I/HtcPowerSaver(  955): >> updateStatus
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): processMsg: DefaultState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  955): handleMessage: X
D/WifiController(  955): battery changed pluggedType: 2
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  955): acquireWL(2fd30df8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000}
V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239827, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{30eeb2d1: PendingIntentRecord{16c66317 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=263520, Int=0
,D/PMS     (  955): acquireWL(7972837): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  955): sending alarm PendingIntent{1b2711a4: PendingIntentRecord{3fdaab0d com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1456940501892, Int=0
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): releaseWL(7972837): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  955): releaseWL(2fd30df8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/ActionCombine( 1878): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1878): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1878): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1878): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5437): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5437): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5437): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1218): apply : com.google.android.gms 0 14 5 40,
,W/System  ( 5437): Ignoring header User-Agent because its value was null.
,D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5437): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5437): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5437): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5437): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5437): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  955): acquireWL(36cc8d27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  955): n_update end
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  955): releaseWL(36cc8d27): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PMS     (  955): runPSCheck
D/WifiController(  955): handleMessage: E msg.what=155652
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): processMsg: ApStaDisabledState
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  955): acquireWL(3b442bd4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000}
V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359827, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{3b59717d: PendingIntentRecord{16c66317 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=573585, Int=0
,D/PMS     (  955): acquireWL(9579872): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/PMS     (  955): releaseWL(3b442bd4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, NODATA
D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/PMS     (  955): releaseWL(9579872): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  955): acquireWL(4ead4c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(4ead4c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): handleMessage: E msg.what=155652
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): handleMessage: X
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1468): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1468): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1468): sku_id=118
D/ContactMessageStore( 1468): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1468): start background delete task...
,D/ContactMessageStore( 1468): size: 0 , 0
,D/ContactMessageStore( 1468): Background delete complete
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  955): Explicit concurrent mark sweep GC freed 25814(1466KB) AllocSpace objects, 5(604KB) LOS objects, 33% free, 18MB/27MB, paused 1.831ms total 190.747ms
,I/art     ( 1878): Explicit concurrent mark sweep GC freed 19265(1089KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.189ms total 70.189ms
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1878): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1878): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1878): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5437): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5437): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5437): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5437): Ignoring header User-Agent because its value was null.
,D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5437): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5437): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5437): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5437): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
I/RemoteViews( 1218): reapply : com.google.android.gms 4 40
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5437): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): acquireWL(320eb3ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
,D/PMS     (  955): releaseWL(320eb3ed): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PMS     (  955): runPSCheck
D/WifiController(  955): handleMessage: E msg.what=155652
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): processMsg: ApStaDisabledState
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  955): acquireWL(21630222): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
,I/BatteryService(  955): n_update end
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/PMS     (  955): releaseWL(21630222): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  955): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  955): updateBatteryInfo
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  955): battery changed pluggedType: 2
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/PMS     (  955): runPSCheck
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  955): Checking...
D/UsbnetService(  955): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): handleMessage: E msg.what=155652
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  955): processMsg: ApStaDisabledState
I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  955): processMsg: DefaultState
,I/HtcPowerSaver(  955): << updateStatus
D/WifiController(  955): handleMessage: X
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  955): acquireWL(2a1a74b3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
D/UsbnetService(  955): BroadcastReceiver::onReceive+
I/BatteryService(  955): n_update end
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/PMS     (  955): releaseWL(2a1a74b3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  955): updateBatteryInfo
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  955): handleMessage: E msg.what=155652
D/NotificationService(  955): plugged=true pluggin=true
D/WifiController(  955): processMsg: ApStaDisabledState
D/PMS     (  955): runPSCheck
D/WifiController(  955): processMsg: DefaultState
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): handleMessage: X
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): battery changed pluggedType: 2
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1878): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1878): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1878): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5437): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5437): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5437): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5437): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1218): reapply : com.google.android.gms 4 40
D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5437): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5437): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5437): [NET] android_getaddrinfo_proxy+
D/libc    ( 5437): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5437): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): acquireWL(c91725d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 955 1000 WorkSource{1000}
,V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=599827, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{3bb437d2: PendingIntentRecord{1329f0a3 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1456941172608, Int=0
,D/SmartSyncUtils( 5933): isEpsOn(), nState = 0
,D/PMS     (  955): acquireWL(313f4fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5933 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5933): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5933): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5933): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 5933): SettingOnTime = 1456984800000, randomSettingOnTime = 1456983200000
D/SmartSyncScreenOnOffTimeReceiver( 5933): SettingOffTime = 1456963200000, randomSettingOffTime = 1456965327000
,D/SmartSyncScreenOnOffTimeReceiver( 5933): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5933): bNightMode = true,
,D/SmartSyncScreenOnOffTimeReceiver( 5933): bNightModeTurnOffOnce = false
D/PMS     (  955): releaseWL(313f4fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  955): releaseWL(c91725d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/PMS     (  955): acquireWL(37f7d759): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null,
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(37f7d759): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  955): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  955): battery changed pluggedType: 2
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/WifiController(  955): handleMessage: E msg.what=155652
D/WifiController(  955): processMsg: ApStaDisabledState
,D/WifiController(  955): processMsg: DefaultState
,D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  955): handleMessage: X
D/HtcPowerSaver(  955): updateBatteryInfo
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  955): runPSCheck
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  955): Checking...,
I/HtcPowerSaver(  955): >> updateStatus
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  955): acquireWL(3ff9ff1e): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{1000},
V/AlarmManager(  955): sending alarm PendingIntent{a2faf8a: PendingIntentRecord{2c85f9fb android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805702, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{32d03475: PendingIntentRecord{1a202c0a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1019828, Int=0
,D/Finsky  ( 5437): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  955): sending alarm PendingIntent{21d9c5cc: PendingIntentRecord{eba588c com.android.vending startService}}, i=null, t=0, cnt=1, w=1456940861273, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{bc59015: PendingIntentRecord{16c66317 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1037293, Int=0
,I/ActivityManager(  955): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6038 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  955): sending alarm PendingIntent{17dad11b: PendingIntentRecord{29c372b8 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1456941093779, Int=0
V/AlarmManager(  955): sending alarm PendingIntent{77c1891: PendingIntentRecord{3370c76e com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1456941121304, Int=0
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  955): acquireWL(738accd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1878 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1878): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1878): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1878): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1878): [NET] android_getaddrinfo_proxy+
,W/ContextImpl( 5933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/libc    ( 1878): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  955): releaseWL(738accd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1878): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  955): releaseWL(3ff9ff1e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On,
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
D/PowerUsageList:PowerUsageHelper( 5933): MY_DEBUG = false
,D/PowerUsageService( 5933): repeat time = 1456942097569,
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5437): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PowerUsageList:PowerUsageHelper( 5933): PowerProfile::POWER_SCREEN_FULL = 154.8,
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 5933): gen(), null == sipper.uidObj, userId = 0
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PowerUsageService( 5933): calcPower(), no data
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5437): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/cutils-trace( 6062): Error opening trace file: Permission denied (13)
I/dex2oat ( 6062): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6062): dex2oat: override thread count:4
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5437): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
D/Finsky  ( 5437): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5437): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5437): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1796): client connected with version: 7571000,
,I/dex2oat ( 6062): dex2oat took 675.849ms (threads: 4),
,I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): VersionCode:             148001224,
,I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6038): ApplicationMonitor {f3649c7}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6038): PnsModel {256b6f06}: update(): Update registration caused by: alarm
,I/PushClient( 6038): PnsConfigModel {ec304d5}: <init>(): Use dm-client for provisioning.
,W/System.err( 6038): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6038): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6038): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6038): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  955): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6072 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6072): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6072 dbg=false s=true,
,I/DeviceManagement( 6072): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6072): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6072): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6072): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6072): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2e1af5e1] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6072): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6072): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6072): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6072): SessionStateController: Checking invariants...
,I/DeviceManagement( 6072): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6072): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6072): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6072): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2e1af5e1],
,I/DeviceManagement( 6072): WorkflowService: Stopping workflow service,
,D/Process (  955): killProcessQuiet, pid=5664
I/ActivityManager(  955): Killing 5664:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5664
,I/PushClient( 6038): PnsModel {256b6f06}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  955): killProcessQuiet, pid=5507,
I/ActivityManager(  955): Killing 5507:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  955): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  955): Recipient 5507
,D/PMS     (  955): acquireWL(15301e8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 955 1000 WorkSource{10072},
V/AlarmManager(  955): sending alarm PendingIntent{1b13d9d5: PendingIntentRecord{2390d5ea com.android.vending startService}}, i=null, t=0, cnt=1, w=1456941212769, Int=0
D/PMS     (  955): releaseWL(15301e8c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5437): [562] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5437): [1] 5.onFinished: Installation state replication succeeded.,
,D/PMS     (  955): acquireWL(22d490db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
I/BatteryService(  955): n_update end
D/PMS     (  955): releaseWL(22d490db): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  955): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  955): runPSCheck
D/UsbnetService(  955): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): handleMessage: E msg.what=155652
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: ApStaDisabledState
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): processMsg: DefaultState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  955): handleMessage: X
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  955): acquireWL(3d069778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 955 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  955): n_update end
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  955): releaseWL(3d069778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  955): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  955): updateBatteryInfo
D/UsbnetService(  955): onReceive BATTERY_CHANGED
D/NotificationService(  955): plugged=true pluggin=true
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  955):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  955): BroadcastReceiver::onReceive-
D/PMS     (  955): runPSCheck
D/WifiController(  955): handleMessage: E msg.what=155652
D/HtcPowerSaver(  955): Checking...
D/WifiController(  955): processMsg: ApStaDisabledState,
I/HtcPowerSaver(  955): >> updateStatus
D/WifiController(  955): processMsg: DefaultState
D/WifiController(  955): battery changed pluggedType: 2
D/WifiController(  955): handleMessage: X
,I/HtcPowerSaver(  955): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  955): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  955): User[0] Flushing usage stats to disk
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1878): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1878): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1878): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1878): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1878): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1878): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1878): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1878): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1878): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5437): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5437): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5437): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5437): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5437): Ignoring header User-Agent because its value was null.
,D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5437): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5437): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5437): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5437): [NET] android_getaddrinfo_proxy+
D/libc    ( 5437): [NET] android_getaddrinfo_proxy get netid:0
,I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5437): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,TIME-OUT KILL (timeout was 1200000ms)
```
