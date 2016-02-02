#### Test 575312435db8e90_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
W/CSCSettings( 2753): Setting Ringtones (type) : 2
D/CscParser( 2753): MessageTone: null
W/CSCSettings( 2753): 1. Tag_Str: null
D/TimaKeyStoreProvider( 6299): in addTimaSignatureService
W/CSCSettings( 2753): Setting Ringtones (type) : 1
D/CscParser( 2753): RingTone: null
W/CSCSettings( 2753): 1. Tag_Str: null
D/TimaKeyStoreProvider( 6299): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6299): Added TimaKesytore provider
W/CSCSettings( 2753): Setting Ringtones (type) : 4
D/CscParser( 2753): AlarmTone: null
W/CSCSettings( 2753): 1. Tag_Str: null
I/SELinux ( 6306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6306):  
I/SELinux ( 6306):  
I/SELinux ( 6306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6306): >>>>> Normal User
E/dalvikvm( 6306): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
E/SELinux ( 6306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6306): in addTimaSignatureService
D/TimaKeyStoreProvider( 6306): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6306): Added TimaKesytore provider
D/dalvikvm( 6299): GC_CONCURRENT freed 3015K, 29% free 9560K/13408K, paused 3ms+2ms, total 29ms
D/dalvikvm( 6299): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/dalvikvm( 6306): GC_CONCURRENT freed 2994K, 29% free 9569K/13400K, paused 4ms+2ms, total 29ms
D/dalvikvm( 6306): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/FactoryTestApp( 5612): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
I/FactoryTestApp( 5612): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 5612): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 5612): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 5612): [Support$Properties.get] property=ro.factory.factory_binary
I/FactoryTestApp( 5612): [ModuleCommon$setMediascanningCounter]  
I/FactoryTestApp( 5612): [ModuleCommon$getMediaScanningCount] get : 1
I/IndexBroadcastProcessorService( 6306): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
D/FactoryTest( 5612): User mode
I/FactoryTestApp( 5612): [ModuleCommon$getMediaScanningCount] get : 2
I/FactoryTestApp( 5612): [ModuleCommon$getMediaScanningCount] get : 2
D/FactoryTestApp( 5612): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
D/FactoryTestApp( 5612): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 5612): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 5612): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
I/FactoryTestApp( 5612): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
I/FactoryTestApp( 5612): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
I/IndexBroadcastProcessorService( 6306): lucene systemReadyToIndex
--------- beginning of /dev/log/system
W/ContextImpl( 5612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
D/FactoryTestApp( 5612): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=true
I/FactoryTestApp( 5612): [FactoryTestBroadcastReceiver$wake lock] SUPPORT_BOOST_MEDIASCAN
I/FactoryTestApp( 5612): [ModulePower$ModulePower] Create ModulePower
I/FactoryTestApp( 5612): [ModulePower$doMediaScanWakeLock] wake=false
D/FactoryTest( 5612): User mode
I/FactoryTestApp( 5612): [ModuleCommon$15 Test Ready flag] set
I/IndexService( 6306): lucene onCreate ...service
I/FactoryTestApp( 5612): [ModuleCommon$isFirstBoot] before : false
D/FactoryTestApp( 5612): [DummyFtClient$onCreate] Create DummyFtClient service
I/FactoryTestApp( 5612): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 5612): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 5612): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 5612): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTestApp( 5612): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
D/FactoryTestApp( 5612): [DummyFtClient$onStartCommand] ...
D/FactoryTestApp( 5612): [DummyFtClient$sendBootCompletedAndFinish] ...
D/FactoryTestApp( 5612): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 5612): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
I/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
W/ContextImpl( 5612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
D/GalleryCacheReady( 3372): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 3372): handleMeidaScanFinish()
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/SELinux ( 6335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6335):  
W/ContextImpl( 6306): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6306): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/FaceInterface( 3372): requestFaceScan() is called.
I/FaceInterface( 3372): startFaceScan() : waiting 5 sec
W/LocalSuggestAlbumData( 3372): query fail: 
W/LocalSuggestAlbumData( 3372): query fail: 
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 3244): SLink location service is enable. content://media/external/images/media not register
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 3244): SLink location service is enable. content://media/external/video/media not register
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
I/LocationTagReadyService( 3244): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
I/SELinux ( 6335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6335):  
I/SELinux ( 6335):  
I/SELinux ( 6335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6335): >>>>> Normal User
E/dalvikvm( 6335): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
I/SettingSearchManagerReceiver( 2753): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 2753): addSearchInfoDB
E/SELinux ( 6335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3244): [Slink platform] The state of Slink geocode service is true
I/SELinux ( 6353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6353):  
D/TimaKeyStoreProvider( 6335): in addTimaSignatureService
D/TimaKeyStoreProvider( 6335): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6335): Added TimaKesytore provider
I/SELinux ( 6357): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6357):  
I/dalvikvm( 6306): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 6306): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
D/dalvikvm( 6306): VFY: replacing opcode 0x71 at 0x01ed
I/SELinux ( 6353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6353):  
I/SELinux ( 6353):  
I/SELinux ( 6353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6353): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6353): >>>>> Normal User
E/dalvikvm( 6353): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10162 ]
E/SELinux ( 6353): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6353): in addTimaSignatureService
I/SELinux ( 6357): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6357):  
I/SELinux ( 6357):  
I/SELinux ( 6357): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6357): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6357): >>>>> Normal User
E/dalvikvm( 6357): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
D/TimaKeyStoreProvider( 6353): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6353): Added TimaKesytore provider
E/SELinux ( 6357): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/IndexService( 6306): lucene beginIndexing
D/TimaKeyStoreProvider( 6357): in addTimaSignatureService
D/TimaKeyStoreProvider( 6357): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6357): Added TimaKesytore provider
I/GallerySearchProvider( 3372): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
I/SELinux ( 6381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6381):  
D/dalvikvm( 6353): GC_CONCURRENT freed 2995K, 29% free 9574K/13404K, paused 2ms+1ms, total 34ms
D/dalvikvm( 6353): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/dalvikvm( 6335): GC_CONCURRENT freed 2998K, 29% free 9567K/13404K, paused 3ms+2ms, total 25ms
D/dalvikvm( 6335): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/IndexService( 6306): lucene onDestroy start
I/IndexService( 6306): lucene onDestroy end
I/SELinux ( 6381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6381):  
I/SELinux ( 6381):  
I/SELinux ( 6381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/IndexService( 6306): lucene cleanupEverything start
E/SELinux ( 6381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6381): >>>>> Normal User
E/dalvikvm( 6381): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
E/SELinux ( 6381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 6357): GC_CONCURRENT freed 2988K, 29% free 9578K/13404K, paused 3ms+2ms, total 33ms
D/dalvikvm( 6357): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/IndexService( 6306): ERROR: null
E/ParserThreadsListManager( 6306): Lucene Interrupt in run
I/IndexService( 6306): lucene cleanupEverything end
I/Process ( 6306): Sending signal. PID: 6306 SIG: 9
D/TimaKeyStoreProvider( 6381): in addTimaSignatureService
D/TimaKeyStoreProvider( 6381): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6381): Added TimaKesytore provider
I/ActivityManager( 2421): Process com.samsung.indexservice (pid 6306) (adj 9) has died.
I/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$onServiceConnected] connected done
D/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
D/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$write] Response ��
D/AT_Distributor( 1958): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/AT_Distributor( 1958): SetAtdStatus(), 1_1_0
D/AT_Distributor( 1958): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
D/dalvikvm( 6381): GC_CONCURRENT freed 2998K, 29% free 9571K/13404K, paused 2ms+2ms, total 23ms
D/dalvikvm( 6381): WAIT_FOR_CONCURRENT_GC blocked 20ms
V/KVNProvider( 6381): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
V/KVNProvider( 6381): getFindoCursor query string : 
I/SettingSearchManagerReceiver( 2753): endInsert
I/MediaStoreImporter( 6214): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
V/KVNProvider( 6381): getTagSearchCursor() tagSearchCursor count : 0
I/SELinux ( 6398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6398):  
I/ActivityManager( 2421): Killing 5179:com.sec.android.app.camera/u0a149 (adj 15): empty #43
I/ActivityManager( 2421): Killing 5231:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
I/SELinux ( 6398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6398):  
I/SELinux ( 6398):  
I/SELinux ( 6398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6398): >>>>> Normal User
E/dalvikvm( 6398): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
E/SELinux ( 6398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6398): in addTimaSignatureService
I/ActivityManager( 2421): Killing 5256:com.sec.modem.settings/1000 (adj 15): empty #43
D/TimaKeyStoreProvider( 6398): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6398): Added TimaKesytore provider
D/dalvikvm( 6398): GC_CONCURRENT freed 2995K, 29% free 9567K/13400K, paused 2ms+2ms, total 25ms
D/dalvikvm( 6398): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/AssistantMenuSettingSearch( 6398): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 6398): Make Setting DB
,W/ContextImpl( 6398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 
I/ActivityManager( 2421): Killing 5295:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/knox    ( 5091): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT
W/ContextImpl( 5091): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 5091): KNOXAgentService. startJobThread() start
D/knox    ( 5091): KNOXAgentService. JobThread()
D/knox    ( 5091): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5091): KNOXAgentService. startJobThread() wait
D/knox    ( 5091): KNOXAgentService : onCreate()
D/knox    ( 5091): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5091): startFileChecker
I/knox    ( 5091): start checking file is exist to uploading
D/knox    ( 5091): notiShow :0 / context pref : 2
D/knox    ( 5091): KNOXAgentService : onDestroy().
D/knox    ( 5091): ModuleBase.cancelAllAlarmManageModule()
I/knox    ( 5091): denial log zip completed
D/daemonapp( 5348): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5348): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5348): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5348): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/dalvikvm( 5348): GC_CONCURRENT freed 2653K, 26% free 9950K/13408K, paused 4ms+6ms, total 45ms
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/comdaemonstockapp( 5348): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: widgetappstockclockDAEMON_PROCESS_START
D/comdaemonstockapp( 5348): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
D/comdaemonstockapp( 5348): [Daemon_Stock]>>> StockclockDaemonService.java:113 [0:0] isFirstRunning , false
D/daemonapp( 5348): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5348): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5348): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5348): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
D/daemonapp( 5348): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5348): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5348): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5348): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
D/daemonapp( 5348): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5348): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5348): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5348): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5348): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 5348): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5348): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
I/ActivityManager( 2421): Waited long enough for: ServiceRecord{432ffa08 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
D/AndroidRuntime( 6411): 
D/AndroidRuntime( 6411): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6411): CheckJNI is OFF
D/AndroidRuntime( 6411): setted country_code = Poland
D/AndroidRuntime( 6411): setted countryiso_code = PL
D/AndroidRuntime( 6411): setted sales_code = PLS
D/AndroidRuntime( 6411): readGMSProperty: start
D/AndroidRuntime( 6411): readGMSProperty: already setted!!
D/AndroidRuntime( 6411): readGMSProperty: end
D/AndroidRuntime( 6411): addProductProperty: start
D/dalvikvm( 6411): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6411): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6411): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6411): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6411): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/GCM     ( 2856): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/GCoreFlp( 2735): No location to return for getLastLocation()
W/FusedLocationProvider( 2735): location=null
I/ActivityManager( 2421): Killing 5363:com.gameloft.android.GloftGF2H/u0a179 (adj 15): empty #43
E/memtrack( 6411): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6411): failed to load memtrack module: -2
D/dalvikvm( 6411): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/SPPClientService( 5546): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
I/SELinux ( 6431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6431):  
D/SSRMv2:SIOP( 2421): SIOP:: AP = 350, Delta = -10
D/AndroidRuntime( 6411): Calling main entry com.android.commands.am.Am
I/SELinux ( 6431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6431):  
I/SELinux ( 6431):  
I/SELinux ( 6431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6431): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6431): >>>>> Normal User
E/dalvikvm( 6431): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
E/SELinux ( 6431): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6431): in addTimaSignatureService
D/TimaKeyStoreProvider( 6431): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6431): Added TimaKesytore provider
D/AndroidRuntime( 6411): Shutting down VM
D/dalvikvm( 6411): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+0ms, total 6ms
D/dalvikvm( 6431): GC_CONCURRENT freed 2993K, 29% free 9567K/13400K, paused 8ms+2ms, total 34ms
D/dalvikvm( 6431): WAIT_FOR_CONCURRENT_GC blocked 25ms
E/SPPClientService( 6431): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6431): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 6431): PushLog.txt file is not deleted.
D/SPPClientService( 6431): PushLog.txt file is not deleted.
D/SPPClientService( 6431): ============PushLog. stop!
I/SELinux ( 6450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6450):  
I/ActivityManager( 2421): Killing 5376:com.gameloft.android.GloftKLMF/u0a180 (adj 15): empty #43
I/SELinux ( 6450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6450):  
I/SELinux ( 6450):  
I/SELinux ( 6450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6450): >>>>> Normal User
E/dalvikvm( 6450): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6450): in addTimaSignatureService
D/TimaKeyStoreProvider( 6450): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6450): Added TimaKesytore provider
D/dalvikvm( 6450): GC_CONCURRENT freed 2997K, 29% free 9569K/13400K, paused 2ms+2ms, total 26ms
D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 23ms
E/SPPClientService( 6450): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6450): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 6450): PushLog.txt file is not deleted.
D/SPPClientService( 6450): PushLog.txt file is not deleted.
D/SPPClientService( 6450): ============PushLog. stop!
I/ActivityManager( 2421): Killing 5392:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
E/MTPRx   ( 5624): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 5624): check value of boot_completed is1
E/MTPRx   ( 5624): check booting is completed_sys.boot_completed
E/MTPRx   ( 5624): Sd-Card path/storage/extSdCard
E/MTPRx   ( 5624): Status for mount/Unmount :removed
E/MTPRx   ( 5624): SDcard is not available
W/MTPRx   ( 5624): value of connected istrue
W/MTPRx   ( 5624): value of configured istrue
W/MTPRx   ( 5624): value of mtpEnabled istrue
W/MTPRx   ( 5624): value of ptpEnabled isfalse
E/MTPRx   ( 5624): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 5624): mtpRunningStatus1
E/MTPRx   ( 5624): MTP already launched. So return.
D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
D/dalvikvm( 2421): GC_EXPLICIT freed 1310K, 12% free 24569K/27892K, paused 8ms+18ms, total 220ms
D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2581): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off
,D/dalvikvm( 5405): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5405): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5405): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5405): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5405): VFY: unable to resolve instance field 36
,D/dalvikvm( 5405): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5405): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5405): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5405): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5405): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5405): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5405): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c4ecf8
,D/dalvikvm( 5405): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c4ecf8
,D/dalvikvm( 5405): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c4ecf8, skipping init
,D/dalvikvm( 5405): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c4ecf8
,D/dalvikvm( 5405): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c4ecf8
,V/JNIHelp ( 5405): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5405): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c4ecf8
,D/dalvikvm( 5405): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42c4ecf8
D/dalvikvm( 5405): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c4ecf8
,D/dalvikvm( 5405): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c4ecf8
,I/ProviderInstaller( 5405): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 6476): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6476):  
,I/SELinux ( 6476): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6476):  
I/SELinux ( 6476):  
,I/SELinux ( 6476): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6476): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6476): >>>>> Normal User
,E/dalvikvm( 6476): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 6476): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6476): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6476): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6476): Added TimaKesytore provider
,D/dalvikvm( 6476): GC_CONCURRENT freed 3012K, 29% free 9560K/13408K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6476): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/FactoryTestApp( 5612): [IPCWriterToSecPhoneService$disConnectSecPhoneService]  
,I/Icing.InternalIcingCorporaProvider( 6476): Updating corpora: A: com.google.android.gms, C: MAYBE
,D/FileShare-Server( 4866): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/SELinux ( 6490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6490):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 44K, 9% free 9504K/10380K, paused 4ms+4ms, total 44ms
,I/SELinux ( 6490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6490):  
I/SELinux ( 6490):  
,I/SELinux ( 6490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6490): >>>>> Normal User
,E/dalvikvm( 6490): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 6490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 9% free 9504K/10380K, paused 3ms+5ms, total 37ms
,D/TimaKeyStoreProvider( 6490): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6490): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6490): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 9% free 9504K/10380K, paused 3ms+4ms, total 36ms
,I/SELinux ( 6504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6504):  
,D/LocationManagerService( 2421): getProviders()=[passive]
,I/SELinux ( 6504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6504):  
I/SELinux ( 6504):  
,I/SELinux ( 6504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6504): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 6504): >>>>> Normal User
,E/dalvikvm( 6504): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 6504): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6504): in addTimaSignatureService
D/dalvikvm( 6490): GC_CONCURRENT freed 3005K, 29% free 9567K/13404K, paused 4ms+2ms, total 35ms
,D/dalvikvm( 6490): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/TimaKeyStoreProvider( 6504): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6504): Added TimaKesytore provider
,D/BezelQuickConnect( 5162): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5162): BezelBroadcastReceiver - packageName : com.google.android.gms
,D/PackageBroadcastService( 3434): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3434): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 2421): Killing 5428:com.google.android.youtube/u0a175 (adj 15): empty #43
,D/dalvikvm( 6504): GC_CONCURRENT freed 2990K, 29% free 9579K/13408K, paused 10ms+3ms, total 45ms
,D/dalvikvm( 6504): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/Icing   ( 3434): updateResources: need to parse f{com.google.android.gms}
,I/dalvikvm( 3698): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 3698): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3698): VFY: replacing opcode 0x6e at 0x0017
,I/DBG_DIAGMONDM( 5736): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 4728): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,D/Headlines( 5847): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5847): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5847): Breath 17388 latestRequest time : 1454412314253 current time : 1454412331641
,D/dalvikvm( 3698): GC_CONCURRENT freed 2373K, 25% free 10156K/13408K, paused 7ms+7ms, total 107ms
I/ActivityManager( 2421): Killing 5707:com.sec.pcw.device/1000 (adj 15): empty #43
,E/SPPClientService( 5546): [g] getNetMCC return empty string
,E/SPPClientService( 5546): [g] getNetMNC return empty string
,D/Mms/MessagesLockscreen( 6091): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
,E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
,I/SettingSearch/SearchIntentReceiver( 2832): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 2832): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread start --> mDoingInitTitleDB : true
I/SettingSearch/SearchIntentReceiver( 2832): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 2832): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/FaceInterface( 3372): startFaceScan() : going on
,D/FaceInterface( 3372): startFaceScan() is called.
,D/ContentApp( 2723): startScan() is called.
,D/FaceValue( 2723): mSleepTime: 800
,D/FaceValue( 2723): mMaxThreadNum: 2
,W/FaceValue( 2723): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 2723): startScan() is end.
D/ContentApp( 2723): face_restore FINISHED_TYPE: 3
D/FaceScanner( 2723): isNeedToRestore : start
,I/SettingSearch/SettingsSearchManager( 2832): Infomation -> numtitleinfo : 0 numSearchinfo : 319
,I/SettingSearch/SettingsSearchManager( 2832):  Infomation -> getItem size : 319
,W/ContextImpl( 6214): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 6214): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 6214): onCreate
,D/CacheService( 6214): onBind
,I/MusicLeanback( 6214): Conditions not met for autocaching.
,I/MusicLeanback( 6214): Stop autocaching.
,D/CacheService( 6214): onDestroy
,I/Icing.InternalIcingCorporaProvider( 6476): UpdateCorporaTask done [took 1257 ms] updated apps [took 1257 ms] 
,D/FactoryTestApp( 5612): [DummyFtClient$onDestroy] Destroy DummyFtClient service
D/FactoryTestApp( 5612): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 5612): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 5612): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
,D/FactoryTestApp( 5612): [DummyFtClient$onDestroy] kill process
,I/Process ( 5612): Sending signal. PID: 5612 SIG: 9
I/ActivityManager( 2421): Killing 5719:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,I/FaceInterface( 3372): startFaceScan() : going on
,D/FaceInterface( 3372): startFaceScan() is called.
,D/ContentApp( 2723): startScan() is called.
,D/ContentApp( 2723): startScan() is end.
D/ContentApp( 2723): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 2723): isNeedToRestore : start
,I/ActivityManager( 2421): Process com.sec.factory (pid 5612) (adj 0) has died.
,I/Icing   ( 3434): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 3434): GC_CONCURRENT freed 1691K, 17% free 12786K/15312K, paused 6ms+9ms, total 75ms
,D/dalvikvm( 3434): WAIT_FOR_CONCURRENT_GC blocked 39ms
,W/SQLiteConnectionPool( 3434): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 3434): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/Icing   ( 3434): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 3434): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/dalvikvm( 2832): GC_EXPLICIT freed 491K, 24% free 10274K/13488K, paused 8ms+7ms, total 65ms
,D/dalvikvm( 6353): GC_EXPLICIT freed 882K, 25% free 10149K/13404K, paused 3ms+10ms, total 51ms
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{43154e60 u0 com.sec.spp.push/.PushClientService}
,D/dalvikvm( 2421): GC_EXPLICIT freed 1189K, 12% free 24559K/27892K, paused 8ms+18ms, total 217ms
,I/ActivityManager( 2421): Killing 5671:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/PackageManager( 2421): [MSG] MCS_UNBIND
I/PackageManager( 2421): calling disconnectService()
,D/PackageManager( 2421): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2421): Killing 5783:com.policydm/1000 (adj 15): empty #43
,D/dalvikvm( 2832): GC_EXPLICIT freed 351K, 24% free 10283K/13488K, paused 5ms+8ms, total 49ms
,D/dalvikvm( 6353): GC_EXPLICIT freed 1028K, 26% free 10010K/13404K, paused 3ms+9ms, total 47ms
,E/SPPClientService( 5546): [b] __ProvisionReply__
,V/AlarmManager( 2421):  next == MAX_VALUE
,E/SPPClientService( 5546): [g] getPLMN return empty string
,E/SPPClientService( 5546): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5546): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/dalvikvm( 5546): GC_CONCURRENT freed 2137K, 23% free 10399K/13408K, paused 5ms+4ms, total 48ms
,E/SPPClientService( 5546): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5546): [g] getNetMCC return empty string
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Finsky  ( 3698): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 3698): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3698): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3698): VFY: replacing opcode 0x62 at 0x0038
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2856): GC_EXPLICIT freed 969K, 21% free 10943K/13728K, paused 6ms+12ms, total 91ms
,I/System.out( 3698): Thread-174(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3698): Thread-174(ApacheHTTPLog):isShipBuild true
,I/System.out( 3698): Thread-174(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/IcingInternalCorpora( 3434): getNumBytesRead when not calculated.
,D/dalvikvm( 2832): GC_EXPLICIT freed 343K, 24% free 10294K/13488K, paused 4ms+7ms, total 47ms
,I/System.out( 3698): Thread-174 calls detatch()
,D/dalvikvm( 6353): GC_EXPLICIT freed 898K, 26% free 10005K/13404K, paused 3ms+9ms, total 50ms
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 5546): [b] __InitReply__
I/qtaguid ( 3698): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 3698): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(68) failed with errno -22
,I/System.out( 3698): Thread-175 calls detatch()
,D/Finsky  ( 3698): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3698): Failed write_ctrl(u 68) res=-1 errno=22
,I/qtaguid ( 3698): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(68) failed with errno -22
,I/System.out( 3698): Thread-174 calls detatch()
,I/PowerManagerService( 2421): [PWL] Off : 30s ago
,D/dalvikvm( 3698): GC_CONCURRENT freed 1314K, 19% free 10889K/13396K, paused 4ms+9ms, total 50ms
,D/dalvikvm( 3698): WAIT_FOR_CONCURRENT_GC blocked 28ms
,V/AlarmManager( 2421): waitForAlarm result :4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = -10
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2421): GC_EXPLICIT freed 617K, 13% free 24460K/27892K, paused 8ms+17ms, total 215ms
,D/dalvikvm( 3698): GC_CONCURRENT freed 835K, 13% free 12100K/13772K, paused 4ms+3ms, total 45ms
,D/dalvikvm( 3698): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 3698): GC_FOR_ALLOC freed 1129K, 17% free 12463K/14972K, paused 38ms, total 39ms
,D/dalvikvm( 3698): GC_FOR_ALLOC freed 1447K, 19% free 13212K/16172K, paused 38ms, total 39ms
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 2832): GC_EXPLICIT freed 354K, 24% free 10301K/13488K, paused 5ms+7ms, total 52ms
,D/dalvikvm( 6353): GC_EXPLICIT freed 899K, 26% free 10015K/13404K, paused 3ms+9ms, total 46ms
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3698): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 3698): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(68) failed with errno -22
,I/System.out( 3698): Thread-175 calls detatch()
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{43328ad8 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 6353): GC_EXPLICIT freed 906K, 26% free 10013K/13404K, paused 4ms+12ms, total 56ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 350K, 24% free 10309K/13488K, paused 5ms+10ms, total 57ms
,D/Finsky  ( 3698): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 2735): callingUid 10012, callindPid: 2735
,D/DeviceConnectionService( 2735): client connected with version: 8296000
,D/Finsky  ( 3698): [198] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3698): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3698): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3698): Thread-185(HTTPLog):isShipBuild true
,I/System.out( 3698): Thread-185(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2421): waitForAlarm result :8
,D/dalvikvm( 6353): GC_EXPLICIT freed 877K, 26% free 10011K/13404K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 362K, 24% free 10297K/13488K, paused 4ms+8ms, total 58ms
,D/dalvikvm( 2421): GC_EXPLICIT freed 789K, 13% free 24497K/27892K, paused 7ms+16ms, total 212ms
,D/dalvikvm( 6353): GC_EXPLICIT freed 875K, 26% free 10016K/13404K, paused 3ms+8ms, total 45ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/dalvikvm( 2832): GC_EXPLICIT freed 351K, 24% free 10306K/13488K, paused 5ms+12ms, total 106ms
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 6353): GC_EXPLICIT freed 874K, 26% free 10014K/13404K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 346K, 24% free 10311K/13488K, paused 5ms+7ms, total 51ms
,E/Watchdog( 2421): !@Sync 3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
,D/dalvikvm( 6353): GC_EXPLICIT freed 871K, 26% free 10012K/13404K, paused 3ms+9ms, total 46ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 355K, 24% free 10317K/13488K, paused 5ms+8ms, total 49ms
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,D/dalvikvm( 2421): GC_EXPLICIT freed 359K, 13% free 24493K/27892K, paused 8ms+15ms, total 208ms
,D/dalvikvm( 6353): GC_EXPLICIT freed 872K, 26% free 10011K/13404K, paused 4ms+9ms, total 46ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 352K, 24% free 10327K/13488K, paused 4ms+7ms, total 48ms
,D/dalvikvm( 6353): GC_CONCURRENT freed 1471K, 22% free 10496K/13404K, paused 2ms+9ms, total 35ms
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2832): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 2832): LOCALE_CHANGED call search setting db finish!!
,V/AlarmManager( 2421): waitForAlarm result :4,
,D/Headlines( 5847): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5847): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5847): Breath 41646 latestRequest time : 1454412314253 current time : 1454412355899,
,D/Finsky  ( 3698): [187] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 3698): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = -10,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___,
,V/AlarmManager( 2421): <AppSync3 Whitelist>,
,V/AlarmManager( 2421): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/Icing   ( 3434): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3434): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/FactoryTest( 5624): Not factory mode,
,D/FactoryTest( 5624): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5624): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5624): still no open session command from host, so toast,
W/ContextImpl( 5624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2421): mDVFSHelper.acquire(),
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1,
,E/MTPRx   ( 5624): started activity for popup
,E/SettingsReceiverActivity( 5624): PREF_DONT_ASK_AGAIN : true,
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1,
,W/InputMethodManagerService( 2421): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@42f27fe8 attribute=null, token = android.os.BinderProxy@42c44588,
,I/SQLiteSecureOpenHelper( 4194): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4194): getDatabaseLocked(b,b,pwd)...
,D/SettingsReceiverActivity( 5624): dev.kiessupport is : TRUE
,I/DBG_DM  ( 4728): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4728): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 34
,I/DBG_DM  ( 4728): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:418][onResume] Postpone Count : 34
,I/DBG_DM  ( 4728): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4728): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,I/DBG_DM  ( 4728): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 34
,I/DBG_DM  ( 4728): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4728): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4728): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4728): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4728): setTransGradationMode to true,
D/StatusBarManagerService( 2421): semi p:4728,o:t
,I/DBG_DM  ( 4728): [3.19.140541][Line:400][onPause] ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8,
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 75s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5847): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5847): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5847): Breath 75824 latestRequest time : 1454412314253 current time : 1454412390077,
,I/VacuumService( 2735): Vacuum at: now=1454412390347 tag=VacuumService,
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5847): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5847): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5847): Breath 90032 latestRequest time : 1454412314253 current time : 1454412404285,
,E/Watchdog( 2421): !@Sync 5,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 105s ago,
,I/ClearcutLoggerApiImpl( 2856): disconnect managed GoogleApiClient,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5847): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5847): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5847): Breath 120030 latestRequest time : 1454412314253 current time : 1454412434283
,D/Headlines( 5847): stop ,
,D/Headlines( 5847): Breath.onDestroy : ,
I/ActivityManager( 2421): Killing 5821:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,E/Watchdog( 2421): !@Sync 6,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2421): !@Sync 7,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2390K, 13% free 25447K/29168K, paused 189ms, total 189ms,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 8,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 9,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 225s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2421): initializing...,
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
,I/TZ: mc_tlc_communication( 2421): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2421): Opening the session
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 10
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 10,
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 275s ago,
,E/Watchdog( 2421): !@Sync 11,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :4,
,I/SELinux ( 7401): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7401):  
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7401): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7401):  
I/SELinux ( 7401):  
,I/SELinux ( 7401): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7401): >>>>> Normal User,
,E/dalvikvm( 7401): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7401): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7401): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7401): Added TimaKesytore provider,
,D/dalvikvm( 7401): GC_CONCURRENT freed 3000K, 29% free 9570K/13408K, paused 3ms+2ms, total 27ms,
,D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2421): Killing 5859:com.google.android.apps.magazines/u0a115 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 12
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5546): [b] __PingReply__
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 13
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 14
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 15
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2581): GC_CONCURRENT freed 15732K, 33% free 33855K/50416K, paused 21ms+9ms, total 98ms
,E/Watchdog( 2421): !@Sync 16
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 17
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 2978K, 17% free 25405K/30340K, paused 186ms, total 186ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 18
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 19
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 8151
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 20
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 21
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5643): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5643): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2421): waitForAlarm result :4
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x003d
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 24
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2421): !@Sync 22
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Watchdog( 2421): !@Sync 23
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2421): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
V/AlarmManager( 2421): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 24
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 25
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/dalvikvm( 4069): GC_CONCURRENT freed 2893K, 28% free 9727K/13452K, paused 4ms+2ms, total 40ms
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 26
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 3061K, 17% free 25391K/30340K, paused 208ms, total 208ms
D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 27
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 28
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 29
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 30
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 31
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 8462 seconds from now (1454413207128)
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2735): Thread-122(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-122(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2735): GC_CONCURRENT freed 1701K, 19% free 11729K/14384K, paused 6ms+6ms, total 62ms
,D/ConnectivityService( 2421): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 32
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,E/SPPClientService( 5546): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 33
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 34
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 35
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 36
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 37
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 3280K, 17% free 25424K/30340K, paused 220ms, total 220ms
D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 38
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 39
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 40
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2421): !@Sync 41
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 42
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2421): waitForAlarm result :4
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
,D/Sensors ( 2421): LightSensor enableSensor = 1
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3434): Aggregate from 1454411722598 (log), 1454411722598 (data)
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 18
D/SensorManager( 2421): unregisterListener ::   
D/lights  ( 2421): led_pattern : 5 +
,D/lights  ( 2421): led_pattern : 5 -
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5546): [b] __PingReply__
,TIME-OUT KILL (timeout was 1200000ms)
```
