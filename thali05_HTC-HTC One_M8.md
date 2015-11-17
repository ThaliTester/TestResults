#### Test 503880196ac79ce_thali05_HTC-HTC One_M8 Logs


```--------- beginning of main
11-17 18:30:29.531  1121  1121 I RemoteViews: apply : com.nero.android.htc.sync 1 9 3 53
11-17 18:30:29.551   892  1534 D Process : killProcessQuiet, pid=5050
11-17 18:30:29.551   892  1534 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
--------- beginning of system
11-17 18:30:29.551   892  1534 W libprocessgroup: failed to open /acct/uid_10013/pid_5050/cgroup.procs: No such file or directory
11-17 18:30:29.751  5334  5334 D Messaging: supportCMAS(SIE)/init? false/true
11-17 18:30:29.751  5334  5334 D MmsConfig: networkCode: 
11-17 18:30:29.751  5334  5334 D MessageCustFlag: sku_id=99
11-17 18:30:29.761  5334  5334 D MmsConfig: SIE smsPri: null
11-17 18:30:29.761  5334  5334 D MmsConfig: networkCode: 
11-17 18:30:29.771  5334  5334 D MmsConfig: packageName: com.htc.vvm.att does not exist
11-17 18:30:29.771  5334  5545 D Messaging: mNeedToUpdateDate2 start
11-17 18:30:29.781  5334  5334 D ReportIndicatorCache: startAsyncQueryReports ---
11-17 18:30:29.781  5334  5351 D MmsAsyncWorkHandler: 
11-17 18:30:29.781  5334  5351 D MmsAsyncWorkHandler: HM tk = 20001
11-17 18:30:29.781  5334  5351 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
11-17 18:30:29.791  5334  5334 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@13efdd06
11-17 18:30:29.801  5334  5334 D DraftCache: [DraftCache/1] DraftCache.constructor
11-17 18:30:29.801  5334  5334 D DraftCache: [DraftCache/1] refresh
11-17 18:30:29.801  5334  5547 I Messaging: mccmnc> 
11-17 18:30:29.821  5334  5334 D MmsConfig: networkCode: 
11-17 18:30:29.821  1449  1464 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
11-17 18:30:29.821  1449  1464 D MmsSmsV2Provider:  slotId = -1000
11-17 18:30:29.821  1449  1464 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
11-17 18:30:29.821  1449  2098 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
11-17 18:30:29.821  5334  5550 D Messaging: ViewCache CreatePreloadOnlyConversationList
11-17 18:30:29.821  1449  2098 D MmsSmsV2Provider:  slotId = -1000
11-17 18:30:29.821  1449  2098 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
11-17 18:30:29.831  1449  1464 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
11-17 18:30:29.831  1449  1464 D AccFlag : sku_id=99
11-17 18:30:29.831  1449  1465 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
11-17 18:30:29.831  1449  1465 D MmsSmsV2Provider:  slotId = -1000
11-17 18:30:29.831  1449  1465 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
11-17 18:30:29.841  5334  5351 D DraftCache: [DraftCache/751] rebuildCache
11-17 18:30:29.841  1449  2391 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
11-17 18:30:29.841  1449  2391 D MmsSmsV2Provider:  slotId = -1000
11-17 18:30:29.841  1449  2391 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
11-17 18:30:29.841  5334  5546 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
11-17 18:30:29.851  5334  5545 D Messaging: mNeedToUpdateDate2: false
11-17 18:30:29.851  1449  1465 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
11-17 18:30:29.851  1449  1465 D Jerry   : URI_DRAFT
11-17 18:30:29.851  5334  5351 D DraftCache: hasDraft() = false mNeedNotifyChange = true
11-17 18:30:29.851  5334  5351 D DraftCache: [DraftCache/751] rebuildCache time: 6
11-17 18:30:29.851  5334  5351 D MmsAsyncWorkHandler: 
11-17 18:30:29.851  5334  5351 D MmsAsyncWorkHandler: HM tk = 20002
11-17 18:30:29.861  1449  2391 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
11-17 18:30:29.861  1449  2391 D AccFlag : sku_id=99
11-17 18:30:29.871  1449  1465 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
11-17 18:30:29.871  1449  1465 D AccFlag : sku_id=99
11-17 18:30:29.871  5334  5550 D MessageCustFlag: sense_version=6.0
11-17 18:30:29.871  5334  5550 D Jerry   : start to preload cursor >>>>>>>
11-17 18:30:29.881  1449  2391 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
11-17 18:30:29.881  1449  2391 D MmsSmsV2Provider:  slotId = -1000
11-17 18:30:29.881  5334  5334 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
11-17 18:30:29.881  5334  5334 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
11-17 18:30:29.881  5334  5334 D PhoneStorageUtil: createReceiver
11-17 18:30:29.891  5334  5550 D Messaging: ViewCache CreatePreload
11-17 18:30:29.891  5334  5550 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
11-17 18:30:29.891  1449  1465 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
11-17 18:30:29.891  1449  1465 V MmsProvider: Update uri=content://mms, match=0
11-17 18:30:29.891  1449  1465 V MmsProvider: selection=st=129 AND m_type!=134
11-17 18:30:29.891  5334  5554 D Messaging: Reset downloading state: 0
11-17 18:30:29.891  5334  5554 V MmsSystemEventReceiver: TransactionService is going to be woken up.
11-17 18:30:29.901  5334  5334 V TransactionService: 1-Creating TransactionService
11-17 18:30:29.901  5334  5550 D Cust_MMSMS: _has_set_default_values_2=true
11-17 18:30:29.911  5334  5550 D MsgPreferenceUtils: def_index: 0
11-17 18:30:29.911  5334  5550 D MsgPreferenceUtils: globalIndex = 1
11-17 18:30:29.911  5334  5550 D MsgPreferenceUtils: phone state: true
11-17 18:30:29.911  5334  5550 D MsgPreferenceUtils: sd state: false
11-17 18:30:29.911  5334  5550 D MsgPreferenceUtils: vIndex = 0
11-17 18:30:29.921  5334  5334 V TransactionService: onStartCommand: 1
11-17 18:30:29.921  5334  5334 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
11-17 18:30:29.921  5334  5556 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
11-17 18:30:29.921  5334  5556 V TransactionService: Loading previous transactions.
11-17 18:30:29.931  1449  1464 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
11-17 18:30:29.931  1449  1464 D AccFlag : device_type: 1
11-17 18:30:29.941  5334  5556 D TransactionService: Force set service start id to 1
11-17 18:30:29.941  5334  5556 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
11-17 18:30:29.941  5334  5556 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
11-17 18:30:29.941  5334  5556 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
11-17 18:30:29.941  5334  5334 V TransactionService: Destroying TransactionService
11-17 18:30:29.941  5334  5556 V TransactionService: 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
11-17 18:30:29.951  5445  5445 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
11-17 18:30:29.951  5445  5445 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
11-17 18:30:29.951  5407  5407 D ProviderChangeReceiver: ---------------------------------------------------
11-17 18:30:29.951  5407  5407 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
11-17 18:30:29.951  5407  5568 D HtcAlertService: start to updateAlertNotification!
11-17 18:30:29.951  5428  5428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
11-17 18:30:30.001  5407  5568 D HtcAlertService: No fired or scheduled alerts
11-17 18:30:30.001  5407  5568 D HtcAlertUtils: -- cancelReminderNotification --
11-17 18:30:30.001  5407  5568 D HtcAlertUtils: broadcastExistReminder!
11-17 18:30:30.001  1196  1196 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
11-17 18:30:30.011   892  1535 I ActivityManager: Killing 5190:com.google.android.apps.docs/u0a107 (adj 15): empty #17
11-17 18:30:30.011   892  1535 D Process : killProcessQuiet, pid=5190
11-17 18:30:30.011   892  1535 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
11-17 18:30:30.051   892  2142 I ActivityManager: Recipient 5190
11-17 18:30:30.091   892  2142 D Process : killProcessQuiet, pid=5190
11-17 18:30:30.091   892  2142 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:30.091   892  2142 W libprocessgroup: failed to open /acct/uid_10107/pid_5190/cgroup.procs: No such file or directory
11-17 18:30:30.141  1492  2595 I SocialFeedProvider: +disConnect socialManager
11-17 18:30:30.141  1492  2595 I SocialFeedProvider: disconnect socialManager
11-17 18:30:30.151  1492  2595 I SocialFeedProvider: -disConnect socialManager
,11-17 18:30:30.511  1764  1764 I ConfigService: onDestroy
11-17 18:30:30.781  5580  5589 E cutils-trace: Error opening trace file: No such file or directory (2)
11-17 18:30:30.811  5580  5580 D CustomizationManager: ====startRecUseTime====
11-17 18:30:30.811  5580  5580 D htc.customization.log.level:  is 
11-17 18:30:30.821  5580  5580 W CustomizationLogLevel: Level value is invalid, use default level 2
11-17 18:30:30.891  5580  5580 D CustomizationManager:  Read ACC file spent 0.046 (s)
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__001
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__E11
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__102
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__203
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__405
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__304
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__032
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__A48
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__K18
11-17 18:30:30.901  5580  5580 D CIDMapFileReader: Parsing tag item name = HTC__002
11-17 18:30:30.901  5580  5580 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
11-17 18:30:30.901  5580  5580 I CustomizationCIDLoader: Parsing tag category name = system
11-17 18:30:30.901  5580  5580 I CustomizationCIDLoader: Parsing tag category name = application
11-17 18:30:30.901  5580  5580 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
11-17 18:30:30.901  5580  5580 I CustomizationCIDLoader: Parsing tag category name = Settings
11-17 18:30:30.901  5580  5580 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:30.911  5580  5580 I CustomizationCIDLoader: Parsing tag category name = AudioService
11-17 18:30:30.911  5580  5580 I CustomizationCIDLoader: Parsing tag category name = ACC
11-17 18:30:30.911  5580  5580 D CustomizationManager:  Read CID file spent 0.094 (s)
11-17 18:30:30.911  5580  5580 D CustomizationManager:  All configurations done spent 0.094 (s)
11-17 18:30:30.921  5580  5580 E ActTriggerJNI: open library fail.
11-17 18:30:30.941  2234  2248 E MP-Decision: Update arg 2
11-17 18:30:30.941   892  1536 W asset   : Copying FileAsset 0xb8f5c3a8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:30.941   892  1536 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:30:30.941  2234  2248 E MP-Decision: Update arg 4
11-17 18:30:30.941   892  1022 D PMS     : acquireHCC(fd73d01): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 892 1000 null
11-17 18:30:30.941   892  1022 D PMS     : acquireHCC(30177a6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 892 1000 null
11-17 18:30:30.951  2234  2248 E MP-Decision: Update arg "0 190 240 240".
11-17 18:30:30.951  2234  2248 E MP-Decision: Update arg "0 75 400 400".
11-17 18:30:30.951   892   995 I AnimationUtil: isHTCRecent(HelloWorld/Recent screens.)/0
11-17 18:30:30.951   892  1536 D PMS     : acquireWL(6f9a83d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 892 1000 null
11-17 18:30:30.951  1492  1492 I FeedHostManager: [onPause]
11-17 18:30:30.951  1492  1492 I FeedProviderManager: onPause
11-17 18:30:30.951  1492  1492 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@190b03ac
11-17 18:30:30.951  1492  2169 I SocialFeedProvider: +onPause
11-17 18:30:30.951  1492  2169 I SocialFeedProvider: -onPause
11-17 18:30:30.961   892  1537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
11-17 18:30:30.991   892  1535 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5612 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:30:31.021   892   993 D StatusBarManagerService: setSystemUiVisibility(0x0)
11-17 18:30:31.021   892   993 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:31.021   892   993 D StatusBarManagerService: hiding MENU key
11-17 18:30:31.031  5612  5612 W asset   : Copying FileAsset 0xb8db3e70 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
11-17 18:30:31.051  1492  1492 I TrimMemoryManager: [trimMemory] 20
11-17 18:30:31.081  5612  5612 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
11-17 18:30:31.101  5612  5612 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9068-9070)
11-17 18:30:31.101  5612  5612 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:31.111  5612  5612 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17545be1}
11-17 18:30:31.111  5612  5612 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:31.111  5612  5612 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:31.121  5612  5612 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:30:31.131  5612  5612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:31.131  5612  5612 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:30:31.141  5612  5634 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:30:31.151  5612  5612 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:30:31.151  5612  5612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:31.151  5612  5612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:31.151  5612  5612 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
11-17 18:30:31.151  5612  5612 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:30:31.151  5612  5612 I Adreno-EGL: Build Date: 12/11/14 Thu
11-17 18:30:31.151  5612  5612 I Adreno-EGL: Local Branch: 
11-17 18:30:31.151  5612  5612 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
11-17 18:30:31.151  5612  5612 I Adreno-EGL: Local Patches: NONE
11-17 18:30:31.151  5612  5612 I Adreno-EGL: Reconstruct Branch: NOTHING
,11-17 18:30:31.201   892  1491 W System.err: java.lang.Throwable: stack dump
11-17 18:30:31.201   892  1491 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
11-17 18:30:31.201   892  1491 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
11-17 18:30:31.201   892  1491 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
11-17 18:30:31.201   892   994 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
11-17 18:30:31.201   892   994 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fc4e6d7:true
11-17 18:30:31.201   892  1491 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:31.201  5612  5646 D BluetoothAdapter: 299488541: getState() :  mService = null. Returning STATE_OFF
11-17 18:30:31.281  5612  5612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:31.291  5612  5612 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:30:31.291  5612  5612 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
11-17 18:30:31.301  5612  5612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:31.301  5612  5612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:31.341  5612  5612 D Atlas   : Validating map...
11-17 18:30:31.341  5612  5644 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-17 18:30:31.401  5612  5612 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3dd93542, mServedView=org.apache.cordova.engine.SystemWebView{36c1f953 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@13c0a290
11-17 18:30:31.401   892  2142 I InputMethodManagerService: Disable input method client, pid=1492
11-17 18:30:31.401   892  2142 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:30:31.401   892  2142 I InputMethodManagerService: Enable input method client, pid=5612
11-17 18:30:31.411   892   907 D PMS     : releaseWL(6f9a83d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
11-17 18:30:31.411   892   995 I ActivityManager: Displayed com.example.hello/.MainActivity: +454ms
11-17 18:30:31.451  1264  1264 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
11-17 18:30:31.451  1264  1264 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
11-17 18:30:31.451  1264  1264 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
11-17 18:30:31.451  1264  1264 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
11-17 18:30:31.491  5612  5612 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5612
11-17 18:30:31.501  5612  5612 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:30:31.561  5612  5612 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:30:31.581  5612  5651 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:30:31.631  3119  3158 I HtcModeClient: handler message = 4011
11-17 18:30:31.631  3119  3158 E HtcModeClient: Check connection and retry 5 times.
11-17 18:30:31.661  5612  5660 D jxcore_app_log: JniHelper::setJavaVM(0xb7d18b98), pthread_self() = -1191803424
11-17 18:30:31.661  5612  5660 D JX-Cordova: jxcore cordova android initializing
11-17 18:30:31.701  5612  5612 W jxcore-log: Initializing JXcore engine
11-17 18:30:31.701  5612  5612 W jxcore-log: JXcore engine is ready
11-17 18:30:31.711  5612  5612 W jxcore-log: Starting JXcore engine
,11-17 18:30:31.841  5612  5612 W jxcore-log: Platform android
11-17 18:30:31.841  5612  5612 W jxcore-log: 
,11-17 18:30:31.841  5612  5612 W jxcore-log: Process ARCH arm
11-17 18:30:31.841  5612  5612 W jxcore-log: 
,11-17 18:30:31.881  5612  5612 I jxcore-log: JXcore Cordova bridge is ready!,
11-17 18:30:31.881  5612  5612 I jxcore-log: 
11-17 18:30:31.881  5612  5612 W jxcore-log: JXcore engine is started
,11-17 18:30:31.941  5612  5612 E jxcore-log: >> HTC-HTC One_M8
11-17 18:30:31.941  5612  5612 E jxcore-log: 
,11-17 18:30:31.941  5612  5612 I jxcore-log: Total memory 1912020992
11-17 18:30:31.941  5612  5612 I jxcore-log: 
,11-17 18:30:31.941  5612  5612 I jxcore-log: Free memory 141709312
11-17 18:30:31.941  5612  5612 I jxcore-log: 
,11-17 18:30:31.941  5612  5612 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:31.941  5612  5612 I jxcore-log: 
11-17 18:30:31.941  5612  5612 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:31.941  5612  5612 I jxcore-log: 
,11-17 18:30:31.941  5612  5612 I jxcore-log: userPath [ 'www' ]
11-17 18:30:31.941  5612  5612 I jxcore-log: 
,11-17 18:30:31.941  5612  5612 I jxcore-log: Size 1080 1776,
11-17 18:30:31.941  5612  5612 I jxcore-log: 
11-17 18:30:31.951  5612  5612 I jxcore-log: Screen Brightness 142
11-17 18:30:31.951  5612  5612 I jxcore-log: 
,11-17 18:30:31.951  5612  5612 E jxcore-log: Dummy Error Log.
11-17 18:30:31.951  5612  5612 E jxcore-log: 
,11-17 18:30:32.181  5264  5288 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:32.201  4128  4128 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,11-17 18:30:32.461  5612  5612 I jxcore-log: getBuffer is called!!!!
11-17 18:30:32.461  5612  5612 I jxcore-log: 
,11-17 18:30:32.571  1680  5506 I SensorManager: unregisterListenerImpl++: listener = com.google.android.location.collectionlib.cm@16acafdc
,11-17 18:30:32.571   892  1324 W SensorService: Following SensorService logs are not warning, just make sure they are printed
11-17 18:30:32.571   892  1324 W SensorService: disable: get sensor name = Accelerometer Sensor
11-17 18:30:32.571   892  1324 W SensorService: pid=1680, uid=10025
11-17 18:30:32.571   892  1324 W SensorService: Active sensors: size = 3
11-17 18:30:32.571   892  1324 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=2)
11-17 18:30:32.571   892  1324 W SensorService: CM36282 Light sensor (handle=0x00000003, connections=1)
,11-17 18:30:32.571   892  1324 W SensorService: CM36282 Proximity sensor (handle=0x00000004, connections=1)
11-17 18:30:32.571   892  1491 W SensorService: SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@16acafdc, eanble = 0, strlen(mName) = 53
11-17 18:30:32.571   892  1491 W SensorService: Active Listeners: mActiveListeners.size() = 3
11-17 18:30:32.571   892  1491 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@1a70520f
11-17 18:30:32.571   892  1491 W SensorService: Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@32d62172
11-17 18:30:32.571   892  1491 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@bd9a2d5
11-17 18:30:32.571   892  1491 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,11-17 18:30:32.571   892  1446 D PMS     : acquireWL(e5677b6): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1680 10025 null
11-17 18:30:32.571   892  1446 D PMS     : releaseWL(177e060f): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
11-17 18:30:32.571   892  1262 D PMS     : releaseWL(e5677b6): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,11-17 18:30:32.571   892   908 D PMS     : acquireWL(e9cb7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1680 10025 null
,11-17 18:30:32.571   892  1534 D PMS     : releaseWL(396cf6e): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,11-17 18:30:32.571   892  2142 D PMS     : releaseWL(e9cb7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
11-17 18:30:32.571   892  1535 D PMS     : acquireWL(2682ac24): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1680 10025 null
,11-17 18:30:32.571   892  1142 D PMS     : releaseWL(1df76e9): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
,11-17 18:30:32.581   892  1536 D PMS     : acquireWL(3dee738d): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1680 10025 null
,11-17 18:30:32.581   892  1262 D PMS     : releaseWL(3dee738d): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,11-17 18:30:32.581   892  1446 D PMS     : acquireWL(31ca5942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1680 10025 WorkSource{10025 com.google.android.gms}
11-17 18:30:32.581   892  1535 D PMS     : releaseWL(31ca5942): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
11-17 18:30:32.581   892  1436 D PMS     : acquireWL(25664d53): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1680 10025 null
11-17 18:30:32.581   892  1324 D PMS     : releaseWL(25664d53): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,11-17 18:30:32.591   892  1262 D PMS     : releaseWL(2682ac24): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,11-17 18:30:32.711   479   479 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-17 18:30:32.941   892  1022 D PMS     : releaseHCC(fd73d01): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,11-17 18:30:32.941   892  1022 D PMS     : releaseHCC(30177a6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,11-17 18:30:32.941  2234  2248 E MP-Decision: Update arg 1
,11-17 18:30:33.371   892  1491 I art     : Explicit concurrent mark sweep GC freed 10828(519KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.466ms total 133.677ms,
,11-17 18:30:33.901   892  2142 D Process : killProcessQuiet, pid=4053,
11-17 18:30:33.901   892  2142 I ActivityManager: Killing 4053:com.android.defcontainer/u0a15 (adj 15): empty #17
,11-17 18:30:33.901   892  2142 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,11-17 18:30:33.921   892  1446 I ActivityManager: Recipient 4053,
,11-17 18:30:33.931   892  1446 D Process : killProcessQuiet, pid=4053,
11-17 18:30:33.931   892  1446 W libprocessgroup: failed to open /acct/uid_10015/pid_4053/cgroup.procs: No such file or directory,
11-17 18:30:33.931   892  1446 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:33.941   892  2106 I ActivityManager: Killing 5360:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
11-17 18:30:33.941   892  2106 D Process : killProcessQuiet, pid=5360,
11-17 18:30:33.941   892  2106 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,11-17 18:30:33.961   892  1491 I ActivityManager: Recipient 5360,
,11-17 18:30:33.981   892  1491 D Process : killProcessQuiet, pid=5360,
11-17 18:30:33.981   892  1491 W libprocessgroup: failed to open /acct/uid_10016/pid_5360/cgroup.procs: No such file or directory
11-17 18:30:33.981   892  1491 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:35.221   892  1446 D PMS     : acquireWL(39506690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 892 1000 null,
11-17 18:30:35.231  1196  1196 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
11-17 18:30:35.221   892  1446 I BatteryService: n_update end
11-17 18:30:35.231  1196  1196 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
11-17 18:30:35.221   892  1446 D PMS     : releaseWL(39506690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
11-17 18:30:35.231  1196  1196 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
11-17 18:30:35.231   892   892 D UsbnetService: BroadcastReceiver::onReceive+,
11-17 18:30:35.231   892   892 D NotificationService: plugged=true pluggin=true
11-17 18:30:35.231   892   892 D UsbnetService: onReceive BATTERY_CHANGED
11-17 18:30:35.231  1121  1121 D PowerUI : closing low battery warning: level=100
11-17 18:30:35.231   892   892 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
11-17 18:30:35.231  1121  1121 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
11-17 18:30:35.231   892   892 D UsbnetService: BroadcastReceiver::onReceive-
11-17 18:30:35.231   892  1078 D WifiController: battery changed pluggedType: 2
11-17 18:30:35.231   892  1010 D HtcPowerSaver: updateBatteryInfo
11-17 18:30:35.241  1121  1340 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,11-17 18:30:35.231   892   892 D PMS     : runPSCheck
11-17 18:30:35.231   892   892 D HtcPowerSaver: Checking...
11-17 18:30:35.231   892   892 I HtcPowerSaver: >> updateStatus
11-17 18:30:35.241   892   892 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
11-17 18:30:35.241   892   892 I HtcPowerSaver: << updateStatus,
,11-17 18:30:35.251   892  1262 D PMS     : acquireWL(9dbbb89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 892 1000 null
11-17 18:30:35.251   892  1262 I BatteryService: n_update end
11-17 18:30:35.251   892  1262 D PMS     : releaseWL(9dbbb89): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,11-17 18:30:35.291  1121  1121 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,11-17 18:30:36.671  3119  3158 I HtcModeClient: handler message = 4011,
,11-17 18:30:36.671  3119  3158 E HtcModeClient: Check connection and retry 6 times.,
,11-17 18:30:36.971   892   908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:30:36.971   892   908 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false,
,11-17 18:30:37.011   892  1078 D WifiService: New client listening to asynchronous messages
11-17 18:30:36.971   892   908 W Settings:Agent: MONITOR_LOG,
11-17 18:30:37.011   892  1491 D WifiService: setWifiEnabled: false pid=5612, uid=10380
11-17 18:30:36.971   892   908 W Settings:Agent: name: bluetooth_on,
11-17 18:30:37.011   892  1491 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:30:36.971   892   908 W Settings:Agent: value: 0,
11-17 18:30:37.011   892  1491 I WifiService: isSprintWifiRestricted(): false,
,11-17 18:30:36.971   892   908 W Settings:Agent: >> traceCallingStack()
,11-17 18:30:37.011   892  1491 I WifiService: isMdmWifiRestricted(): false
,11-17 18:30:36.971   892   908 W Settings:Agent: Process.myPid(): 892
11-17 18:30:37.041   892   907 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4128, uid=10025, userID:0
,11-17 18:30:36.971   892   908 W Settings:Agent: Process.myTid(): 908,
11-17 18:30:36.971   892   908 W Settings:Agent: Process.myUid(): 1000
,11-17 18:30:36.971   892   908 W Settings:Agent: 
,11-17 18:30:36.971   892   908 W Settings:Agent: 
11-17 18:30:36.971   892   908 W System.err: java.lang.Throwable: stack dump
,11-17 18:30:36.981   892   908 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
,11-17 18:30:36.981   892   908 W System.err: ,	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:30:36.981   892   908 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64),
11-17 18:30:37.051   892  1142 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4128, uid=10025, userID:0
11-17 18:30:36.981   892   908 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,11-17 18:30:36.981   892   908 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
11-17 18:30:36.981   892   908 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:30:36.981   892   908 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
11-17 18:30:36.981   892   908 W System.err: 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
11-17 18:30:36.981   892   908 W System.err: ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
11-17 18:30:36.981   892   908 W System.err: ,	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:37.051   892  1535 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4128, uid=10025, userID:0
11-17 18:30:36.981   892   908 W Settings:Agent: 
,11-17 18:30:36.981   892   908 W Settings:Agent: << traceCallingStack(): 13(ms),
11-17 18:30:36.991   892   994 D BluetoothManagerService: Message: MESSAGE_DISABLE
11-17 18:30:37.011   892   892 E WifiTrafficPoller: ADD_CLIENT: 7
11-17 18:30:37.011  5612  5612 D WifiManager: setWifiEnabled: Base Package Name=com.example.hello, uid=10380
11-17 18:30:37.011   892  1491 W Settings:Agent: MONITOR_LOG
11-17 18:30:37.011   892  1491 W Settings:Agent: name: wifi_on,
11-17 18:30:37.011   892  1491 W Settings:Agent: value: 0
11-17 18:30:37.011   892  1491 W Settings:Agent: >> traceCallingStack()
11-17 18:30:37.011   892  1491 W Settings:Agent: Process.myPid(): 892
11-17 18:30:37.011   892  1491 W Settings:Agent: Process.myTid(): 1491
11-17 18:30:37.011   892  1491 W Settings:Agent: Process.myUid(): 1000
11-17 18:30:37.011   892  1491 W Settings:Agent: 
,11-17 18:30:37.011   892  1491 W Settings:Agent: 
11-17 18:30:37.021   892  1491 W System.err: java.lang.Throwable: stack dump
11-17 18:30:37.031   892  1491 W System.err: ,	at java.lang.Thread.dumpStack(Thread.java:490)
11-17 18:30:37.031   892  1491 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
11-17 18:30:37.031   892  1491 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,11-17 18:30:37.031   892  1491 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
11-17 18:30:37.031   892  1491 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
,11-17 18:30:37.031   892  1491 W System.err: ,	,at android.provider.Settings$Global.putInt(Settings.java:7503)
11-17 18:30:37.031   892  1491 W System.err: 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
,11-17 18:30:37.031   892  1491 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
11-17 18:30:37.031   892  1491 W System.err: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
11-17 18:30:37.031   892  1491 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,11-17 18:30:37.031   892  1491 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,11-17 18:30:37.031   892  1491 W Settings:Agent: 
11-17 18:30:37.031   892  1491 W Settings:Agent: << traceCallingStack(): 17(ms),
11-17 18:30:37.041  5612  5612 I jxcore-log: ****TEST TOOK:  5107  ms ****
11-17 18:30:37.041  5612  5612 I jxcore-log: 
11-17 18:30:37.041  5612  5612 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:37.041  5612  5612 I jxcore-log: 
,11-17 18:30:37.051  4128  4187 I CheckinService: Done disabling old GoogleServicesFramework version
,11-17 18:30:37.441  5681  5691 E cutils-trace: Error opening trace file: No such file or directory (2),
,11-17 18:30:37.481  5681  5681 D CustomizationManager: ====startRecUseTime====,
11-17 18:30:37.481  5681  5681 D htc.customization.log.level:  is 
11-17 18:30:37.481  5681  5681 W CustomizationLogLevel: Level value is invalid, use default level 2
,11-17 18:30:37.551  5681  5681 D CustomizationManager:  Read ACC file spent 0.042 (s),
,11-17 18:30:37.551  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__001
,11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__E11
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__102,
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__203
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__405
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__Y13
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__304,
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__A07
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__032
,11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__J15
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__016
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__M27
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__A48
,11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__K18
11-17 18:30:37.561  5681  5681 D CIDMapFileReader: Parsing tag item name = HTC__002
,11-17 18:30:37.561  5681  5681 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = system,
,11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = application
,11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = Settings
,11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = AudioService
,11-17 18:30:37.561  5681  5681 I CustomizationCIDLoader: Parsing tag category name = ACC
,11-17 18:30:37.571  5681  5681 D CustomizationManager:  Read CID file spent 0.087 (s),
11-17 18:30:37.571  5681  5681 D CustomizationManager:  All configurations done spent 0.087 (s)
,11-17 18:30:37.581  5681  5681 E ActTriggerJNI: open library fail.
11-17 18:30:37.601   892  1536 D PackageManager: deletePackageAsUser: pkg=com.example.hello, pid=5681, uid=2000 userid=0,
,11-17 18:30:37.601   892   987 I ActivityManager: Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
11-17 18:30:37.601   892   987 I ActivityManager: Killing 5612:com.example.hello/u0a380 (adj 0): stop com.example.hello
11-17 18:30:37.601   892   987 D Process : killProcessQuiet, pid=5612
11-17 18:30:37.601   892   987 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,11-17 18:30:37.631   892  1262 I ActivityManager: Recipient 5612,
11-17 18:30:37.631   892  1535 I WindowState: WIN DEATH: Window{13bce792 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:30:37.631   892  1078 D WifiService: Client connection lost with reason: 4
,11-17 18:30:37.651   892  1051 W PackageSettings: Skipping PackageSetting{307c91e2 com.test.thalitest/10373} due to missing metadata
,11-17 18:30:37.711   892   987 W ActivityManager: Force removing ActivityRecord{2a78b5e7 u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,11-17 18:30:37.721  2234  2248 E MP-Decision: Update arg "0 380 380 380".
11-17 18:30:37.721  2234  2248 E MP-Decision: Update arg "0 400 400 400".
,11-17 18:30:37.721   892  1262 W ActivityManager: Spurious death for ProcessRecord{c7e6baf 5612:com.example.hello/u0a380}, curProc for 5612: null
11-17 18:30:37.721   892  1051 I ActivityManager: Force stopping com.example.hello appid=10380 user=0: pkg removed
,11-17 18:30:37.731  1196  1196 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,11-17 18:30:37.731   892   987 I ActivityManager: Waited long enough for: ServiceRecord{2a87a0ea u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
11-17 18:30:37.731  1196  1196 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
11-17 18:30:37.731   892   987 I ActivityManager: Waited long enough for: ServiceRecord{dc76342 u0 com.htc.musicenhancer/.EnhancerService},
,11-17 18:30:37.731  1196  1196 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
11-17 18:30:37.741   892   908 D PMS     : acquireWL(33b8745): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1680 10025 WorkSource{10025 com.google.android.gms},
,11-17 18:30:37.751   892  2106 D PMS     : releaseWL(33b8745): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
11-17 18:30:37.761  1492  1492 I FeedHostManager: [onResume]
11-17 18:30:37.761  1492  1492 I FeedProviderManager: onResume
11-17 18:30:37.771   892   993 D StatusBarManagerService: setSystemUiVisibility(0x700)
11-17 18:30:37.761  1492  2169 I SocialFeedProvider: +onResume
11-17 18:30:37.771   892   993 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,11-17 18:30:37.761  1492  2169 I SocialFeedProvider: updateAccounts - Accounts is no change
11-17 18:30:37.771   892   993 D StatusBarManagerService: hiding MENU key
11-17 18:30:37.761  1492  2169 I SocialFeedProvider: -onResume
11-17 18:30:37.831   892  1533 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5612 uid 10380
11-17 18:30:37.761  1492  1492 I ConnectivityHelper: [getCurrentConnectionType] no network connection
11-17 18:30:37.831   892  1533 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
11-17 18:30:37.771  1492  1873 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
11-17 18:30:37.831   892  1533 I InputMethodManagerService: Enable input method client, pid=1492
11-17 18:30:37.771  1492  1873 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
11-17 18:30:37.791  1449  1449 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
11-17 18:30:37.791   892   892 W PackageManager: Unable to load service info ResolveInfo{1c29b269 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
11-17 18:30:37.791   892   892 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
11-17 18:30:37.791   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:30:37.791   892   892 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:37.791   892   892 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
11-17 18:30:37.791   892   892 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
11-17 18:30:37.791   892   892 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:37.791   892   892 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:37.791   892   892 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
11-17 18:30:37.791   892   892 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
11-17 18:30:37.831  5168  5168 I art     : Explicit concurrent mark sweep GC freed 464(30KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 262us total 97.205ms
11-17 18:30:37.841  1550  5714 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
,11-17 18:30:37.841  1589  1931 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
11-17 18:30:37.851  1409  5715 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
,11-17 18:30:37.851  1409  5715 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,11-17 18:30:37.851   892   892 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:30:37.861   892  1101 D TaskPersister: removeObsoleteFile: deleting file=27_task.xml
,11-17 18:30:37.861  1492  1492 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
,11-17 18:30:37.861  1589  1931 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,11-17 18:30:37.871   892   993 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
11-17 18:30:37.871   892   993 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:37.871   892   993 D StatusBarManagerService: hiding MENU key
,11-17 18:30:37.881  1589  1931 E ExternalAccountType: Unsupported attribute readOnly
,11-17 18:30:37.891   892  1533 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,11-17 18:30:37.901   892   986 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,11-17 18:30:37.931   892   986 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:37.961   892  1051 I art     : Explicit concurrent mark sweep GC freed 19323(1386KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.156ms total 112.667ms
,11-17 18:30:37.981   892  1051 W asset   : Copying FileAsset 0xb91774d8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,11-17 18:30:37.981  5718  5718 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,11-17 18:30:38.011  1764  1764 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 18:30:38.011  1764  1764 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-17 18:30:38.011   892  1324 D PMS     : acquireWL(270f5d0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1764 10025 WorkSource{10025 com.google.android.gms}
,11-17 18:30:38.021   892  1436 D PMS     : releaseWL(270f5d0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,11-17 18:30:38.021   892  1142 D Process : killProcessQuiet, pid=5379
,11-17 18:30:38.021   892  1142 I ActivityManager: Killing 5379:com.htc.sdm/u0a82 (adj 15): empty #17
11-17 18:30:38.021   892  1142 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,11-17 18:30:38.031   892   907 I ActivityManager: Recipient 5379
,11-17 18:30:38.051   892   907 D Process : killProcessQuiet, pid=5379
,11-17 18:30:38.051   892   907 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:38.051   892   907 W libprocessgroup: failed to open /acct/uid_10082/pid_5379/cgroup.procs: No such file or directory
,11-17 18:30:38.051  4128  5742 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,11-17 18:30:38.051  4128  4128 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:38.051  4128  4128 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:30:38.051  4128  5742 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:30:38.061  4128  4128 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:38.061  4128  4128 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:38.061  5168  5745 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:30:38.091   892  2106 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5747 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,11-17 18:30:38.101  4128  5742 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:30:38.131  4128  5758 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,11-17 18:30:38.131  4128  5758 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
11-17 18:30:38.131  4128  5758 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:30:38.131  4128  5758 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:30:38.141  4128  5758 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-17 18:30:38.141  4128  5758 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
11-17 18:30:38.141  4128  5758 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:30:38.141  1764  1847 I art     : Explicit concurrent mark sweep GC freed 14419(813KB) AllocSpace objects, 2(32KB) LOS objects, 50% free, 3MB/7MB, paused 732us total 22.671ms
,11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:30:38.151   892  1324 D PMS     : acquireWL(330c2d40): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4128 10025 null
11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:30:38.151  1764  1764 I ConfigService: onCreate
,11-17 18:30:38.151  4128  5758 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
11-17 18:30:38.151   892  1491 D PMS     : releaseWL(330c2d40): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
11-17 18:30:38.151  4128  4128 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,11-17 18:30:38.171  4128  5766 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:38.171  4128  5770 I PeopleContactsSync: CP2 sync disabled
,11-17 18:30:38.171   892  1535 D PMS     : acquireWL(3b3d6e04): PARTIAL_WAKE_LOCK  Icing 0x1 4128 10025 WorkSource{10025 com.google.android.gms}
,11-17 18:30:38.171  4128  4206 I Icing   : doRemovePackageData com.example.hello
11-17 18:30:38.171   892   907 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4128, uid=10025, userID:0
,11-17 18:30:38.171  4128  5766 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:38.191   892  2106 D PMS     : releaseWL(3b3d6e04): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms},
,11-17 18:30:38.211   892  1436 D PMS     : acquireWL(18b27a6e): PARTIAL_WAKE_LOCK  Icing 0x1 4128 10025 WorkSource{10025 com.google.android.gms}
,11-17 18:30:38.221  5168  5745 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,11-17 18:30:38.271  4128  5756 I art     : WaitForGcToComplete blocked for 19.863ms for cause Explicit
,11-17 18:30:38.311  4128  5756 I art     : Explicit concurrent mark sweep GC freed 6184(245KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 521us total 38.059ms
,11-17 18:30:38.321  4128  5756 W DriveInitializer: Awaiting to be initialized
,11-17 18:30:38.321  4128  5776 W DriveInitializer: Background init thread started
,11-17 18:30:38.351  1492  1900 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,11-17 18:30:38.361   364   411 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
,11-17 18:30:38.361   364   411 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:30:38.361  4128  5776 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,11-17 18:30:38.401  4128  5776 W DriveInitializer: Background init thread ended
,11-17 18:30:38.451  5747  5747 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
11-17 18:30:38.451  5747  5747 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:30:38.451  5747  5747 I GAv4    :   adb logcat -s GAv4
,11-17 18:30:38.471  5747  5747 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,11-17 18:30:38.471  1764  5793 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.471  1764  5793 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.471  1764  5793 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:30:38.471  1764  5793 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-17 18:30:38.471  1764  5793 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:30:38.471  1764  5793 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.471  1764  5793 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:30:38.481  5747  5747 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:38.491  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.491  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:38.501  5747  5795 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
11-17 18:30:38.501  5747  5747 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,11-17 18:30:38.501  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:38.501  5747  5795 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.g(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.a(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.e(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdy.b(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at feb.run(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,11-17 18:30:38.501  5747  5795 E GAv4    : Opening the database failed, dropping the table and recreating it
11-17 18:30:38.501  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.g(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.a(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdw.e(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at fdy.b(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at feb.run(Unknown Source)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.501  5747  5795 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,11-17 18:30:38.501  5747  5795 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.511  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.511  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.511  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.511  5747  5795 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.511  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at ael.a(PG:1521)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at hix$a.a(PG:125)
11-17 18:30:38.521  5747  5796 E SQLiteDatabase: 	at aen.run(PG:536)
,11-17 18:30:38.581  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:38.581  5747  5795 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.581   364   411 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
11-17 18:30:38.581   364   411 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.581  5747  5800 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,11-17 18:30:38.581  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.581  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:38.581  5747  5795 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.581   892  1446 D PMS     : acquireWL(27581cc): PARTIAL_WAKE_LOCK  AsyncService 0x1 5237 10176 null
,11-17 18:30:38.581  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.581  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at ael.a(PG:1521)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at hix$a.a(PG:125),
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at aej.c(PG:139)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at aej.b(PG:398)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at agf.f(PG:417)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at oe.run(PG:1112)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.591  5747  5800 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.591  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.591   892  1535 D PMS     : releaseWL(27581cc): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	,at ael.a(PG:1521)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at aej.c(PG:139)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at aej.b(PG:398)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at agf.f(PG:417)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:38.591  5747  5800 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.591   892  1534 D PMS     : acquireWL(13b0b2a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5237 10176 null
11-17 18:30:38.591  5747  5795 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.591  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:38.591  5747  5795 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.591   892  1535 D PMS     : releaseWL(13b0b2a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,11-17 18:30:38.591  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:38.591  5747  5801 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,11-17 18:30:38.591  5747  5801 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
11-17 18:30:38.591  5747  5796 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:38.591  5747  5794 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
11-17 18:30:38.591  5747  5796 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
,11-17 18:30:38.611  2234  2248 E MP-Decision: Update arg 2
,11-17 18:30:38.621   892  1536 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5804 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
11-17 18:30:38.621   892  1324 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,11-17 18:30:38.621  2234  2248 E MP-Decision: Update arg "0 190 240 240".
,11-17 18:30:38.621  2234  2248 E MP-Decision: Update arg "0 75 400 400".
,11-17 18:30:38.631   892   995 I AnimationUtil: isHTCRecent(Drive/Recent screens.)/4
11-17 18:30:38.631   892  1324 D PMS     : acquireWL(1577e491): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 892 1000 null
,11-17 18:30:38.631  1492  1492 I FeedHostManager: [onPause]
11-17 18:30:38.631  1492  1492 I FeedProviderManager: onPause,
,11-17 18:30:38.631  1492  1492 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@190b03ac
11-17 18:30:38.631  5747  5796 D Process : killProcess, pid=5747
11-17 18:30:38.631  1492  2169 I SocialFeedProvider: +onPause
11-17 18:30:38.631  1492  2169 I SocialFeedProvider: -onPause
11-17 18:30:38.631  5747  5796 D Process : vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
11-17 18:30:38.631   361   361 E lowmemorykiller: Error writing /proc/5747/oom_score_adj; errno=22
11-17 18:30:38.631   892  1537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
11-17 18:30:38.631   892   908 E ActivityManager: TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
11-17 18:30:38.631   892   908 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,11-17 18:30:38.631   892   908 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
11-17 18:30:38.631   892   908 W ActivityManager: android.os.TransactionTooLargeException
11-17 18:30:38.631   892   908 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 18:30:38.631   892   908 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:504)
11-17 18:30:38.631   892   908 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2009)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1547)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1060)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:958)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6859)
11-17 18:30:38.631   892   908 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
11-17 18:30:38.631   892   908 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
11-17 18:30:38.631   892   908 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:454)
,11-17 18:30:38.651   892  1436 I ActivityManager: Recipient 5747,
,11-17 18:30:38.711   892   908 I ActivityManager: Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5821 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,11-17 18:30:38.711   892  1436 W ActivityManager: Spurious death for ProcessRecord{3702fe5d 5821:com.google.android.apps.docs/u0a107}, curProc for 5747: null
,11-17 18:30:38.711  1492  1492 I TrimMemoryManager: [trimMemory] 20
,11-17 18:30:38.741   892   993 D StatusBarManagerService: setSystemUiVisibility(0x8600)
,11-17 18:30:38.741   892   993 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:38.741   892   993 D StatusBarManagerService: hiding MENU key
,11-17 18:30:38.771  5804  5804 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=5804 dbg=false s=true,
,11-17 18:30:38.771  5804  5804 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.example.hello],
,11-17 18:30:38.771  5804  5804 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]],
,11-17 18:30:38.781  5804  5804 I DeviceManagement: WorkflowService: Starting workflow service,
,11-17 18:30:38.781  5804  5839 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@35ff59f4] args=[Bundle[mParcelledData.dataSize=108]],
11-17 18:30:38.781  5804  5839 I DeviceManagement: PackageUpdateWorkflow: ==================================================
11-17 18:30:38.781  5804  5839 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
,11-17 18:30:38.781  5804  5839 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,11-17 18:30:38.791  5804  5839 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,11-17 18:30:38.811   892  1262 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5840 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,11-17 18:30:38.821  5804  5839 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.example.hello
,11-17 18:30:38.821  5804  5858 I DeviceManagement: SessionStateController: Checking invariants...
,11-17 18:30:38.871  5840  5840 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854),
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1393)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	,at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5696)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
,11-17 18:30:38.871  5840  5840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:30:38.881  5840  5840 E AndroidRuntime: Process: com.android.documentsui, PID: 5840
11-17 18:30:38.881  5840  5840 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	,at android.app.ActivityThread.main(ActivityThread.java:5696)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: ,	at android.content.ContentResolver.call(ContentResolver.java:1393)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
11-17 18:30:38.881  5840  5840 E AndroidRuntime: 	... 9 more
,11-17 18:30:38.911   892  1446 E ActivityManager: App crashed! Process: com.android.documentsui,
11-17 18:30:38.911   892  2106 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5860 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,11-17 18:30:38.911   892  1446 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
11-17 18:30:38.911   892  1533 D PMS     : releaseWL(dce9793): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,11-17 18:30:38.921   892  1537 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
11-17 18:30:38.921   892  1537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:38.921   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:38.921   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:38.921   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
11-17 18:30:38.921   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
11-17 18:30:38.921   892  1537 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:38.921   892  1537 W System.err: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:38.921   892  1537 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:38.921   892  1537 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:38.921   892  1537 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:38.921   892  1537 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:38.921   892  1537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:38.921   892  1537 W System.err: 	... 12 more
11-17 18:30:38.931   892  1446 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
11-17 18:30:38.931   892  1446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:38.931   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:38.931   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:38.931   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:30:38.931   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:30:38.931   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:30:38.931   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555),
,11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
11-17 18:30:38.941   892  5882 E ErrorReport: HtcErrorReportManager.Error in dumping error information
11-17 18:30:38.941   892  5882 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1447781438959.dbox_tmp: open failed: EROFS (Read-only file system)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:38.941   892  5882 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:38.941   892  5882 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:38.941   892  5882 E ErrorReport: 	... 4 more
11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
11-17 18:30:38.951   892   987 W ActivityManager: Can't addPackageDependency on system process
11-17 18:30:38.931   892  1446 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:30:38.931   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
11-17 18:30:38.931   892  1446 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:38.931   892  1446 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:38.931   892  1446 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:38.931   892  1446 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:38.931   892  1446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:38.931   892  1446 W System.err: 	... 14 more
11-17 18:30:38.941   892  1446 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
11-17 18:30:38.941   892  1446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:38.941   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:38.941   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:38.941   892  1446 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:30:38.941   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:30:38.941   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:30:38.941   892  1446 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.handleA,pplicationCrashInner(ActivityManagerService.java:12219)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
11-17 18:30:38.941   892  1446 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:30:38.941   892  1446 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
11-17 18:30:38.941   892  1446 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:38.941   892  1446 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:38.941   892  1446 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:38.941   892  1446 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:38.941   892  1446 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:38.941   892  1446 W System.err: 	... 14 more
11-17 18:30:38.981   892   993 D StatusBarManagerService: setSystemUiVisibility(0x8000)
11-17 18:30:38.991   892  1491 D Process : killProcessQuiet, pid=5445
11-17 18:30:38.981   892   993 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:30:38.991   892  1491 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
11-17 18:30:38.981   892   993 D StatusBarManagerService: hiding MENU key
11-17 18:30:38.991   892  1491 I ActivityManager: Killing 5445:com.htc.bgp/u0a11 (adj 15): empty #17
11-17 18:30:38.991  5860  5860 D ExternalStorage: After updating volumes, found 1 active roots
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:39.001  5804  5858 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:39.001   892  1324 I ActivityManager: Recipient 5445
11-17 18:30:39.001  1409  1631 D AutoSetting: service - handleMessage() stop self
11-17 18:30:39.011  1409  1631 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.sense.hsp/shared_prefs/preference.xml to backup file /data/user/0/com.htc.sense.hsp/shared_prefs/preference.xml.bak
,11-17 18:30:39.061   892  1324 D Process : killProcessQuiet, pid=5445
,11-17 18:30:39.061   892  1324 W libprocessgroup: failed to open /acct/uid_10011/pid_5445/cgroup.procs: No such file or directory
11-17 18:30:39.061   892  1324 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:39.061  1409  1631 D AutoSetting: service - handleMessage() quit looper
,11-17 18:30:39.071  1409  1409 D AutoSetting: service - onDestroy() END
,11-17 18:30:39.071  5804  5858 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,11-17 18:30:39.071  5804  5839 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.071  5804  5839 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.example.hello
,11-17 18:30:39.071  5804  5839 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
,11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:39.071  5804  5839 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:39.071  5804  5839 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@35ff59f4]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.071  5804 , 5839 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:39.071  5804  5839 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:39.071   892  1535 I ActivityManager: Killing 5128:com.google.android.gms:car/u0a25 (adj 15): empty #17
11-17 18:30:39.071  5804  5804 I DeviceManagement: WorkflowService: Stopping workflow service
11-17 18:30:39.071   892  1535 D Process : killProcessQuiet, pid=5128
11-17 18:30:39.071   892  1535 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,11-17 18:30:39.091  5821  5821 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
11-17 18:30:39.091  5821  5821 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:30:39.091  5821  5821 I GAv4    :   adb logcat -s GAv4
,11-17 18:30:39.101   892  1533 I ActivityManager: Recipient 5128,
,11-17 18:30:39.131   892  1533 D Process : killProcessQuiet, pid=5128
11-17 18:30:39.131   892  1533 W libprocessgroup: failed to open /acct/uid_10025/pid_5128/cgroup.procs: No such file or directory
11-17 18:30:39.131   892  1533 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:39.131  5821  5821 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:39.151  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.151  5821  5821 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:39.151  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.151  5821  5892 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:39.161  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.g(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.a(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.e(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdy.b(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at feb.run(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
11-17 18:30:39.161  5821  5892 E GAv4    : Opening the database failed, dropping the table and recreating it
11-17 18:30:39.161  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.161  5821  5892 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.g(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.a(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdw.e(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at fdy.b(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at feb.run(Unknown Source)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:39.161  5821  5892 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
11-17 18:30:39.161  5821  5892 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,11-17 18:30:39.161  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.161  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.161  5821  5892 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.161  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.161  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.171  5821  5821 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,11-17 18:30:39.181  5821  5893 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254),
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at ael.a(PG:1521)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at hix$a.a(PG:125)
11-17 18:30:39.181  5821  5893 E SQLiteDatabase: 	at aen.run(PG:536)
,11-17 18:30:39.251   364   411 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
11-17 18:30:39.251   364   411 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:30:39.251  5821  5898 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at ael.a(PG:1521)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at hix$a.a(PG:125)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at aej.c(PG:139)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at aej.b(PG:398)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at agf.f(PG:417)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at oe.run(PG:1112)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:39.251  5821  5898 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at aej.c(PG:139)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at aej.b(PG:398)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at agf.f(PG:417)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:30:39.251  5821  5898 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:30:39.261  4128  4206 I Icing   : Indexing 133D3F44B423C1F90B90CE261AE1222BFA42C728 from com.google.android.googlequicksearchbox
,11-17 18:30:39.271  1492  1873 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,11-17 18:30:39.271  1492  1873 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3e752c82 +
,11-17 18:30:39.271  1492  1873 I Prism.WidgetManager: onLoadItems() +,
,11-17 18:30:39.291  5821  5899 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:30:39.291  5821  5899 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
11-17 18:30:39.291  4128  4206 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
11-17 18:30:39.291  4128  4206 E Icing   : Could not init tag ds.tag.deleted
11-17 18:30:39.291   892  1436 I art     : Explicit concurrent mark sweep GC freed 22390(1191KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.479ms total 80.697ms
11-17 18:30:39.301  5821  5821 E ErrorNotificationActivity: Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
11-17 18:30:39.301  1492  1873 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:39.311  5821  5835 I art     : Background sticky concurrent mark sweep GC freed 5064(460KB) AllocSpace objects, 4(64KB) LOS objects, 13% free, 3MB/4MB, paused 6.807ms total 23.763ms,
,11-17 18:30:39.311  4714  5878 W MediaManager: [DualLensScanUtil],	mmpCursor count is 0
,11-17 18:30:39.321   892  1533 I ActivityManager: Killing 4753:com.google.android.music:main/u0a167 (adj 15): empty #17,
11-17 18:30:39.321   892  1533 D Process : killProcessQuiet, pid=4753
11-17 18:30:39.321   892  1533 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,11-17 18:30:39.341   892   908 I ActivityManager: Recipient 4753
11-17 18:30:39.341   892  1536 D MediaRouterService: Client com.google.android.music (pid 4753): Died!
,11-17 18:30:39.341  5821  5821 D Atlas   : Validating map...
,11-17 18:30:39.361  5821  5899 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:30:39.401   892   908 D Process : killProcessQuiet, pid=4753,
11-17 18:30:39.401   892   908 W libprocessgroup: failed to open /acct/uid_10167/pid_4753/cgroup.procs: No such file or directory
11-17 18:30:39.401   892   908 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:39.411  5821  5899 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
11-17 18:30:39.411  5821  5899 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:30:39.421  4128  4206 I Icing   : Indexing done 133D3F44B423C1F90B90CE261AE1222BFA42C728
,11-17 18:30:39.421  4128  4206 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,11-17 18:30:39.421  4128  4206 E Icing   : Writing status failed
11-17 18:30:39.421  4128  4206 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,11-17 18:30:39.421   892  1535 D PMS     : releaseWL(18b27a6e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,11-17 18:30:39.441  5821  5837 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238),
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at ael.a(PG:1521)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at hix$a.a(PG:125)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at aej.c(PG:139)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at aej.a(PG:358)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at aej.a(PG:345)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at agf.d(PG:281)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at agf.b(PG:312)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: ,	at agf.a(PG:221)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
11-17 18:30:39.441  5821  5837 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
,11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: Failed to query Account133 object
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	,at aej.c(PG:139)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at aej.a(PG:358)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at aej.a(PG:345)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at agf.d(PG:281)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	,at agf.b(PG:312)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at agf.a(PG:221)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.content.ContentProvider.query(ContentProvider.java:960)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
11-17 18:30:39.441  5821  5837 E AbstractDatabaseInstance: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: Writing exception to parcel
11-17 18:30:39.451  5821  5837 E DatabaseUtils: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at aev.getWritableDatabase(PG:238)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at ael.a(PG:1521)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at hix$a.a(PG:125)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at aej.c(PG:139)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	,at aej.a(PG:358)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at aej.a(PG:345)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at agf.d(PG:281)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at agf.b(PG:312)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at agf.a(PG:221)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.content.ContentProvider.query(ContentProvider.java:960)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
11-17 18:30:39.451  5821  5837 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:39.451  5840  5859 W Documents: Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.451  5840  5859 D Documents: Update found 6 roots in 586ms
11-17 18:30:39.451  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:39.451  5821  5892 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:39.451  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.451  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.451  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:39.451  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.451  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.461  5821  5892 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.461  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.461  5821  5892 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.461  5821  5892 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,11-17 18:30:39.461  5821  5893 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
11-17 18:30:39.461  5821  5891 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	,at aev.getWritableDatabase(PG:238),
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
11-17 18:30:39.461  5821  5893 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
,11-17 18:30:39.471  1492  1873 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,11-17 18:30:39.471   892  1436 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,11-17 18:30:39.491  5821  5901 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
11-17 18:30:39.491  5821  5901 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:30:39.491  5821  5901 I Adreno-EGL: Build Date: 12/11/14 Thu
,11-17 18:30:39.491  5821  5901 I Adreno-EGL: Local Branch: 
11-17 18:30:39.491  5821  5901 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
11-17 18:30:39.491  5821  5901 I Adreno-EGL: Local Patches: NONE
11-17 18:30:39.491  5821  5901 I Adreno-EGL: Reconstruct Branch: NOTHING
,11-17 18:30:39.501  5821  5893 D Process : killProcess, pid=5821
11-17 18:30:39.501  5821  5893 D Process : vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
,11-17 18:30:39.511   892  1536 I WindowState: WIN DEATH: Window{316d0a51 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
11-17 18:30:39.511   892  1262 I ActivityManager: Recipient 5821
,11-17 18:30:39.511   892  1068 W InputDispatcher: channel '1b0c0bb7 com.google.android.apps.docs.app.ErrorNotificationActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-17 18:30:39.511   892  1068 E InputDispatcher: channel '1b0c0bb7 com.google.android.apps.docs.app.ErrorNotificationActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,11-17 18:30:39.521   892  1262 D Process : killProcessQuiet, pid=5821
,11-17 18:30:39.521   892  1262 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
11-17 18:30:39.521   892  1537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,11-17 18:30:39.521   892  1535 W InputDispatcher: Attempted to unregister already unregistered input channel '1b0c0bb7 com.google.android.apps.docs.app.ErrorNotificationActivity (s)'
11-17 18:30:39.521   892  1535 I WindowState: WIN DEATH: Window{1b0c0bb7 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,11-17 18:30:39.521   892  1068 I WindowManager: WINDOW DIED Window{1b0c0bb7 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,11-17 18:30:39.541   892  1262 I ActivityManager: Process com.google.android.apps.docs (pid 5821) has died
11-17 18:30:39.541   892  1262 W ActivityManager: Force removing ActivityRecord{1006bd1b u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state
,11-17 18:30:39.541  2234  2248 E MP-Decision: Update arg "0 380 380 380".
11-17 18:30:39.541  2234  2248 E MP-Decision: Update arg "0 400 400 400".
11-17 18:30:39.541   892  1262 I ActivityManager: Killing 5507:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
11-17 18:30:39.541   892  1262 D Process : killProcessQuiet, pid=5507
11-17 18:30:39.541   892  1262 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:1868 
,11-17 18:30:39.551  1492  1873 E Prism.WidgetManager: The same lists. No need to update. skip it.
,11-17 18:30:39.551  1492  1873 I Prism.WidgetManager: onLoadItems() -
11-17 18:30:39.551  1492  1873 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3e752c82 -
,11-17 18:30:39.561   892  1533 I ActivityManager: Recipient 5507
,11-17 18:30:39.561  1492  1873 E SQLiteLog: (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error
,11-17 18:30:39.561   892  1078 D WifiService: Client connection lost with reason: 4
11-17 18:30:39.561  1492  1873 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb8dcaad8
11-17 18:30:39.561  1492  1873 E AndroidRuntime: FATAL EXCEPTION: TaskWorker
11-17 18:30:39.561  1492  1873 E AndroidRuntime: Process: com.htc.launcher, PID: 1492
11-17 18:30:39.561  1492  1873 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	,at android.content.ContentResolver.delete(ContentResolver.java:1320)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:39.561  1492  1873 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:30:39.561   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.561   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.561   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.561   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.561   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.571   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=6
11-17 18:30:39.571   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted,
11-17 18:30:39.571   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.571   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.581   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,11-17 18:30:39.581   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.581   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.581   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.581   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.581   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
11-17 18:30:39.581   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.581   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.581   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.591   892  1533 D Process : killProcessQuiet, pid=5507
11-17 18:30:39.591   892  1533 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,11-17 18:30:39.591   892  1533 W libprocessgroup: failed to open /acct/uid_10005/pid_5507/cgroup.procs: No such file or directory
,11-17 18:30:39.591   892  2106 E ActivityManager: App crashed! Process: com.htc.launcher
11-17 18:30:39.591   892  2106 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
11-17 18:30:39.591   892  1537 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
11-17 18:30:39.591   892  1537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:39.591   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:39.591   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:39.591   892  1537 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
11-17 18:30:39.591   892  1537 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
,11-17 18:30:39.591   892  1537 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:39.591   892  1537 W System.err: 	at android.os.Looper.loop(Looper.java:155)
11-17 18:30:39.591   892  1537 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:30:39.591   892  1537 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:39.591  1492  1492 I FeedHostManager: [onResume]
11-17 18:30:39.591  1492  1492 I FeedProviderManager: onResume
11-17 18:30:39.591   892  1537 W System.err: 	at libcore.io.Posix.open(Native Method)
,11-17 18:30:39.591  1492  2169 I SocialFeedProvider: +onResume
11-17 18:30:39.591  1492  2169 I SocialFeedProvider: updateAccounts - Accounts is no change
11-17 18:30:39.591  1492  2169 I SocialFeedProvider: -onResume
11-17 18:30:39.591   892  1537 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:39.591   892  1537 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:39.591   892  1537 W System.err: 	... 12 more
11-17 18:30:39.591  1492  1492 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,11-17 18:30:39.601   892  2106 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
11-17 18:30:39.601   892  2106 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
11-17 18:30:39.601   892  2106 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
11-17 18:30:39.601   892  2106 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
11-17 18:30:39.601   892  2106 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:39.601   892  2106 W System.err: 	... 14 more
11-17 18:30:39.601   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.601   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.601   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.601   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.601   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.601   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
,11-17 18:30:39.601   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.601   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.601   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.601   892  2106 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
11-17 18:30:39.601   892  2106 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
11-17 18:30:39.601   892  2106 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
,11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
11-17 18:30:39.601   892  2106 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
11-17 18:30:39.601   892  2106 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
11-17 18:30:39.601   892  2106 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,11-17 18:30:39.601   892  2106 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:39.601   892  2106 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:39.601   892  2106 W System.err: 	... 14 more
,11-17 18:30:39.611   892  2106 W ActivityManager:   Force finishing activity com.htc.launcher/.Launcher
,11-17 18:30:39.611   892  2106 D PMS     : acquireWL(1577e491): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 892 1000 null
11-17 18:30:39.611   892  5903 E ErrorReport: HtcErrorReportManager.Error in dumping error information
11-17 18:30:39.611   892  5903 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1447781439622.dbox_tmp: open failed: EROFS (Read-only file system)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:30:39.611   892  5903 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:30:39.611   892  5903 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:30:39.611   892  5903 E ErrorReport: 	... 4 more
,11-17 18:30:39.611   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.611   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.611   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.611   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.611   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.611   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
11-17 18:30:39.611   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.611   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.611   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.621  1492  1492 I FeedHostManager: [onPause]
11-17 18:30:39.621  1492  1492 I FeedProviderManager: onPause
,11-17 18:30:39.621  1492  2169 I SocialFeedProvider: +onPause
11-17 18:30:39.621  1492  2169 I SocialFeedProvider: -onPause
11-17 18:30:39.621  1492  1492 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@190b03ac,
11-17 18:30:39.631   892  1537 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,11-17 18:30:39.631   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
11-17 18:30:39.631   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.631   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.631   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.631   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.631   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
11-17 18:30:39.631   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,11-17 18:30:39.631   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.631   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:30:39.631   892  1436 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,11-17 18:30:39.651   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
11-17 18:30:39.651   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.651   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.651   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.651   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.651   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
11-17 18:30:39.651   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.651   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.651   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.661  1492  1492 I OrientationManager: [init] currentOrienation: 1
,11-17 18:30:39.661   892  1491 W AppWidgetServiceImpl: startListening(),set useForground = true,
11-17 18:30:39.661   892  1491 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
11-17 18:30:39.661   892  1491 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
11-17 18:30:39.661   892  1491 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
,11-17 18:30:39.661   892  1491 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
11-17 18:30:39.661   892  1491 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
11-17 18:30:39.661   892  1491 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
11-17 18:30:39.661   892  1491 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
11-17 18:30:39.661   892  1491 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
11-17 18:30:39.661   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.661   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.661   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.661   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.661   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.661   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
11-17 18:30:39.661   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.661   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.661   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:30:39.671  1492  1492 W ResourceType: Invalid package identifier when getting bag for resource number 0x00000014
,11-17 18:30:39.671  1492  1492 I FeedScrollGridView: velocity 0.850000
,11-17 18:30:39.681   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
11-17 18:30:39.681   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.681   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.681   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.681   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.681   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
11-17 18:30:39.681   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.681   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.681   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.691  1492  1492 I Prism.IndicatorPagedVi_: IndicatorPagedView.nCapability with type count = 1 and capability = 20,
,11-17 18:30:39.701   892   987 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=5904 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
11-17 18:30:39.701   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.701   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.701   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.701   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.701   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.701   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=8
11-17 18:30:39.701   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.701   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.701   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.711   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
11-17 18:30:39.711   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.711   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.711   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.721   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.721   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
11-17 18:30:39.721   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.721   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:30:39.721   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.731   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.731   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.731   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.731   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.731   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.731   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
11-17 18:30:39.731   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.731   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.731   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.751   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,11-17 18:30:39.751   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.751   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.751   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.751   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:39.751   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
11-17 18:30:39.751   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.751   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.751   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.761   366   366 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:39.761   366   366 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:39.761   366   366 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:39.761   366   366 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:39.761   366   366 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:30:39.761   366   366 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
11-17 18:30:39.761   366   366 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:30:39.761   366   366 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:30:39.761   366   366 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:30:39.781   366   366 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,11-17 18:30:39.781   366   366 E qdoverlay: MdpCtrl close error in unset
```
