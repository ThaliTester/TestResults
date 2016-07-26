#### Test 757892686f45c73_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main
07-26 15:20:44.888  4322  4322 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-26 15:20:44.888  4322  4322 I ConfigFetchService: launchTask
07-26 15:20:44.888  4322  6594 I PeopleContactsSync: CP2 sync disabled
--------- beginning of system
07-26 15:20:44.888   910  1307 D PMS     : acquireWL(3f44011): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4322 10025 WorkSource{10192 com.test.thalitest}
07-26 15:20:44.888   910  1599 D PMS     : releaseWL(6623f95): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
07-26 15:20:44.898  4322  4322 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:44.898  4322  4322 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-26 15:20:44.898  4322  4322 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
07-26 15:20:44.898   910  1402 D PMS     : acquireWL(38aaa576): PARTIAL_WAKE_LOCK  Icing 0x1 4322 10025 WorkSource{10025 com.google.android.gms}
07-26 15:20:44.898   910  1269 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4322, uid=10025, userID:0
07-26 15:20:44.898   910  1625 D PMS     : releaseWL(38aaa576): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-26 15:20:44.918  4322  6593 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UqDm1HuOrntfa1nZGn-CwvHTYy3fS3G4-Z8J41LSc1ddbsdA48bLDCyoyA0i_76Yqb7qpRSM_y4NImww3LLWjKkIzTU2Nmqk3IRqPvhzbs2wVs_XQpZdaYnwb-Vdat87MmkBN1PhCOissF-0cv4HCJ1STdRIiN_MySWUTd5CqhdscACuCYc87DjcmiPfPfPu1GN0G0
07-26 15:20:44.918  4322  6593 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-26 15:20:44.918  4322  4322 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
07-26 15:20:44.918  4322  4322 D Vision  : Failed to find package metadata for com.test.thalitest
07-26 15:20:44.918  4322  4322 D Vision  : No vision deps
07-26 15:20:44.928  4322  6593 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-26 15:20:44.928  4322  6593 D libc    : [NET] android_getaddrinfofornet-, err=8
07-26 15:20:44.928  4322  6593 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-26 15:20:44.928  4322  6593 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-26 15:20:44.938  4322  6593 D libc    : [NET] android_getaddrinfo_proxy+
07-26 15:20:44.938  4322  6593 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-26 15:20:44.938   460  6597 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-26 15:20:44.938   460  6597 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-26 15:20:44.938   460  6597 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-26 15:20:44.938   460  6597 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-26 15:20:44.938  4322  6593 D libc    : [NET] android_getaddrinfo_proxy-, success
07-26 15:20:44.958   910  1600 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6598 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
07-26 15:20:44.958  6432  6596 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-26 15:20:45.018  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.018  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.058  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.058  4322  6593 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-26 15:20:45.058  4322  6593 D libc    : [NET] android_getaddrinfofornet-, err=8
07-26 15:20:45.058  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.068  4322  6593 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-26 15:20:45.068  4322  6593 D libc    : [NET] android_getaddrinfofornet-, err=8
07-26 15:20:45.088  1830  1853 I art     : Explicit concurrent mark sweep GC freed 11961(642KB) AllocSpace objects, 5(405KB) LOS objects, 48% free, 4MB/8MB, paused 531us total 21.047ms
07-26 15:20:45.098  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.108  4322  4322 I ConfigFetchService: fetch service done; releasing wakelock
07-26 15:20:45.108   910  1623 D PMS     : releaseWL(3f44011): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10192 com.test.thalitest}
07-26 15:20:45.108  4322  4322 I ConfigFetchService: stopping self
07-26 15:20:45.108  4322  6595 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:20:45.108   910  1284 D PMS     : acquireWL(1fd6577c): PARTIAL_WAKE_LOCK  Icing 0x1 4322 10025 WorkSource{10025 com.google.android.gms}
07-26 15:20:45.118   910   938 D PMS     : releaseWL(1fd6577c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-26 15:20:45.118   910   910 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3
07-26 15:20:45.118   910  1598 D PMS     : acquireWL(27de905a): PARTIAL_WAKE_LOCK  Icing 0x1 4322 10025 WorkSource{10025 com.google.android.gms}
07-26 15:20:45.138   910  1307 D PMS     : releaseWL(27de905a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-26 15:20:45.148  1437  1892 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-26 15:20:45.148  1437  1892 D PhoneApp: -- N1 =0
07-26 15:20:45.148  1437  1892 D PhoneApp: -- N2 =0
07-26 15:20:45.148  1437  1892 D PhoneApp: -- N3 =0
07-26 15:20:45.178   910  1402 D PMS     : acquireWL(28001a14): PARTIAL_WAKE_LOCK  Icing 0x1 4322 10025 WorkSource{10025 com.google.android.gms}
07-26 15:20:45.178  6432  6596 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 223 ms] updated apps [took 223 ms] 
07-26 15:20:45.338   910  1600 I art     : Explicit concurrent mark sweep GC freed 28360(1550KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.528ms total 74ms
07-26 15:20:45.468  4322  6595 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:45.468  4322  6595 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-26 15:20:45.508  6408  6408 D Messaging: supportCMAS(SIE)/init? false/true
07-26 15:20:45.508  6408  6408 D MmsConfig: networkCode: 
07-26 15:20:45.508  6408  6408 D MessageCustFlag: sku_id=99
07-26 15:20:45.508  6408  6408 D MmsConfig: SIE smsPri: null
07-26 15:20:45.508  6408  6408 D MmsConfig: networkCode: 
07-26 15:20:45.508  6408  6625 D Messaging: mNeedToUpdateDate2 start
07-26 15:20:45.508  6408  6408 D MmsConfig: packageName: com.htc.vvm.att does not exist
07-26 15:20:45.508  6408  6408 D ReportIndicatorCache: startAsyncQueryReports ---
07-26 15:20:45.508  6408  6425 D MmsAsyncWorkHandler: 
07-26 15:20:45.508  6408  6425 D MmsAsyncWorkHandler: HM tk = 20001
07-26 15:20:45.508  6408  6425 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
07-26 15:20:45.518  6598  6598 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-26 15:20:45.518  6598  6598 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-26 15:20:45.518  6598  6598 I GAv4    :   adb logcat -s GAv4
07-26 15:20:45.518  6408  6408 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@29860cf2
07-26 15:20:45.518  6408  6408 D DraftCache: [DraftCache/1] DraftCache.constructor
07-26 15:20:45.518  6408  6408 D DraftCache: [DraftCache/1] refresh
07-26 15:20:45.518  6408  6408 D MmsConfig: networkCode: 
07-26 15:20:45.528  6408  6631 D Messaging: ViewCache CreatePreloadOnlyConversationList
07-26 15:20:45.528  6598  6598 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-26 15:20:45.538  6408  6408 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
07-26 15:20:45.538  6408  6408 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
07-26 15:20:45.538  6408  6408 D PhoneStorageUtil: createReceiver
07-26 15:20:45.538  6408  6629 I Messaging: mccmnc> 
07-26 15:20:45.538  6408  6631 D MessageCustFlag: sense_version=6.0
07-26 15:20:45.548  6598  6598 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-26 15:20:45.548  6408  6631 D Jerry   : start to preload cursor >>>>>>>
07-26 15:20:45.548  1437  2138 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 107
07-26 15:20:45.548  1437  2138 V MmsProvider: Update uri=content://mms, match=0
07-26 15:20:45.548  1437  2138 V MmsProvider: selection=st=129 AND m_type!=134
07-26 15:20:45.548  6408  6632 D Messaging: Reset downloading state: 0
07-26 15:20:45.548  6408  6632 V MmsSystemEventReceiver: TransactionService is going to be woken up.
07-26 15:20:45.548  6598  6635 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-26 15:20:45.558  6408  6408 W art     : No such thread id for suspend: 18
07-26 15:20:45.558  6408  6408 V TransactionService: 1-Creating TransactionService
07-26 15:20:45.558  1437  2194 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 109
07-26 15:20:45.558  1437  2194 D AccFlag : sku_id=99
07-26 15:20:45.558  6408  6425 D DraftCache: [DraftCache/871] rebuildCache
07-26 15:20:45.558  1437  2145 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 108
07-26 15:20:45.558  1437  2145 D MmsSmsV2Provider:  slotId = -1000
07-26 15:20:45.558  1437  2145 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
07-26 15:20:45.558  1437  2138 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 107
07-26 15:20:45.558  1437  2138 D MmsSmsV2Provider:  slotId = -1000
07-26 15:20:45.558  1437  2138 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
07-26 15:20:45.558  1437  2194 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 109
07-26 15:20:45.558  1437  2194 D MmsSmsV2Provider:  slotId = -1000
07-26 15:20:45.568  6408  6408 V TransactionService: onStartCommand: 1
07-26 15:20:45.568  6408  6408 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-26 15:20:45.568  1437  2138 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 107
07-26 15:20:45.568  1437  2138 D Jerry   : URI_DRAFT
07-26 15:20:45.568  6408  6636 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-26 15:20:45.568  6408  6636 V TransactionService: Loading previous transactions.
07-26 15:20:45.568  6408  6425 D DraftCache: hasDraft() = false mNeedNotifyChange = true
07-26 15:20:45.568  6598  6598 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
07-26 15:20:45.568  6408  6425 D DraftCache: [DraftCache/871] rebuildCache time: 0
07-26 15:20:45.568  1437  2145 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 108
07-26 15:20:45.568  1437  2145 D MmsSmsV2Provider:  slotId = -1000
07-26 15:20:45.568  1437  2145 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
07-26 15:20:45.568  6408  6425 D MmsAsyncWorkHandler: 
07-26 15:20:45.568  6408  6425 D MmsAsyncWorkHandler: HM tk = 20002
07-26 15:20:45.568  6408  6631 D Messaging: ViewCache CreatePreload
07-26 15:20:45.568  6408  6631 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
07-26 15:20:45.568  6408  6627 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
07-26 15:20:45.578  1437  1462 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
07-26 15:20:45.578  1437  1462 D MmsSmsV2Provider:  slotId = -1000
07-26 15:20:45.578  1437  1462 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-26 15:20:45.578  6408  6625 D Messaging: mNeedToUpdateDate2: false
07-26 15:20:45.578  1437  1463 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
07-26 15:20:45.578  1437  1463 D AccFlag : sku_id=99
07-26 15:20:45.578  1437  2194 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 109
07-26 15:20:45.578  1437  2194 D AccFlag : sku_id=99
07-26 15:20:45.588  6408  6631 D Cust_MMSMS: _has_set_default_values_2=true
07-26 15:20:45.588  6408  6631 D MsgPreferenceUtils: def_index: 0
07-26 15:20:45.588  6408  6631 D MsgPreferenceUtils: globalIndex = 1
07-26 15:20:45.588  1437  2138 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 107
07-26 15:20:45.588  6408  6631 D MsgPreferenceUtils: phone state: true
07-26 15:20:45.588  1437  2138 D AccFlag : device_type: 1
07-26 15:20:45.588  6408  6631 D MsgPreferenceUtils: sd state: false
07-26 15:20:45.588  6408  6631 D MsgPreferenceUtils: vIndex = 0
07-26 15:20:45.588  6408  6636 D TransactionService: Force set service start id to 1
07-26 15:20:45.588  6408  6636 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
07-26 15:20:45.588  6408  6636 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-26 15:20:45.588  6408  6408 V TransactionService: Destroying TransactionService
07-26 15:20:45.588  6408  6636 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
07-26 15:20:45.598  6408  6636 V TransactionService: 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-26 15:20:45.668   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
07-26 15:20:45.668   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
07-26 15:20:45.668  6598  6662 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
07-26 15:20:45.678   910  1627 D PMS     : acquireWL(dfb03e3): PARTIAL_WAKE_LOCK  AsyncService 0x1 6519 10176 null
07-26 15:20:45.678   910   940 D PMS     : releaseWL(dfb03e3): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-26 15:20:45.678   910  1377 D PMS     : acquireWL(bcd3c99): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6519 10176 null
07-26 15:20:45.688  6598  6663 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-26 15:20:45.688   910  1402 D PMS     : releaseWL(bcd3c99): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
07-26 15:20:45.688  6598  6663 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-26 15:20:45.728  6598  6612 W art     : Suspending all threads took: 8.758ms
07-26 15:20:45.728   910  1627 I ActivityManager: Killing 5695:com.google.android.setupwizard/u0a80 (adj 15): empty #17
07-26 15:20:45.728   910  1627 D Process : killProcessQuiet, pid=5695
07-26 15:20:45.728   910  1627 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-26 15:20:45.738   910  1600 I ActivityManager: Recipient 5695
07-26 15:20:45.738  6598  6663 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
07-26 15:20:45.778  6598  6663 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-26 15:20:45.778  6598  6663 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-26 15:20:45.788   910  1600 D Process : killProcessQuiet, pid=5695
07-26 15:20:45.788   910  1600 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:45.788   910  1600 W libprocessgroup: failed to open /acct/uid_10080/pid_5695/cgroup.procs: No such file or directory
07-26 15:20:45.788  1830  1830 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:20:46.218  1501  1938 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-26 15:20:46.348  1501  1938 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-26 15:20:46.218  1501  1938 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@34ef3feb +
07-26 15:20:46.218  1501  1938 I Prism.WidgetManager: onLoadItems() +
07-26 15:20:46.428  4322  4404 I Icing   : Indexing 133D3F44B423C1F90B90CE261AE1222BFA42C728 from com.google.android.googlequicksearchbox
07-26 15:20:46.478  4322  4404 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-26 15:20:46.488  1501  1938 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-26 15:20:46.488  1501  1938 I Prism.WidgetManager: onLoadItems() -
07-26 15:20:46.488  1501  1938 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@34ef3feb -
07-26 15:20:46.518  4322  4404 I Icing   : Indexing done 133D3F44B423C1F90B90CE261AE1222BFA42C728
07-26 15:20:46.528   910  1307 D PMS     : releaseWL(28001a14): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-26 15:20:46.598  6687  6705 E cutils-trace: Error opening trace file: No such file or directory (2)
07-26 15:20:46.708  6687  6687 D CustomizationManager: ====startRecUseTime====
07-26 15:20:46.708  6687  6687 D htc.customization.log.level:  is 
07-26 15:20:46.708  6687  6687 W CustomizationLogLevel: Level value is invalid, use default level 2
07-26 15:20:46.818  6687  6687 D CustomizationManager:  Read ACC file spent 0.061 (s)
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__001
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__102
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__203
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__405
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__304
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__032
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__016
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-26 15:20:46.818  6687  6687 D CIDMapFileReader: Parsing tag item name = HTC__002
07-26 15:20:46.818  6687  6687 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = system
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = application
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = Settings
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-26 15:20:46.818  6687  6687 I CustomizationCIDLoader: Parsing tag category name = ACC
07-26 15:20:46.828  6687  6687 D CustomizationManager:  Read CID file spent 0.113 (s)
07-26 15:20:46.828  6687  6687 D CustomizationManager:  All configurations done spent 0.113 (s)
07-26 15:20:46.848  6687  6687 E ActTriggerJNI: open library fail.
07-26 15:20:46.858   910  1599 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:46.858  2279  2299 E MP-Decision: Update arg 2
07-26 15:20:46.858   910  1035 D PMS     : acquireHCC(2ad30c5b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 910 1000 null
07-26 15:20:46.858  2279  2299 E MP-Decision: Update arg 4
07-26 15:20:46.858   910  1035 D PMS     : acquireHCC(33022cf8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 910 1000 null
07-26 15:20:46.868  2279  2299 E MP-Decision: Update arg "0 190 240 240".
07-26 15:20:46.868  2279  2299 E MP-Decision: Update arg "0 75 400 400".
07-26 15:20:46.898   910  1599 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6716 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:46.908   910   910 V ActivityManager: Display changed displayId=0
07-26 15:20:46.908  1202  1202 D DotMatrix: [EventService]  onDisplayChanged: 0
07-26 15:20:46.908  1202  1202 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
07-26 15:20:46.948  1501  1501 I TrimMemoryManager: [trimMemory] 20
07-26 15:20:46.988  6716  6716 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-26 15:20:46.998  6716  6716 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9048-9049)
07-26 15:20:47.008  6716  6716 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:47.018  6716  6716 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b316f43}
07-26 15:20:47.018  6716  6716 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:47.018  6716  6716 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:47.028  6716  6716 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-26 15:20:47.028  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:47.028  6716  6716 E SysUtils: ApplicationContext is null in ApplicationStatus
07-26 15:20:47.038  6716  6716 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-26 15:20:47.048  6716  6716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:47.048  6716  6716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:47.048  6716  6716 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
07-26 15:20:47.048  6716  6716 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:20:47.048  6716  6716 I Adreno-EGL: Build Date: 12/11/14 Thu
07-26 15:20:47.048  6716  6716 I Adreno-EGL: Local Branch: 
07-26 15:20:47.048  6716  6716 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
07-26 15:20:47.048  6716  6716 I Adreno-EGL: Local Patches: NONE
07-26 15:20:47.048  6716  6716 I Adreno-EGL: Reconstruct Branch: NOTHING
07-26 15:20:47.098   910  1627 W System.err: java.lang.Throwable: stack dump
07-26 15:20:47.098   910  1010 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-26 15:20:47.098   910  1010 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aede03c:true
07-26 15:20:47.098   910  1627 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-26 15:20:47.098   910  1627 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
07-26 15:20:47.098   910  1627 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-26 15:20:47.098   910  1627 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-26 15:20:47.108  6716  6747 D BluetoothAdapter: 949492149: getState(). Returning 12
,07-26 15:20:47.168  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:47.178  6716  6716 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:47.188  6716  6716 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-26 15:20:47.188  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:47.188  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:47.238  6716  6716 D Atlas   : Validating map...
,07-26 15:20:47.238   910  1549 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-26 15:20:47.238  6716  6745 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-26 15:20:47.258   910  1009 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
,07-26 15:20:47.258   910  1009 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:47.258   910  1009 D StatusBarManagerService: hiding MENU key
,07-26 15:20:47.258   910  1009 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-26 15:20:47.258   910  1009 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:47.258   910  1009 D StatusBarManagerService: hiding MENU key
,07-26 15:20:47.278  6716  6716 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@ec19008, mServedView=org.apache.cordova.engine.SystemWebView{307cf3a1 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@6f4f9c6
,07-26 15:20:47.278   910  1402 I InputMethodManagerService: Disable input method client, pid=1501,
07-26 15:20:47.278   910  1402 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-26 15:20:47.358  6716  6716 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-26 15:20:47.378   910  1011 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +461ms (total +517ms)
,07-26 15:20:47.418  6716  6716 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6716
,07-26 15:20:47.488  6716  6716 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,07-26 15:20:47.568  6716  6763 D jxcore_app_log: JniHelper::setJavaVM(0xb8908b98), pthread_self() = -1178864760,
,07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-26 15:20:47.578  6716  6763 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30589695 added. We now have 1 listener(s)
,07-26 15:20:47.578   910  1598 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:20:47.578  6716  6763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
,07-26 15:20:47.578  6716  6763 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
,07-26 15:20:47.578  6716  6763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:20:47.578  6716  6763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
,07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:20:47.588  6716  6763 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2afd0b38 added. We now have 1 listener(s)
07-26 15:20:47.588  6716  6763 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:47.588   910  1082 D WifiService: New client listening to asynchronous messages
07-26 15:20:47.588   910   910 E WifiTrafficPoller: ADD_CLIENT: 8
,07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
07-26 15:20:47.588   910  1402 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:20:47.588  6716  6763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
,07-26 15:20:47.598  6716  6763 D BluetoothAdapter: 949492149: getState(). Returning 12,
07-26 15:20:47.598  6716  6763 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:47.598  6716  6763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:47.598  6716  6763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:47.598  6716  6763 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:20:47.598  6716  6763 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:47.598  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:47.598  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:47.618  6716  6716 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,07-26 15:20:48.158  6716  6770 W jxcore-log: Initializing JXcore engine,
07-26 15:20:48.158  6716  6770 W jxcore-log: JXcore engine is ready
,07-26 15:20:48.218  6716  6770 W jxcore-log: Starting JXcore engine,
,07-26 15:20:48.308  6716  6770 W jxcore-log: Platform android,
07-26 15:20:48.308  6716  6770 W jxcore-log: 
07-26 15:20:48.308  6716  6770 W jxcore-log: Process ARCH arm
07-26 15:20:48.308  6716  6770 W jxcore-log: 
,07-26 15:20:48.358   910  1598 D Process : killProcessQuiet, pid=6283,
07-26 15:20:48.358   910  1598 I ActivityManager: Killing 6283:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
07-26 15:20:48.358   910  1598 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-26 15:20:48.368   910   940 I ActivityManager: Recipient 6283,
,07-26 15:20:48.448   910   940 D Process : killProcessQuiet, pid=6283,
07-26 15:20:48.448   910   940 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:48.448   910   940 W libprocessgroup: failed to open /acct/uid_10079/pid_6283/cgroup.procs: No such file or directory
,07-26 15:20:48.498  6716  6770 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:48.498  6716  6770 I jxcore-log: 
,07-26 15:20:48.498  6716  6770 W jxcore-log: JXcore engine is started
,07-26 15:20:48.508  6716  6763 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:48.508  6716  6716 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:48.508  6716  6770 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-26 15:20:48.508  6716  6770 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:20:48.518  6716  6716 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:20:48.518  6716  6716 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:20:48.518   910  1284 I ActivityManager: Killing 6244:com.google.android.gms.unstable/u0a25 (adj 15): empty #17
07-26 15:20:48.518   910  1284 D Process : killProcessQuiet, pid=6244
07-26 15:20:48.518   910  1284 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
,07-26 15:20:48.538   910  1625 I ActivityManager: Recipient 6244
,07-26 15:20:48.588   910  1625 D Process : killProcessQuiet, pid=6244
07-26 15:20:48.588   910  1625 W libprocessgroup: failed to open /acct/uid_10025/pid_6244/cgroup.procs: No such file or directory
07-26 15:20:48.588   910  1625 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:48.588  6716  6763 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 69ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:20:48.588  6716  6716 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
,07-26 15:20:48.588  6716  6716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:20:48.588  6716  6716 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:48.588  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:48.588  6716  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:48.588  6716  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:48.588  6716  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30589695 removed from the list
07-26 15:20:48.588  6716  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:48.588  6716  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2afd0b38 removed from the list
07-26 15:20:48.588  6716  6716 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:48.588  6716  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:20:48.588  6716  6716 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:20:48.758  6771  6774 E cutils-trace: Error opening trace file: No such file or directory (2)
,07-26 15:20:48.798  6771  6771 D CustomizationManager: ====startRecUseTime====
07-26 15:20:48.798  6771  6771 D htc.customization.log.level:  is 
,07-26 15:20:48.798  6771  6771 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-26 15:20:48.858   910  1035 D PMS     : releaseHCC(2ad30c5b): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
07-26 15:20:48.858   910  1035 D PMS     : releaseHCC(33022cf8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
07-26 15:20:48.858  2279  2299 E MP-Decision: Update arg 1
,07-26 15:20:48.868  6771  6771 D CustomizationManager:  Read ACC file spent 0.042 (s),
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__001
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__102
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__203
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__405
,07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__304
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__032
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__016
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__A48
,07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-26 15:20:48.868  6771  6771 D CIDMapFileReader: Parsing tag item name = HTC__002
07-26 15:20:48.868  6771  6771 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = system
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = application
,07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = Settings
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-26 15:20:48.868  6771  6771 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-26 15:20:48.878  6771  6771 D CustomizationManager:  Read CID file spent 0.079 (s)
07-26 15:20:48.878  6771  6771 D CustomizationManager:  All configurations done spent 0.079 (s)
,07-26 15:20:48.888  6771  6771 E ActTriggerJNI: open library fail.
,07-26 15:20:48.898   910   938 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6771, uid=2000 userid=0,
07-26 15:20:48.898   910  1002 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
,07-26 15:20:48.898   910  1002 I ActivityManager: Killing 6716:com.test.thalitest/u0a192 (adj 9): stop com.test.thalitest
07-26 15:20:48.898   910  1002 D Process : killProcessQuiet, pid=6716
07-26 15:20:48.898   910  1002 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,07-26 15:20:48.928   910  1625 I ActivityManager: Recipient 6716
,07-26 15:20:48.928   910  1082 D WifiService: Client connection lost with reason: 4
,07-26 15:20:48.998   910  1056 W PackageSettings: Skipping PackageSetting{2375adaf com.example.hello/10380} due to missing metadata
,07-26 15:20:49.118   910  1625 W ActivityManager: Spurious death for ProcessRecord{2e7c8fb3 6716:com.test.thalitest/u0a192}, curProc for 6716: null,
07-26 15:20:49.118   910  1056 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
,07-26 15:20:49.128  1202  1202 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-26 15:20:49.128  1202  1202 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-26 15:20:49.128  1202  1202 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,07-26 15:20:49.128  1501  1938 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-26 15:20:49.128  1501  1938 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-26 15:20:49.138  1501  1501 I Launcher: Deferring update until onResume
07-26 15:20:49.138  1501  1501 D Launcher: waitUntilResume // bindAppsRemoved
07-26 15:20:49.138   910   940 D PMS     : acquireWL(1643e970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1726 10025 WorkSource{10025 com.google.android.gms}
,07-26 15:20:49.138   910  1627 D PMS     : releaseWL(1643e970): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,07-26 15:20:49.138   910  1078 D PMS     : acquireWL(2904356e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,07-26 15:20:49.138   910  1079 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
,07-26 15:20:49.148  1601  2002 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-26 15:20:49.158  1601  2002 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,07-26 15:20:49.158  1501  1501 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
,07-26 15:20:49.168  1384  6785 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,07-26 15:20:49.168  1437  1437 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
,07-26 15:20:49.168  1384  6785 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
07-26 15:20:49.168   910  1078 D PMS     : releaseWL(2904356e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-26 15:20:49.168   910  1079 V NetworkPolicy: writePolicyLocked()
,07-26 15:20:49.168  1575  6786 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-26 15:20:49.178  1601  2002 E ExternalAccountType: Unsupported attribute readOnly,
,07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfofornet-, err=8
07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfo_proxy+
07-26 15:20:49.188   910  1079 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-26 15:20:49.198   460  6794 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-26 15:20:49.198   460  6794 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-26 15:20:49.198   910  1057 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,07-26 15:20:49.208   910   910 W PackageManager: Unable to load service info ResolveInfo{1818af6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-26 15:20:49.208   910   910 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-26 15:20:49.208   910   910 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:49.208   910   910 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-26 15:20:49.208   910   910 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-26 15:20:49.208   910   910 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-26 15:20:49.208   910   910 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:49.208   910   910 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:49.208   910   910 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
07-26 15:20:49.208   910   910 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,07-26 15:20:49.218   910  1001 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-26 15:20:49.248   460  6794 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-26 15:20:49.248   460  6794 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-26 15:20:49.248   910  1079 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-26 15:20:49.268   910  1079 V NetworkPolicy: updateNetworkEnabledLocked()
07-26 15:20:49.268   910  1079 V NetworkPolicy: updateNotificationsLocked()
,07-26 15:20:49.268   910   910 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.298   910  1001 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-26 15:20:49.298  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,07-26 15:20:49.298   910  1009 D StatusBarManagerService: setSystemUiVisibility(0x8700)
,07-26 15:20:49.298   910  1009 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:49.298   910  1009 D StatusBarManagerService: hiding MENU key
07-26 15:20:49.298   910  1009 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-26 15:20:49.298   910  1009 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:49.298   910  1009 D StatusBarManagerService: hiding MENU key,
,07-26 15:20:49.308   910  1056 I art     : Explicit concurrent mark sweep GC freed 29373(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 17MB/26MB, paused 1.493ms total 190.593ms
,07-26 15:20:49.318   910  1599 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6716 uid 10192
07-26 15:20:49.318   910  1599 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-26 15:20:49.328  1830  1830 E NetworkScheduler.SchedulerReceiver: Invalid parameter app,
,07-26 15:20:49.328  1830  1830 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-26 15:20:49.328   910  1269 D PMS     : acquireWL(3213d9af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1830 10025 WorkSource{10025 com.google.android.gms}
,07-26 15:20:49.338   910  1626 D PMS     : releaseWL(3213d9af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,07-26 15:20:49.348   910  1600 I ActivityManager: Killing 5205:com.htc.bgp/u0a11 (adj 15): empty #17,
07-26 15:20:49.348   910  1600 D Process : killProcessQuiet, pid=5205
07-26 15:20:49.348   910  1600 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-26 15:20:49.358   910  1624 I ActivityManager: Recipient 5205,
,07-26 15:20:49.418   910  1624 D Process : killProcessQuiet, pid=5205
,07-26 15:20:49.418   910  1624 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:49.418   910  1624 W libprocessgroup: failed to open /acct/uid_10011/pid_5205/cgroup.procs: No such file or directory
,07-26 15:20:49.428  4322  6813 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:49.428  4322  4322 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:49.428  4322  4322 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:20:49.428  4322  6813 D AccountUtils: Clearing selected account for com.test.thalitest
,07-26 15:20:49.438  4322  4322 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,07-26 15:20:49.438  4322  4322 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:20:49.438  6432  6816 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,07-26 15:20:49.448   910  1623 D PMS     : acquireWL(32867f33): PARTIAL_WAKE_LOCK  AsyncService 0x1 6519 10176 null
,07-26 15:20:49.448   910  1600 D PMS     : releaseWL(32867f33): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-26 15:20:49.448   910  1307 D PMS     : acquireWL(19d0f069): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6519 10176 null
07-26 15:20:49.458  6548  6548 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
07-26 15:20:49.458  6548  6548 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,07-26 15:20:49.458   910  1600 D PMS     : releaseWL(19d0f069): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-26 15:20:49.458  6548  6548 I DeviceManagement: WorkflowService: Starting workflow service
,07-26 15:20:49.458  6548  6819 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@67706f9] args=[Bundle[mParcelledData.dataSize=112]]
07-26 15:20:49.458  6548  6819 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-26 15:20:49.458  6548  6819 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
07-26 15:20:49.458  6548  6819 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,07-26 15:20:49.468  6548  6819 I DeviceManagement: ModelRegistry: Loading model meta data from resources...,
,07-26 15:20:49.478   910  1284 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6820 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a,
,07-26 15:20:49.488  4322  6813 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-26 15:20:49.508  6548  6819 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,07-26 15:20:49.508   910  1307 D PMS     : acquireWL(34a978dd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4322 10025 null
,07-26 15:20:49.518  4322  4322 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-26 15:20:49.518   910  1600 D PMS     : releaseWL(34a978dd): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-26 15:20:49.518  6548  6841 I DeviceManagement: SessionStateController: Checking invariants...
,07-26 15:20:49.518  4322  6836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,07-26 15:20:49.518  4322  6836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-26 15:20:49.518  4322  6836 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-26 15:20:49.518  4322  6836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-26 15:20:49.528  4322  6836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,07-26 15:20:49.528  4322  6836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2,
07-26 15:20:49.528  4322  6836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-26 15:20:49.528  4322  6839 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:20:49.538  4322  6836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,07-26 15:20:49.538  4322  6836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-26 15:20:49.538  4322  6839 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:20:49.548  4322  6836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,07-26 15:20:49.548  4322  6836 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,07-26 15:20:49.548  4322  6836 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-26 15:20:49.548  4322  6836 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,07-26 15:20:49.588  4322  4322 I ConfigFetchService: service connected,
,07-26 15:20:49.598  4322  6845 I PeopleContactsSync: CP2 sync disabled
07-26 15:20:49.598   910  1377 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4322, uid=10025, userID:0
,07-26 15:20:49.598   910  1600 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6846 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a,
07-26 15:20:49.598  6313  6313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-26 15:20:49.608   910   940 D PMS     : acquireWL(4dcc3aa): PARTIAL_WAKE_LOCK  Icing 0x1 4322 10025 WorkSource{10025 com.google.android.gms},
,07-26 15:20:49.608  6313  6855 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-26 15:20:49.608  6313  6855 D PowerUsageService: removed uid = 10192
,07-26 15:20:49.608  4322  4404 I Icing   : doRemovePackageData com.test.thalitest
,07-26 15:20:49.628   910  1307 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=6865 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:20:49.638  6432  6816 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 200 ms] updated apps [took 200 ms] 
,07-26 15:20:49.668  6865  6865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:20:49.668  6846  6846 D ExternalStorage: After updating volumes, found 1 active roots
,07-26 15:20:49.698  4322  6829 W DriveInitializer: Awaiting to be initialized,
,07-26 15:20:49.698  4322  6891 W DriveInitializer: Background init thread started
,07-26 15:20:49.708   910   940 I ActivityManager: Killing 6341:com.htc.mobiledata/u0a48 (adj 15): empty #17,
07-26 15:20:49.708   910   940 D Process : killProcessQuiet, pid=6341
07-26 15:20:49.708   910   940 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-26 15:20:49.718   910  1377 I ActivityManager: Recipient 6341,
,07-26 15:20:49.718  6548  6841 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,07-26 15:20:49.738   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/,
07-26 15:20:49.738   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:20:49.748  4322  6891 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files,
,07-26 15:20:49.758   910  1377 D Process : killProcessQuiet, pid=6341,
07-26 15:20:49.758   910  1377 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:49.758   910  1377 W libprocessgroup: failed to open /acct/uid_10048/pid_6341/cgroup.procs: No such file or directory
,07-26 15:20:49.798  6820  6844 D Documents: Update found 7 roots in 238ms
,07-26 15:20:49.808  6820  6885 D Documents: Update found 7 roots in 138ms
,07-26 15:20:49.808  6548  6819 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,07-26 15:20:49.808  6548  6819 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-26 15:20:49.808  6548  6819 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0xb99f7798
,07-26 15:20:49.818  6548  6819 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@67706f9]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
07-26 15:20:49.818  6548  6819 W DeviceManagement: ,	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
07-26 15:20:49.818  6548  6819 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.818  6548  6548 I DeviceManagement: WorkflowService: Stopping workflow service
07-26 15:20:49.818   910  1402 I ActivityManager: Killing 6369:com.google.android.talk/u0a120 (adj 15): empty #17
07-26 15:20:49.818   910  1402 D Process : killProcessQuiet, pid=6369
07-26 15:20:49.818   910  1402 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-26 15:20:49.828  4322  6902 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-26 15:20:49.828  4322  6902 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb9baa088
07-26 15:20:49.838   910  1626 I ActivityManager: Recipient 6369
07-26 15:20:49.838  4322  6891 W DriveInitializer: Background init thread ended
07-26 15:20:49.848  4322  6902 E AndroidRuntime: FATAL EXCEPTION: pool-13-thread-1
07-26 15:20:49.848  4322  6902 E AndroidRuntime: Process: com.google.android.gms, PID: 4322
07-26 15:20:49.848  4322  6902 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.a.a.a.a(SourceFile:65)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.a.a.b.run(SourceFile:97)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-26 15:20:49.848  4322  6902 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,07-26 15:20:49.868   910  1626 D Process : killProcessQuiet, pid=6369
07-26 15:20:49.868   910  1626 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:49.868   910  1626 W libprocessgroup: failed to open /acct/uid_10120/pid_6369/cgroup.procs: No such file or directory
07-26 15:20:49.868   910  1625 E ActivityManager: App crashed! Process: com.google.android.gms
07-26 15:20:49.868  4322  6902 D Process : killProcess, pid=4322
07-26 15:20:49.868  4322  6902 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
07-26 15:20:49.878   910  6905 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:20:49.878   910  6905 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:20:49.878   910  6905 E DropBoxManagerService: 	... 5 more
07-26 15:20:49.888   910  1599 D Process : killProcessQuiet, pid=4322
07-26 15:20:49.888   910  1599 I ActivityManager: Recipient 4322
07-26 15:20:49.888   910  1599 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-26 15:20:49.888   910  1057 D PMS     : handleWLDeath(4dcc3aa): PARTIAL_WAKE_LOCK  Icing 0x1
07-26 15:20:49.888   910  1082 D WifiService: Client connection lost with reason: 4
,07-26 15:20:49.928   910  1599 I ActivityManager: Process com.google.android.gms (pid 4322) has died
,07-26 15:20:49.928  1830  1830 I ConfigService: onDestroy
,07-26 15:20:49.928   910  1599 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
07-26 15:20:49.928   910  1599 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
07-26 15:20:49.928   910  1599 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
07-26 15:20:49.928   910  1599 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
07-26 15:20:49.928   910  1599 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,07-26 15:20:50.658  1501  1938 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-26 15:20:50.658  1501  1938 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@34ef3feb +
,07-26 15:20:50.658  1501  1938 I Prism.WidgetManager: onLoadItems() +,
,07-26 15:20:50.908  1501  1938 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.

```
