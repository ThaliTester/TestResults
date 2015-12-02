#### Test 50388019193a02f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1467): handler message = 4011
E/HtcModeClient( 1467): Check connection and retry 3 times.
,E/cutils-trace( 2534): Error opening trace file: No such file or directory (2)
D/Messaging( 2486): mNeedToUpdateDate2 start
D/MmsConfig( 2486): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 2486): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 2486): 
D/MmsAsyncWorkHandler( 2486): HM tk = 20001
D/ReportIndicatorCache( 2486): MSG_QUERY_REPORTS >>
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1215):  phoneType = -1
D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
I/Messaging( 2486): mccmnc> 
D/DraftCache( 2486): [DraftCache/1] DraftCache.constructor
D/DraftCache( 2486): [DraftCache/1] refresh
D/MmsConfig( 2486): networkCode: 
D/Messaging( 2486): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/AccFlag ( 1215): sku_id=99
D/DraftCache( 2486): [DraftCache/202] rebuildCache
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1215):  phoneType = -1
D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1215):  phoneType = -1
D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 2486): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 2486): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 2486): createReceiver
D/Messaging( 2486): mNeedToUpdateDate2: false
D/MessageCustFlag( 2486): sense_version=6.0
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/Jerry   ( 1215): URI_DRAFT
D/Jerry   ( 2486): start to preload cursor >>>>>>>
D/DraftCache( 2486): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 2486): [DraftCache/202] rebuildCache time: 5
D/MmsAsyncWorkHandler( 2486): 
D/MmsAsyncWorkHandler( 2486): HM tk = 20002
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1215):  phoneType = -1
D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1215): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsProvider( 1215): Update uri=content://mms, match=0
V/MmsProvider( 1215): selection=st=129 AND m_type!=134
D/Messaging( 2486): Reset downloading state: 0
V/MmsSystemEventReceiver( 2486): TransactionService is going to be woken up.
D/Messaging( 2486): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1215):  phoneType = -1
V/TransactionService( 2486): 1-Creating TransactionService
V/TransactionService( 2486): onStartCommand: 1
D/MmsSystemEventReceiver( 2486): unRegisterForConnectionStateChanges
V/TransactionService( 2486): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 2486): Loading previous transactions.
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/AccFlag ( 1215): sku_id=99
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/AccFlag ( 1215): device_type: 1
D/Messaging( 2486): ViewCache CreatePreload
D/Messaging( 2486): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1215): sku_id=99
D/TransactionService( 2486): Force set service start id to 1
V/TransactionService( 2486): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 2486): unRegisterForConnectionStateChanges
D/Cust_MMSMS( 2486): _has_set_default_values_2=true
V/TransactionService( 2486): Destroying TransactionService
D/TransactionService( 2486): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 2486): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 2486): def_index: 0
D/MsgPreferenceUtils( 2486): globalIndex = 1
D/MsgPreferenceUtils( 2486): phone state: true
D/MsgPreferenceUtils( 2486): sd state: false
D/MsgPreferenceUtils( 2486): vIndex = 0
D/CustomizationManager( 2534): ====startRecUseTime====
D/htc.customization.log.level( 2534):  is 
W/CustomizationLogLevel( 2534): Level value is invalid, use default level 2
D/CustomizationManager( 2534):  Read ACC file spent 0.089 (s)
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2534): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2534): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2534): Parsing tag category name = system
I/CustomizationCIDLoader( 2534): Parsing tag category name = application
I/CustomizationCIDLoader( 2534): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2534): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2534): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2534): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2534): Parsing tag category name = Settings
D/CustomizationManager( 2534):  Read CID file spent 0.143 (s)
D/CustomizationManager( 2534):  All configurations done spent 0.144 (s)
W/HtcNativeFlag( 2534): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2534): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2534): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2534): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2534
D/PMS     (  905): acquireHCC(42f82320): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
W/asset   (  905): Copying FileAsset 0x6413ae78 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1121202368
D/PMS     (  905): acquireHCC(42ee29a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1250): [onPause]
I/FeedProviderManager( 1250): onPause
I/FeedHostManager( 1250): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@425e3b58
I/SocialFeedProvider( 1250): +onPause
I/SocialFeedProvider( 1250): -onPause
D/PMS     (  905): acquireWL(42e8dc90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2567 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
W/asset   ( 2567): Copying FileAsset 0x5c842428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1250): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 2567): Binding Chromium to main looper Looper (main, tid 1) {423dd200}
I/LibraryLoader( 2567): Expected native library version number "",actual native library version number ""
I/chromium( 2567): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2567): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e50080:true
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 2567): 1111436280: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): acquireWL(42bd9a68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(42eb6e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(42eb6e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2567): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2567): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2567): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2567): Local Branch: 
I/Adreno-EGL( 2567): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2567): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2567):                  aa63bbd948f41d15fc72f585e
D/MediaScanner( 2205):  prescan time: 155ms
D/MediaScanner( 2205):     scan time: 1714ms
D/MediaScanner( 2205): postscan time: 1ms
D/MediaScanner( 2205):    total time: 1870ms
D/MediaScanner( 2205): -----------------------------------------------------------------
D/MediaScanner( 2205): firstscan(media) time: 1324ms
D/MediaScanner( 2205): secondscan(non-media) time: 390ms
D/MediaScanner( 2205):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2205):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2205):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2205):  [Total]    File(Image+Video+Audio+Others) in database : 1411
D/MediaScannerServiceEx( 2205): [scan]-
D/MediaProvider( 2205): [delete][8]
D/MediaProvider( 2205): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2205): [recoverParentNodes] - 0
D/MediaProvider( 2205): [update][4]
D/MediaScannerServiceEx( 2205): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 2205): [updateImage]+
D/MediaScannerServiceEx( 2205): [updateImage]-0
W/chromium( 2567): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/TAG     ( 2205): mWakeLock.release() at scan()
D/MediaScannerServiceEx( 2205): [6] scan finished
D/HtcBroadcastReceiver( 1215): onReceive: android.intent.action.BOOT_COMPLETED
D/PMS     (  905): releaseWL(4300d688): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
W/dalvikvm( 2567): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2567): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2596 uid=10078 gids={50078}
W/dalvikvm( 2567): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2567): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2567): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2567): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2567): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2567): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2567): CordovaWebView is running on device made by: HTC
D/SMSBackup( 2596): Got ACTION_BOOT_COMPLETED event
D/SMSBackup( 2596): setCheckAlarm
D/SMSBackup( 2596): Next check is scheduled at 60s from now
D/Process (  905): killProcessQuiet, pid=2271
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2271:com.htc.fm/u0a24 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2271
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1215, uid=1001, userID:0
I/ActivityManager(  905): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2613 uid=10083 gids={50083, 3003, 5012, 1028, 1015}
,W/AwContents( 2567): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1250
W/ResourceType( 2567): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2567): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42423f80, mServedView=org.apache.cordova.engine.SystemWebView{423e9f18 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Enable input method client, pid=2567
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
W/AwContents( 2567): nativeOnDraw failed; clearing to background color.
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +328ms
I/[AppShowMeDebug]BootCompletedReceiver( 2613): received boot complete
I/[AppShowMeDebug]BootCompletedReceiver( 2613): push flag is false, skip check
D/PMS     (  905): releaseWL(42e8dc90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  905): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2633 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/Process (  905): killProcessQuiet, pid=2285
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2285:com.htc.HTCSpeaker/u0a26 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2285
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2647 uid=10086 gids={50086, 3003, 5012, 3001, 1028, 3002, 1015}
D/Process (  905): killProcessQuiet, pid=2298
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2298:com.google.android.onetimeinitializer/u0a31 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2298
I/chromium( 2567): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 2567): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LocationManagerService(  905): getProviders()=[passive]
I/ContactAccountLoggerTas( 2647): canRun() : Opted Out
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$ApplicationLaunchReceiver, state=1, flag=1, pid=2647, uid=10086, userID:0
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
W/dalvikvm( 2647): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
D/JsMessageQueue( 2567): Set native->JS mode to OnlineEventsBridgeMode
D/WifiService(  905): New client listening to asynchronous messages
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2647): Registered
I/MediaRouter( 2647): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/MediaRouter( 2647): getSelectedRoute
D/jxcore_app_log( 2567): JniHelper::setJavaVM(0x41f95010), pthread_self() = 1657883024
D/JX-Cordova( 2567): jxcore cordova android initializing
W/jxcore-log( 2567): Initializing JXcore engine
W/jxcore-log( 2567): JXcore engine is ready
W/jxcore-log( 2567): Starting JXcore engine
V/SmsReceiverService( 2486): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 2486): New incoming message, can't cancel notification now
D/MessagingNotification( 2486): newMsgCnt: 0, false
D/Process (  905): killProcessQuiet, pid=2335
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 2335:com.htc.csrecommend/u0a36 (adj 15): empty #17
D/PMS     (  905): releaseWL(42ffba48): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
I/ActivityManager(  905): Recipient 2335
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=2676 uid=10090 gids={50090, 3003, 5012, 1028}
I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
I/WorldClock.Global( 2676): isHtcDevice = true
D/PMS     (  905): acquireWL(426dacf0): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 2676 10090 null
W/jxcore-log( 2567): Platform android
W/jxcore-log( 2567): 
W/jxcore-log( 2567): Process ARCH arm
W/jxcore-log( 2567): 
W/WorldClock.AlarmService( 2676): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
I/WorldClock.AlarmUtils( 2676): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmUtils( 2676): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 2676): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1106): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(426dacf0): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/WorldClock.Global( 2676): isHtcDevice = true
I/ActivityManager(  905): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/jxcore-log( 2567): JXcore Cordova bridge is ready!
I/jxcore-log( 2567): 
W/jxcore-log( 2567): JXcore engine is started
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2696 uid=10091 gids={50091, 3003, 5012}
D/Process (  905): killProcessQuiet, pid=2347
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2347:com.htc.home.personalize/1000 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2347
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/OmaCPPushReceiverV2( 2696): initialCheck: sku=99, result=false
E/jxcore-log( 2567): >> HTC-HTC Desire 820
E/jxcore-log( 2567): 
I/jxcore-log( 2567): Total memory 1964650496
I/jxcore-log( 2567): 
I/jxcore-log( 2567): Free memory 798466048
I/jxcore-log( 2567): 
I/jxcore-log( 2567): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2567): 
I/jxcore-log( 2567): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2567): 
D/Process (  905): killProcessQuiet, pid=1896
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/jxcore-log( 2567): userPath [ 'www' ]
I/jxcore-log( 2567): 
I/jxcore-log( 2567): Size 720 1184
I/jxcore-log( 2567): 
I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2708 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  905): Killing 1896:com.htc.contacts/u0a44 (adj 15): empty #17
I/jxcore-log( 2567): Screen Brightness 142
I/jxcore-log( 2567): 
E/jxcore-log( 2567): Dummy Error Log.
E/jxcore-log( 2567): 
I/ActivityManager(  905): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2723 uid=10098 gids={50098, 3003, 5012}
D/Process (  905): killProcessQuiet, pid=2359
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2359:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2359
,I/ActivityManager(  905): Recipient 1896
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 2723): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=2723 dbg=false s=true
,I/DeviceManagement( 2723): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 2723): WorkflowService: Starting workflow service
,I/ActivityManager(  905): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 2723): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@424073e8] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 2723): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2723): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 2723): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2723): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 2723): BackgroundController: *** Update after boot...
,I/DeviceManagement( 2723): SessionStateController: Checking invariants...
,I/DeviceManagement( 2723): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 2723): SessionStateController: Checking invariants...
,I/DeviceManagement( 2723): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 2723): Perf: *** Cache update - start...
,I/DeviceManagement( 2723): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 2723): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 2723): EnabledAppController: Enabled app scan is pending...
,I/DeviceManagement( 2723): Perf: Scan enabled apps - start...
,I/DeviceManagement( 2723): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
,I/jxcore-log( 2567): getBuffer is called!!!!
I/jxcore-log( 2567): 
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
,I/DeviceManagement( 2723): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
,I/DeviceManagement( 2723): EnabledAppBuilder: Found 9 DM enabled apps.
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2723): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2723): Perf: Scan enabled apps - complete: 627 ms
I/DeviceManagement( 2723): Perf: *** Enabled app cache update - complete: 627 ms
I/DeviceManagement( 2723): Perf: *** Config cache update - start...
I/DeviceManagement( 2723): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2723): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2723): ConfigCacheController: *** Update config cache: updating 0 entries...
,I/DeviceManagement( 2723): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 2723): AlarmController: Scheduling TTL alarm for: 2015.12.03 at 11:49:00.516 CET (due to: com.htc.launcher)
,I/DeviceManagement( 2723): Perf: *** Config cache update - complete: 12 ms
I/DeviceManagement( 2723): Perf: *** Cache update - complete: 640 ms
,I/DeviceManagement( 2723): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@424073e8]
I/DeviceManagement( 2723): WorkflowService: Stopping workflow service
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2723, uid=10098, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2740 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2371
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2371:com.htc.aurora/u0a49 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2371
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(42f82320): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42ee29a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  905): Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexService: pid=2754 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/GAV2    ( 2740): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 2754): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 2754): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 2754): install
,I/MultiDex( 2754): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/MultiDex( 2754): loading existing secondary dex files
I/MultiDex( 2754): load found 3 secondary dex files
,I/MultiDex( 2754): install done
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2740, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2740, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2740, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2740, uid=10107, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/Gmail   ( 2740): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/dalvikvm( 2754): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2754): VFY: unable to resolve instance field 46
W/dalvikvm( 2754): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Gmail   ( 2740): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/JNIHelp ( 2754): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/Gmail   ( 2740): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2740): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2740, uid=10107, userID:0
,I/ActivityManager(  905): Resuming delayed broadcast,
,I/ActivityManager(  905): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
,I/ActivityManager(  905): Killing 2385:com.htc.aurora:remote/u0a49 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=2385
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ProviderInstaller( 2754): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Recipient 2385
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2789 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/NativeLibraryUtils( 2754): Install completed successfully. count=13 extracted=0
,D/PMS     (  905): acquireWL(431f4ef0): PARTIAL_WAKE_LOCK  Icing 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(431f4ef0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2754): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 2754): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
,W/dalvikvm( 2754): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
W/dalvikvm( 2754): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/PMS     (  905): acquireWL(42ff9d80): PARTIAL_WAKE_LOCK  Icing 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2754): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,I/Icing   ( 2754): Storage manager: low false usage 2.00MB avail 7.43GB capacity 7.85GB
,I/htcbackup-core( 2789): ModelRegistry: Loading model meta data from resources...
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,W/ContextImpl( 2789): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2789): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/ActivityManager(  905): Delay finish: com.htc.backup/.receiver.ScheduleBackupReceiver
D/Process (  905): killProcessQuiet, pid=2401
,I/DeviceManagement( 2723): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Killing 2401:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/DeviceManagement( 2723): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[android, com.htc.backup, com.qualcomm.privinit, com.htc.guide, com.htc.usage, com.htc.checkinprovider, com.htc.cirmodule, com.android.inputdevices, com.htc.drive.activator, com.htc.backupreset, com.android.providers.settings, com.htc.feedback, com.htc.autobot.cargps.provider, com.android.CSDFunctionG, com.htc.android.htcloglevel, com.htc.htcpowermanager, com.android.settings, com.htc.lockscreen, com.htc.smartdim, com.htc.android.htcsetupwizard, com.android.keychain, com.qualcomm.timeservice, com.htc.mirrorlinkserver, com.android.location.fused, com.htc.home.personalize]
,I/DeviceManagement( 2723): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  905): Delaying start of: ServiceRecord{42f6d948 u0 com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2401,
,D/MyReportAgent( 2509): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@423e6798
,I/DeviceManagement( 2723): WorkflowService: Starting workflow service
I/DeviceManagement( 2723): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@427085f0] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 2723): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 2723): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 2723): SessionStateController: Checking invariants...
,I/DeviceManagement( 2723): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 2723): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@427085f0]
,I/ActivityManager(  905): Resuming delayed broadcast
I/DeviceManagement( 2723): WorkflowService: Stopping workflow service
,W/ContextImpl( 2789): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/RemoteViews( 1106): com.htc.backup (true,33751552)
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{4242f380 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.htc.backup 3 9 7 15
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{42459bc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1106): com.htc.backup 0 4 4 4
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1106): com.htc.backup 1 1 2 4
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1106): com.htc.backup 1 1 1 4
,I/RemoteViews.Performance( 1106): com.htc.backup 1 11 18 21
,I/htcbackup-core( 2789): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2819 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,V/AlarmManager(  905): sending alarm PendingIntent{42b063a0: PendingIntentRecord{42d7b9c0 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=14, w=1440901414353, Int=604800000
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,W/dalvikvm( 2789): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews.Performance( 1106): com.htc.backup 1 2 15
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews( 1106): com.htc.backup (true,33751552)
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews.Performance( 1106): com.htc.backup 1 2 0 4
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1106): com.htc.backup 1 1 1 4
,I/RemoteViews( 1106): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1106): com.htc.backup 2 1 0 4
,I/RemoteViews.Performance( 1106): com.htc.backup 1 13 21
,D/UPolicy ( 2789): IUserBehaviorLoggingService reference is gotten !
,D/Process (  905): killProcessQuiet, pid=2415
I/ActivityManager(  905): Killing 2415:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(42bd9a68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Recipient 2415
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2754): updateResources: need to parse f{com.google.android.gms}
,W/dalvikvm( 2819): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 2819): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 2819): MmsConfig.loadMmsSettings
,W/dalvikvm( 2819): VFY: unable to resolve instance field 46
,W/dalvikvm( 2819): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 2819): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MmsCustomizationProvider( 2486): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2486): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 2819): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 2819): MmsConfig.loadFromDatabase
,E/Babel   ( 2819): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 2819): MmsConfig.loadFromResources
,E/Babel   ( 2819): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 2819): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2819, uid=10111, userID:0
,W/Settings( 2819): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2819, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2819, uid=10111, userID:0
,V/Babel   ( 2819): babel boot account: thalitester@gmail.com
,V/Babel   ( 2819): babel boot account: SMS
,I/ActivityManager(  905): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2847 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2428
,I/ActivityManager(  905): Killing 2428:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ProviderInstaller( 2819): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Recipient 2428
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  905): sending alarm PendingIntent{42d3cf20: PendingIntentRecord{42def798 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=49319, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42ed3a90: PendingIntentRecord{42e481f0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=49323, Int=0
,I/ActivityManager(  905): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2864 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  905): killProcessQuiet, pid=2451
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2451:com.htc.video/u0a57 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2451
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2754): Internal init done: storage state 0
,I/Icing   ( 2754): Post-init done
I/ActivityManager(  905): Delay finish: com.htc.htccupd/.HtcCupdReceiver
,I/HtcCupdXmlParser( 2864): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 2864): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/HtcCupdXmlParser( 2864): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,D/PMS     (  905): releaseWL(42ff9d80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=2468
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2468:com.htc.lmw/u0a60 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2468
,I/AlarmManager(  905): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
,I/AlarmManager(  905): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  905): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2884 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.htc.aurora
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Process (  905): killProcessQuiet, pid=2509
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2509:com.htc.reportagent/u0a66 (adj 15): empty #17
,D/AccTypeManager( 1305): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/ActivityManager(  905): Recipient 2509
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
W/AccTypeManager( 1305): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1305): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42f7b540
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@431c1100
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42f51ad8
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  905): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.sina.weibo
,I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
,I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
,E/ExternalAccountType( 1305): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/ResetNotifyBootCompleteReceiver( 1215): Receive bootcomplete intent
,W/ContextImpl( 1215): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2897 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/AppTag  ( 2897): getInstance(Context context)
,D/AppTag  ( 2897): getInstance(Context context)
,D/AppTag  ( 2897): onCreate()
,D/QXDM2SD:HtcNative( 1215): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2912 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2145
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2145:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2145
,W/PackageManager(  905): Unable to load service info ResolveInfo{42f465c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,I/HtcModeClient( 1467): handler message = 4011
,E/HtcModeClient( 1467): Check connection and retry 4 times.
,V/Settings:HtcSettingsApplication( 2912): [2912/2912] onCreate()
W/ContextImpl( 2912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2925 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/Process (  905): killProcessQuiet, pid=2596
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 2596:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2596
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 2925): -onCreate()
,I/ActivityManager(  905): Killing 2613:com.htc.showme/u0a83 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=2613
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/Settings:HtcSettingsApplication( 2925): [2925/2925] onCreate()
W/ContextImpl( 2925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Recipient 2613
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 2925): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 2925): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2925): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 2925): Cust_ConnectToPC   : spcsc>false
,D/        ( 2925): Cust_ConnectToPC   : IPT>true
,D/        ( 2925): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2925): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 2925): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2925): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2925): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2925): Cust_ConnectToPC   : spcsc>false
D/        ( 2925): Cust_ConnectToPC   : IPT>true
D/        ( 2925): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2925): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 2925): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2925): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2925): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 2925): setISNotification
D/SmartNS_Utility( 2925): usb_cable_connect = 1
,D/SmartNS_Utility( 2925): usb_denied = 0
I/SmartNS_PSService( 2925): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 2925): usb_cable_connect = 1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2925/1000)
D/SmartNS_Utility( 2925): usb_denied = 0
I/SmartNS_PSService( 2925): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2925/1000)
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/ActivityManager(  905): Killing 2633:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=2633
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Recipient 2633
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews( 1106): com.android.settings (true,33751552)
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{42437110 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.android.settings 1 11 0 10
I/ActivityManager(  905): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2940 uid=9987 gids={49987}
,I/RemoteViews( 1106): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1106): com.android.settings 1 0 10
,I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42eb69d0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42eb69d0, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@429f1a28
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42a1b7a0
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42eb69d0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42eb69d0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{430e3218 u0 ReceiverList{430e3088 905 system/1000/u0 local:430f8c68}}
,D/NfcUiccLockService( 2940): -- To check whether previous opened channel needed to be closed ...
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 3
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42eb69d0, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@429f1a28
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42a1b7a0
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42eb69d0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  905): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2956 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=2312
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2312:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2312
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2968 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2676
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2676:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2676
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 2968): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2968): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2968): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2968): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2968/10168)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 2968): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2968): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2968): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2968): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@42468e10 +
,I/Prism.WidgetManager( 1250): onLoadItems() +
,D/YouTube ( 2968): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 2968): Registered
,I/MediaRouter( 2968): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/YouTube ( 2968): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 2968): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449078373&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (2968/10168)
,D/libc    ( 2968): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2968): [NET] getaddrinfo-,err=8
D/libc    ( 2968): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2968): [NET] getaddrinfo-, 1
,D/libc    ( 2968): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 2968): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 2968): Error sending ping
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2968): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2968): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/YouTube ( 2968): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/MediaRouter( 2968): getSelectedRoute
D/YouTube ( 2968): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 2968): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2968): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2968): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2968/10168)
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  905): Resuming delayed broadcast
,E/Prism.WidgetManager( 1250): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1250): onLoadItems() -
,I/Prism.ItemManager( 1250): loadItems() com.htc.launcher.pageview.WidgetManager@42468e10 -
,W/dalvikvm( 2754): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 2754): Spent 26ms computing apk sha1.
,W/InstanceID/Rpc( 2754): Found 10029
,D/FileApkUtils( 2754): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 2754): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2754): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 2754): Beginning GMS chimera module scan
,W/asset   ( 2754): Copying FileAsset 0x651c0998 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 2754): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 2754): Beginning module configuration check
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/ChimeraCfgMgr( 2754): Module APKs unchanged, check complete
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,E/dalvikvm( 2754): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 2754): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2754/10029)
,D/PMS     (  905): acquireWL(431f6d30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(431c1d00): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2754 10029 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,E/dalvikvm( 2754): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 2754): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 2754): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/GCM     ( 2754): COMPAT: Multi user not supported
,D/PMS     (  905): acquireWL(431c2dd0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1333): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1333/10029)
D/PMS     (  905): acquireWL(431003e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(431f6d30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2754): Checkin interval check for package: unspecified last checkin: 1449076768227 min interval config: 0 actual interval: 1605831
,I/GCoreUlr( 2754): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/PhoneApp( 1215): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1215): -- N1 =0
,D/PhoneApp( 1215): -- N2 =0
,D/PhoneApp( 1215): -- N3 =0
,I/GCoreUlr( 1198): DispatchingService.onCreate()
,I/CheckinService( 2754): Disabling old GoogleServicesFramework version
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2754, uid=10029, userID:0
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
,D/SystemUpdateService( 2754): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
D/PMS     (  905): acquireWL(43208078): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
D/PMS     (  905): acquireWL(43205820): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2754, uid=10029, userID:0
,D/SystemUpdateService( 2754): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1358
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2754, uid=10029, userID:0
W/dalvikvm( 2754): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 3(ms)
D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2754, uid=10029, userID:0
V/AuthZen ( 2754): Handling intent: android.intent.action.BOOT_COMPLETED
D/WifiManager( 2567): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1362
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 5(ms)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: false pid=2567, uid=10396
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2754, uid=10029, userID:0
I/jxcore-log( 2567): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 2567): 
,I/jxcore-log( 2567): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2567): 
D/PMS     (  905): acquireWL(430cb840): PARTIAL_WAKE_LOCK  Icing 0x1 2754 10029 WorkSource{10029 com.google.android.gms}
D/AuthZenEventHandler( 2754): Handling event: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 2754): cancelUpdate (empty URL)
I/SystemUpdateService( 2754): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2754, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2754, uid=10029, userID:0
D/PMS     (  905): releaseWL(431c1d00): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  905): releaseWL(43208078): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2754): Checking schedule, now: 1449078374282 next: 1449599705191
I/CheckinService( 2754): active receiver: disabled
W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2754, uid=10029, userID:0
D/PMS     (  905): releaseWL(431003e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1198): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  905): releaseWL(430cb840): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2754): onDestroy
D/PMS     (  905): releaseWL(431c2dd0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 2754): Using Auth Proxy for data requests.
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2754): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1198, uid=10029, userID:0
,W/dalvikvm( 2754): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 2754): Fetching signing key...
,I/AuthZen ( 2754): Signing key fetched successfully!
,W/BaseAppContext( 2754): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 2754): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2754): Clearing transaction cache
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,I/GCoreUlr( 1198): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  905): acquireWL(42be3bb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42be3bb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1198): Unbound from all location providers
,W/dalvikvm( 1333): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(43205820): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Auth    ( 1333): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GCoreUlr( 1198): DispatchingService.onDestroy()
,I/GCoreUlr( 1198): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1198): Unbound from all location providers
D/PMS     (  905): acquireWL(42d98fd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42d98fd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(42f37770): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1333 10029 null
,W/dalvikvm( 1333): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/PMS     (  905): releaseWL(42f37770): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1333): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 2754): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1333): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3058 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,E/cutils-trace( 3049): Error opening trace file: No such file or directory (2)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(432088a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(432088a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  905): killProcessQuiet, pid=2696
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2696:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2696
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3058, uid=10074, userID:0
,D/CustomizationManager( 3049): ====startRecUseTime====
D/htc.customization.log.level( 3049):  is 
,W/CustomizationLogLevel( 3049): Level value is invalid, use default level 2
,D/Finsky  ( 3058): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3058/10074)
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3058/10074)
,D/CustomizationManager( 3049):  Read ACC file spent 0.056 (s)
,D/CIDMapFileReader( 3049): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 3049): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3049): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3049): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3049): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3049): Parsing tag category name = system
D/Finsky  ( 3058): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/CustomizationCIDLoader( 3049): Parsing tag category name = application
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
I/CustomizationCIDLoader( 3049): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3049): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3049): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3049): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3049): Parsing tag category name = Settings
D/CustomizationManager( 3049):  Read CID file spent 0.103 (s)
,D/CustomizationManager( 3049):  All configurations done spent 0.103 (s)
,W/Settings( 3058): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/HtcNativeFlag( 3049): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3049): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3049): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3049): Fail to get flag for type 'language', use default value: -1
,W/Settings( 3058): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3058): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3058, uid=10074, userID:0
,D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=3049, uid=2000 user=0
,D/Volley  ( 3058): [279] DiskBasedCache.clear: Cache cleared.
D/Process (  905): killProcessQuiet, pid=2708
,D/Ads     ( 3058): Skipping gmscore version check
,I/ActivityManager(  905): Killing 2708:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Volley  ( 3058): [286] DiskBasedCache.clear: Cache cleared.
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Finsky  ( 3058): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3058): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3058): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/asset   (  905): Copying FileAsset 0x62b01b40 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  905): killProcessQuiet, pid=2567
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Recipient 2708
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  905): Killing 2567:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  905): Force removing ActivityRecord{42cb4770 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  905): Skipping PackageSetting{42b54cd8 com.test.thalitest/10389} due to missing metadata
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=0: pkg removed
,D/Finsky  ( 3058): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/InputDispatcher(  905): channel '42c32e98 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '42c32e98 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowManager(  905): WINDOW DIED Window{42c32e98 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager(  905): Resuming delayed broadcast
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '42c32e98 com.example.hello.MainActivity (s)'
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
D/TetherSettings( 2925): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2925): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2925): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2925): Cust_ConnectToPC   : spcsc>false
D/        ( 2925): Cust_ConnectToPC   : IPT>true
D/        ( 2925): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2925): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2925): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2925): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2925): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PMS     (  905): acquireWL(431f4ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
I/PSReceiver( 2925): onReceive:android.intent.action.USER_PRESENT
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1305): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/SmartNS_PSService( 2925): onReceive:android.intent.action.USER_PRESENT
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/ContextImpl( 2925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(431f4ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/Settings( 2925): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/FeedHostManager( 1250): [onResume]
I/SmartNS_PSService( 2925):  defaultType:0
I/FeedProviderManager( 1250): onResume
I/SocialFeedProvider( 1250): +onResume
I/SocialFeedProvider( 1250): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1250): -onResume
,W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42d3dfb8 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  905): WIN DEATH: null
,I/ConnectivityHelper( 1250): [getCurrentConnectionType] no network connection
,W/AccTypeManager( 1305): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1250/10076)
D/AccTypeManager( 1305): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1250): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3106 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,E/ExternalAccountType( 1305): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/GAV2    ( 2740): Thread[GAThread,5,main]: No campaign data found.
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/GAv4-SVC( 2754): Google Analytics 8.3.01 is starting up.
,D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/browser ( 3106): Browser versionCode = 760001523 versionName = 7.0.2512153020
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/SWE_UI  ( 3106): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3106): Loading: swewebviewchromium
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 2567 uid 10396
I/InputMethodManagerService(  905): Enable input method client, pid=1250
,I/LibraryLoader( 3106): Time to load native libraries: 43 ms (timestamps 5441-5484)
I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3106): Initializing chromium process, renderers=9
,I/LibraryLoader( 3106): Expected native library version number "",actual native library version number ""
,I/chromium( 3106): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/PackageManager(  905): Unable to load service info ResolveInfo{42f4ad60 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,E/SharedPreferencesImpl( 3106): Couldn't rename file /data/data/com.htc.sense.browser/shared_prefs/com.htc.sense.browser_preferences.xml to backup file /data/data/com.htc.sense.browser/shared_prefs/com.htc.sense.browser_preferences.xml.bak
,E/SharedPreferencesImpl( 3106): Couldn't rename file /data/data/com.htc.sense.browser/shared_prefs/com.htc.sense.browser_preferences.xml to backup file /data/data/com.htc.sense.browser/shared_prefs/com.htc.sense.browser_preferences.xml.bak
,W/chromium( 3106): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3106): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3106): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3106): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3106): Local Branch: 
I/Adreno-EGL( 3106): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3106): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3106):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=2740
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1275): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  905): Killing 2740:com.google.android.gm/u0a107 (adj 15): empty #17
,I/SIMStateChangeReceiver( 1467): SIM state: ABSENT
,I/SIMStateChangeReceiver( 1467): phoneType = 0
I/SIMStateChangeReceiver( 1467): remove notification
,E/SQLiteLog( 1275): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1275): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.contacts/databases/contacts2.db, handle = 0x5ca24fa8
,W/CContactsProvider2( 1275): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.ContactsTransaction.startTransactionForDb(ContactsTransaction.java:133)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.AbstractContactsProvider.startTransaction(AbstractContactsProvider.java:264)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.AbstractContactsProvider.delete(AbstractContactsProvider.java:149)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.ContactsProvider2.delete(ContactsProvider2.java:2761)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.CContactsProvider2.delete(CContactsProvider2.java:48)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.HtcContactsProvider2.delete(HtcContactsProvider2.java:3345)
W/CContactsProvider2( 1275): ,	at com.android.providers.contacts.HtcContactsProvider2.bacthRemoveSIMContacts(HtcContactsProvider2.java:2828)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.HtcContactsProvider2$5$4.run(HtcContactsProvider2.java:3050)
E/SQLiteLog( 1275): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1275): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.contacts/databases/contacts2.db, handle = 0x5ca24fa8
,W/CContactsProvider2( 1275): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
W/CContactsProvider2( 1275): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.ContactsTransaction.startTransactionForDb(ContactsTransaction.java:133)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.AbstractContactsProvider.startTransaction(AbstractContactsProvider.java:264)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.AbstractContactsProvider.delete(AbstractContactsProvider.java:149)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.ContactsProvider2.delete(ContactsProvider2.java:2761)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.CContactsProvider2.delete(CContactsProvider2.java:48)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.HtcContactsProvider2.delete(HtcContactsProvider2.java:3345)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.HtcContactsProvider2.bacthRemoveSIMContacts(HtcContactsProvider2.java:2836)
W/CContactsProvider2( 1275): 	at com.android.providers.contacts.HtcContactsProvider2$5$4.run(HtcContactsProvider2.java:3050)
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3152 uid=10032 gids={50032, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2723
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3164 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 2723:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2740
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2486): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2486): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2486): onReceive()
D/ExchangePolicystatus( 2486): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2486): onReceive(): else
,D/Process (  905): killProcessQuiet, pid=2789
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1215): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  905): Killing 2789:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2723
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1106): can't get weather sync account
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3181 uid=10041 gids={50041}
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/WeatherRequest( 1106): request cur loc, but there is no sys cur
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3196 uid=10078 gids={50078}
,I/ActivityManager(  905): Recipient 2789
,W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Process (  905): killProcessQuiet, pid=2819
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Killing 2819:com.google.android.talk/u0a111 (adj 15): empty #17
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
V/AlarmManager(  905): sending alarm PendingIntent{428ca690: PendingIntentRecord{42ec55c8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21053, Int=1800000
V/AlarmManager(  905): sending alarm PendingIntent{42cd0420: PendingIntentRecord{42487628 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=49152, Int=259200000
V/AlarmManager(  905): sending alarm PendingIntent{42694208: PendingIntentRecord{42da2728 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50114, Int=0
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/SMSBackup( 3196): Got a database change event
I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3208 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  905): sending alarm PendingIntent{42d041f0: PendingIntentRecord{42dc2a58 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53737, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{42d91b00: PendingIntentRecord{42e1f1c8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1449054000000, Int=86400000
,W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  905): killProcessQuiet, pid=2847
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3220 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  905): Killing 2847:com.htc.backupreset/1000 (adj 15): empty #17
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
,I/ActivityManager(  905): Recipient 2819
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3234 uid=10091 gids={50091, 3003, 5012}
,D/CalendarApplication( 3220): onCreate
D/ProviderChangeReceiver( 3220): ---------------------------------------------------
,D/ProviderChangeReceiver( 3220): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3220): start to updateAlertNotification!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2847
W/ContextImpl( 2912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3249 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,E/SQLiteLog( 1467): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1467): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.calendar/databases/calendar.db, handle = 0x5ca04008
,D/AlertService( 3220): No fired or scheduled alerts
E/DatabaseUtils( 1467): Writing exception to parcel
E/DatabaseUtils( 1467): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DatabaseUtils( 1467): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DatabaseUtils( 1467): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1642)
E/DatabaseUtils( 1467): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1355)
E/DatabaseUtils( 1467): 	at com.android.providers.calendar.HtcFilterImpl_google.do_Query_INSTANCES(HtcFilterImpl_google.java:219)
E/DatabaseUtils( 1467): 	at com.android.providers.calendar.HtcFilterImpl_google.handle_Query(HtcFilterImpl_google.java:62)
E/DatabaseUtils( 1467): 	at com.android.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:126)
E/DatabaseUtils( 1467): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DatabaseUtils( 1467): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DatabaseUtils( 1467): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/DatabaseUtils( 1467): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 1467): 	at dalvik.system.NativeStart.run(Native Method)
W/dalvikvm( 2912): threadid=10: thread exiting with uncaught exception (group=0x41fa6e30)
,E/SQLiteDatabase( 3234): Failed to open database '/data/user/0/com.htc.mobiledata/databases/mobiledata.db'.
E/SQLiteDatabase( 3234): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3234): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3234): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3234): 	at com.htc.apputil.z.a(StatusInProvider.java:1011)
E/SQLiteDatabase( 3234): 	at com.htc.apputil.z.a(StatusInProvider.java:732)
E/SQLiteDatabase( 3234): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:191)
E/SQLiteDatabase( 3234): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:53)
E/SQLiteDatabase( 3234): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3234): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3234): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3234): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3234): 	at dalvik.system.NativeStart.run(Native Method)
,D/HtcAlertUtils( 3220): -- cancelReminderNotification --
,E/SQLiteOpenHelper( 3234): Couldn't open mobiledata.db for writing (will try read-only):
E/SQLiteOpenHelper( 3234): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3234): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3234): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3234): 	at com.htc.apputil.z.a(StatusInProvider.java:1011)
E/SQLiteOpenHelper( 3234): 	at com.htc.apputil.z.a(StatusInProvider.java:732)
E/SQLiteOpenHelper( 3234): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:191)
E/SQLiteOpenHelper( 3234): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:53)
E/SQLiteOpenHelper( 3234): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3234): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3234): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteOpenHelper( 3234): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteOpenHelper( 3234): 	at dalvik.system.NativeStart.run(Native Method)
,D/HtcAlertUtils( 3220): broadcastExistReminder!
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/SQLiteOpenHelper( 3234): Opened mobiledata.db in read-only mode
,E/AndroidRuntime( 2912): FATAL EXCEPTION: IntentService[HtcDndCommandService],
E/AndroidRuntime( 2912): Process: com.android.settings:remote, PID: 2912
E/AndroidRuntime( 2912): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2912): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2912): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2912): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:463)
E/AndroidRuntime( 2912): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/AndroidRuntime( 2912): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/AndroidRuntime( 2912): 	at com.android.settings.framework.core.sound.HtcDndUtils.getCalendarEvent(HtcDndUtils.java:310)
E/AndroidRuntime( 2912): 	at com.android.settings.framework.app.HtcDndCommandService.addCalendarTimeSlot(HtcDndCommandService.java:452)
E/AndroidRuntime( 2912): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleSlotData(HtcDndCommandService.java:511)
E/AndroidRuntime( 2912): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleEventTimer(HtcDndCommandService.java:530)
E/AndroidRuntime( 2912): 	at com.android.settings.framework.app.HtcDndCommandService.onHandleIntent(HtcDndCommandService.java:140)
E/AndroidRuntime( 2912): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2912): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2912): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.settings:remote
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,E/DatabaseUtils( 3234): Writing exception to parcel
E/DatabaseUtils( 3234): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/DatabaseUtils( 3234): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DatabaseUtils( 3234): 	at com.htc.apputil.z.b(StatusInProvider.java:1182)
E/DatabaseUtils( 3234): 	at com.htc.apputil.z.a(StatusInProvider.java:737)
E/DatabaseUtils( 3234): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:490)
E/DatabaseUtils( 3234): 	at com.htc.mobiledata.MobileDataProvider.update(MobileDataProvider.java:61)
E/DatabaseUtils( 3234): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/DatabaseUtils( 3234): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:252)
E/DatabaseUtils( 3234): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 3234): 	at dalvik.system.NativeStart.run(Native Method)
,D/MdScBoot( 3208): [a18.1.] 30@-184546 -> 40(X)
D/MdScBoot( 3208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/MdScBoot( 3208): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
D/MdScBoot( 3208): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
D/MdScBoot( 3208): 	at android.content.ContentProviderProxy.update(ContentProviderNative.java:615)
D/MdScBoot( 3208): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
D/MdScBoot( 3208): 	at com.htc.apputil.b.a(ContentProviderSession.java:149)
D/MdScBoot( 3208): 	at com.htc.apputil.y.a(StatusInProvider.java:507)
D/MdScBoot( 3208): 	at com.htc.apputil.y.a(StatusInProvider.java:79)
D/MdScBoot( 3208): 	at com.htc.mobiledata.services.c.a(SvcpBootComplete.java:273)
D/MdScBoot( 3208): 	at com.htc.apputil.k.b(RequestThreadManager.java:1096)
D/MdScBoot( 3208): 	at com.htc.apputil.k.a(RequestThreadManager.java:16)
D/MdScBoot( 3208): 	at com.htc.apputil.p.a(RequestThreadManager.java:1472)
D/MdScBoot( 3208): 	at com.htc.apputil.k.b(RequestThreadManager.java:1096)
D/MdScBoot( 3208): 	at com.htc.apputil.k.a(RequestThreadManager.java:1151)
D/MdScBoot( 3208): 	at com.htc.apputil.k.a(RequestThreadManager.java:16)
D/MdScBoot( 3208): 	at com.htc.apputil.l.handleMessage(RequestThreadManager.java:988)
D/MdScBoot( 3208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/MdScBoot( 3208): 	at android.os.Looper.loop(Looper.java:157)
D/MdScBoot( 3208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449078376278.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/Process (  905): killProcessQuiet, pid=2864
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 2864:com.htc.htccupd/u0a17 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=2884
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2884:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2864
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2884
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3249): can't get weather sync account
,W/WeatherRequest( 3249): request cur loc, but there is no sys cur
,W/Settings( 3249): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1250): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1250): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1250): com.htc.widget.weatherclock 1 9 17

```
