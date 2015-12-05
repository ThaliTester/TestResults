#### Test 50388019f33194e_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/AbsListView( 2485): Get MotionRecognitionManager
D/NearbySource( 2506): Nearby Source Create!
D/NearbyContext( 2506): Nearby Context Create!
--------- beginning of system
D/MotionRecognitionService( 1016):  ssp status : false
W/ContextImpl( 2506): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 2506): Samsung link source created
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
D/ContactProvider( 2506): getAllContactInfoList Start
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2506): Receive : home resume
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
E/SQLiteLog( 1227): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
D/Mms/UIEventReceiver( 2381): ui event
I/splitIntent( 1016): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/BootupListener( 1481): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1001
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/ContactProvider( 2506): getAllContactInfoList End
I/syncContacts( 2506): thread: 248, sync time = 60
D/PhoneUtilsCommon( 1481): isSupportVoLTE is false.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2355): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2355): onReceive : net.mt.init : DONE
D/StatusChecker( 2355): Service state changed : 3 mSub-1
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 1702): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1702): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 1702): VM with version 2.1.0 has multidex support
I/MultiDex( 1702): install
I/MultiDex( 1702): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 1702): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 1702): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 1702): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8b10b0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1702): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1702): COMPAT: Multi user not supported
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCM     ( 1702): GCM config loaded
D/GCM     ( 1702): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1702): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
D/a       ( 1702): Opening database auth.proximity.permit_store...
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GmsCoreStatsServiceLauncher( 1870): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WearableService( 2060): callingUid 10012, callindPid: 2060
E/USB_UICC(  295): Timeout! No signal received. Retry num = 23
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {a9df347}
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/GmsWearableLS( 1678): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/MDM     ( 1678): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1481): query,matched:0, calling pid = 1870
D/TP/SmsProvider( 1481): match 0:Elapsed time : 1.453 ms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TP/MmsProvider( 1481): Query uri=content://mms, match=0, calling pid = 1870
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1481): query,matched:0, calling pid = 1870
D/TP/SmsProvider( 1481): match 0:Elapsed time : 2.579 ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
D/TP/MmsProvider( 1481): Query uri=content://mms, match=0, calling pid = 1870
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
D/LocationInitializer( 1870): Restart initialization of location
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/GCM     ( 1702): Connected
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
D/GCM     ( 1702): Message class com.google.f.a.a.p
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
I/Mms/MmsApp( 2381):  start initViewCache mms
D/Mms/ComposeMessageFragment( 2381): [start]    fillCache consume time = 1745.18703
D/Mms/ComposeMessageFragment( 2381): fillCache, easy = false
V/UserPresentBroadcastReceiver( 1678): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): start check captive portal 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/AbsListView( 2381): Get MotionRecognitionManager
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/MotionRecognitionService( 1016):  ssp status : false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/ComposeMessageFragment( 2381): [end]    fillCache consume time = 144.734584
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/AndroidRuntime( 2623): 
D/AndroidRuntime( 2623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Mms/BubbleViewCache( 2381): fillCache bubble = 1
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/AndroidRuntime( 2623): CheckJNI is OFF
D/AndroidRuntime( 2623): readGMSProperty: start
D/AndroidRuntime( 2623): readGMSProperty: already setted!!
D/AndroidRuntime( 2623): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2623): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2623): readGMSProperty: end
D/AndroidRuntime( 2623): addProductProperty: start
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
E/SQLiteLog( 1702): (283) recovered 85 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/Scheduler( 1702): Use PeriodicScheduler
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
D/comsamsunglog( 1294): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1294): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1294): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1294): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
W/InstanceID/Rpc( 1702): Found 10012
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
D/daemonapp( 1294): [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
D/daemonapp( 1294): [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
D/daemonapp( 1294): [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> RM:257 [0:0] == rCL 1449275223693
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> RM:273 [0:0] EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
D/daemonapp( 1294): [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1449275223719
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1449296823717
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1449296820000
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449296820000
D/SIP     ( 1481): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
E/File    ( 1481): fail readDirectory() errno=2
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
E/AffinityControl( 2623): AffinityControl: registerfunction enter
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
E/Zygote  ( 2636): MountEmulatedStorage()
I/libpersona( 2636): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2636): v2
I/libpersona( 2636): KNOX_SDCARD not a persona
I/SELinux ( 2636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2636 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1294): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/AndroidRuntime( 2623): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 2636): TimaSignature is unavailable
D/ActivityThread( 2636): Added TimaKeyStore provider
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/FocusedStackFrame( 1016): Set to : 0
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/Launcher.HomeView( 1501): onPause
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1501
D/Launcher( 1501): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/AndroidRuntime( 2623): Shutting down VM
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1294): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
D/SecurityLogAgent( 2636):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 2636):  SeDenialReceiver : File path = /data/misc/audit/audit.old
D/daemonapp( 1294): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
D/daemonapp( 1294): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
D/daemonapp( 1294): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
E/Zygote  ( 2654): MountEmulatedStorage()
E/Zygote  ( 2654): v2
I/libpersona( 2654): KNOX_SDCARD checking this for 10174
I/libpersona( 2654): KNOX_SDCARD not a persona
I/SELinux ( 2654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2654 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2654): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/SecurityLogAgent( 2636):  SeDenialReceiver : Start file Zipping Service 
D/daemonapp( 1294): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
W/ContextImpl( 2636): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
D/AdaptiveEventManager( 1177): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
E/daemonapp( 1294): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
D/AdaptiveEventManager( 1177): currentCityId is null
D/AdaptiveEventManager( 1177): NetWork disabled : Don't refresh weather info : 201
D/AdaptiveEventManager( 1177): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1177): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): mWeatherInfo is not reliable
D/daemonapp( 1294): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
D/daemonapp( 1294): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
D/daemonapp( 1294): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
E/daemonapp( 1294): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1294): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
D/daemonapp( 1294): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 1501): updateVisibility : ActivityRecord{43718d6 token=android.os.BinderProxy@238c5492 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/dhcpcd  ( 2293): wlan0: sending IPv6 Router Solicitation
D/SecurityLogAgent( 2636): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2636): FileZippingService : file path =  /data/misc/audit/audit.old
E/Zygote  ( 2667): MountEmulatedStorage()
I/libpersona( 2667): KNOX_SDCARD checking this for 10135
E/Zygote  ( 2667): v2
I/libpersona( 2667): KNOX_SDCARD not a persona
I/SELinux ( 2667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2667 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/daemonapp( 1294): [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
I/SELinux ( 2667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/TimaKeyStoreProvider( 2654): TimaSignature is unavailable
D/ActivityThread( 2654): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
I/art     (  302): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 21.397ms
D/daemonapp( 1294): [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
D/TimaKeyStoreProvider( 2667): TimaSignature is unavailable
D/ActivityThread( 2667): Added TimaKeyStore provider
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 679us total 17.721ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 594us total 26.279ms
E/Zygote  ( 2685): MountEmulatedStorage()
E/Zygote  ( 2685): v2
I/ActivityManager( 1016): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2685 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 2685): KNOX_SDCARD checking this for 1000
I/libpersona( 2685): KNOX_SDCARD not a persona
I/SELinux ( 2685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1501): onStop
V/ActivityThread( 1501): updateVisibility : ActivityRecord{43718d6 token=android.os.BinderProxy@238c5492 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/SELinux ( 2685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/SELinux ( 2685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1016): isKioskContainerExistOnDevice
W/ResourcesManager( 2667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SecurityLogAgent( 2636): FileZippingService : onPremise disabled. Zipping..  
D/TimaKeyStoreProvider( 2685): TimaSignature is unavailable
D/ActivityThread( 2685): Added TimaKeyStore provider
D/Launcher( 1501): onTrimMemory. Level: 20
W/art     ( 2623): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SecurityLogAgent( 2636): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2636): DenialLogFileZipCreator : Not empty 
,W/ResourcesManager( 2685): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 2636): DenialLogFileZipCreator File existence : true audit.old file size 643
,D/SecurityLogAgent( 2636): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2636): FileZippingService : completed task. Returning wakelock . 
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 24
,I/WebViewFactory( 2654): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 2654): Time to load native libraries: 3 ms (timestamps 229-232)
I/LibraryLoader( 2654): Expected native library version number "",actual native library version number ""
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/WebViewChromiumFactoryProvider( 2654): Binding Chromium to main looper Looper (main, tid 1) {22d70c69}
,I/LibraryLoader( 2654): Expected native library version number "",actual native library version number ""
,I/chromium( 2654): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2654): Initializing chromium process, singleProcess=true
,W/art     ( 2654): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2654): ApplicationContext is null in ApplicationStatus
,W/chromium( 2654): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2654): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2654): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2654): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2654): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2654): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2654): Local Branch: 
I/Adreno-EGL( 2654): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2654): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2654):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/FactoryTestApp( 2685): [FactoryTestBroadcastReceiver$onReceive](2685) onReceive action=android.intent.action.BOOT_COMPLETED
W/ActivityThread( 2685): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 2685): [XMLDataStorage$parseXML](2685) is Live Demo : false
D/FactoryTestApp( 2685): [XMLDataStorage$parseXML](2685) modelXML=sm-a500fu.dat
D/FactoryTestApp( 2685): [XMLDataStorage$parseXML](2685) deviceXML=a5ulte.dat
D/FactoryTestApp( 2685): [XMLDataStorage$parseXML](2685) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2685): [XMLDataStorage$parseAsset](2685) parseAsset Is Started
,I/FactoryTestApp( 2685): [XMLDataStorage$parseAsset](2685) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2685): [XMLDataStorage$parseAsset](2685) Decode base file: factory.dat
,D/BluetoothAdapter( 2654): 124720122: getState() :  mService = null. Returning STATE_OFF
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FACTORY_TEST_APP
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FAILHIST_VERSION
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MODEL_NAME
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MODEL_NUMBER
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=CHIPSET_NAME
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=DEVICE_TYPE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BATT_TYPE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PANEL_TYPE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SPEAKER_COUNT
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MIC_COUNT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SVC_LED_TEST_BRIGHTNESS,
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_LTE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_RCV
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FACTORY_TEST_APO
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_EPEN
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HW_VER_EFS
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FONT_SIZE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=RAM_SIZE_IF
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=MULTI_TSK_THD
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_SELFTEST_DISPLAY_DELAY
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_VOLUME_DOWN
,W/art     ( 2654): Attempt to remove local handle scope entry from IRT, ignoring
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_POWER
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_APP_SWITCH
,W/AwContents( 2654): onDetachedFromWindow called when already detached. Ignoring
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_HOME
,D/PhoneWindow( 2654): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2654): *FMB* installDecor flags : 8456448
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_BACK
,D/SystemWebViewEngine( 2654): CordovaWebView is running on device made by: samsung
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEMI_KEY_TEST_VOLUME_UP
,W/art     ( 2654): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2654): Attempt to remove local handle scope entry from IRT, ignoring
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEMI_KEY_TEST_VOLUME_DOWN
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEMI_KEY_TEST_HOME
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_KEY_TEST_THRESHOLD
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_SENSOR_TEST_ACC_REVERSE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=AT_GPSSTEST
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HALL_IC_TEST
,D/OpenGLRenderer( 2654): Render dirty regions requested: true
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=READ_TARGET_GEOMAGNETIC
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SYS_INFO_FONT_SIZE
,W/chromium( 2654): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_NODE_COUNT_WIDTH
,D/PhoneWindow( 2654): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2654): *FMB* isFloatingMenuEnabled return false
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_SELFTEST_MAX_MELFAS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit,
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BOOTLOADER_VERSION
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BATTERY_TEST_MODE
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=BATTERY_VF_OCV
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA0_THERMISTER_CELCIUS
,D/InputDispatcher( 1016): Focus entered window: 2654
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA0_THERMISTER_ADC
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2654): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2654): Initialized EGL, version 1.4
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PA0_THERMISTER_CELCIUS
,D/OpenGLRenderer( 2654): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2654): Enabling debug mode 0
D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=LPA_MODE_SET
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=GEOMAGNETIC_SENSOR_ADC
,D/PanelView( 1177): There is/are notification(s) 
,D/FactoryTestApp( 2685): [XMLDataStorage$redefinitionById](2685) id=GEOMAGNETIC_SENSOR_POWER
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +772ms
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{289b9b4b u0 com.example.hello/.MainActivity t228} time:30693
W/ActivityManager( 1016): mDVFSHelper.release()
,D/FactoryTestApp( 2685): [XMLDataStorage$parseAsset](2685) SemiFunctionMenu
,D/FactoryTestApp( 2685): [XMLDataStorage$parseAsset](2685) parseAsset Is Completed
,I/Timeline( 2654): Timeline: Activity_idle id: android.os.BinderProxy@1302c295 time:30706
,I/SamsungIME( 1802): getCurrentCandidateView
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/,
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=CHIPSET_MANUFACTURE, value=Qualcomm
,D/SamsungIME( 1802): Dismiss ExpandCandiate
,I/FactoryTestApp( 2685): [ModuleCommon$ModuleCommon](2685) Create ModuleCommon
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2685): [Support$Kernel.read](2685) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2685): [ModuleCommon$readFactoryMode](2685) mode: ON
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2685): [FactoryTestBroadcastReceiver$onReceive](2685) KEYSTRING_BLOCK is already existed...
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2685): [Support$Values.getBoolean](2685) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2685): [Support$Properties.get](2685) property=ro.factory.factory_binary
D/FactoryTestApp( 2685): [FactoryTestBroadcastReceiver$onReceive](2685) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2685): [ModuleCommon$getFtClientEnableState](2685) result : false
I/FactoryTestApp( 2685): [ModuleCommon$connectedJIG](2685) ...
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2685): [ModuleCommon$connectedJIG](2685) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc,
I/SamsungIME( 1802): getDebugLevel  : 0x4f4c
D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2685): [Support$Kernel.read](2685) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2685): [ModuleCommon$connectedJIG](2685) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2685): [ModuleCommon$isConnectionModeNone](2685) mConnectionMode = gsm
I/FactoryTestApp( 2685): [ModuleCommon$isRunningFtClient](2685) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2685): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2685) start DummyFtClient service for APO
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2685): User mode
I/FactoryTestApp( 2685): [ModuleCommon$disableFtClient](2685) ...
,D/FactoryTestApp( 2685): [DummyFtClient$onCreate](2685) Create DummyFtClient service
I/FactoryTestApp( 2685): [XMLDataStorage$parsingXML](2685) FtClient => data parsing was completed.
D/FactoryTestApp( 2685): [DummyFtClient$onReceive](2685) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2685): [ModuleCommon$isConnectionModeNone](2685) mConnectionMode = gsm
,D/FactoryTestApp( 2685): [Support$Values.getBoolean](2685) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2685): [DummyFtClient$onStartCommand](2685) ...
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2738): MountEmulatedStorage()
E/Zygote  ( 2738): v2
,I/libpersona( 2738): KNOX_SDCARD checking this for 1002
I/libpersona( 2738): KNOX_SDCARD not a persona
I/SamsungIME( 1802): getDebugLevel  : 0x4f4c
,I/SELinux ( 2738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2738 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 2738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BindingManager( 2654): Cannot call determinedVisibility() - never saw a connection for the pid: 2654
I/WifiService( 1016): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1016): boot completed
D/UsbDeviceManager( 1016): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1016): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1016): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1016): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/SamsungIME( 1802): KeybaordView init() : load resources
,I/KeyguardEffectViewUtil( 1177): set resource id
,D/SettingsProvider( 1016): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1177): handleBootCompleted()
I/PalmMotion( 1016): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1016): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1016): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1016): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/KeyguardUpdateMonitor( 1177): handleBootCompleted()
,I/chromium( 2654): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,D/TimaKeyStoreProvider( 2738): TimaSignature is unavailable
I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
D/ActivityThread( 2738): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/SamsungIME( 1802): getCurrentKeyboard
I/SamsungIME( 1802): getTextKeyboard
,D/SamsungIME( 1802): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/NfcService( 1461): call the applyRouting
,D/SamsungIME( 1802): showDlgMsgBox : false true true
,W/ResourcesManager( 2738): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 2738): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/RecoverySystem( 1016): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1016): No recovery log file
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2762): MountEmulatedStorage(),
I/libpersona( 2762): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 2762): v2
I/libpersona( 2762): KNOX_SDCARD not a persona
I/SELinux ( 2762): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2762 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2762): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2762): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BluetoothA2dpSinkServiceJni( 2738): register_com_android_bluetooth_a2dp_sink
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/Reset_Reason( 1016): resetString = NPON
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 2762): TimaSignature is unavailable
,V/OtaStartupReceiver( 1481): onOtaspChanged: mOtaspMode=1
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityThread( 2762): Added TimaKeyStore provider
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1016): Copying audit failures to DropBox
I/BootReceiver( 1016): Checking for fsck errors
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2782): MountEmulatedStorage()
,E/Zygote  ( 2782): v2
I/libpersona( 2782): KNOX_SDCARD checking this for 1001
I/libpersona( 2782): KNOX_SDCARD not a persona
,I/SELinux ( 2782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2782 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,D/JsMessageQueue( 2654): Set native->JS mode to OnlineEventsBridgeMode
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SensorService( 1016): [SO] 0.172 0.096 10.209
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TimaKeyStoreProvider( 2782): TimaSignature is unavailable
,D/ActivityThread( 2782): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,E/AndroidProtocolHandler( 2654): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SMD     (  287): DCD OFF
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 25
,E/File    ( 2762): fail readDirectory() errno=2
,W/ResourcesManager( 2782): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/BtSettings.ProfileConfig( 2738): Adding GattService
,D/BtSettings.ProfileConfig( 2738): Adding HeadsetService
,D/BtSettings.ProfileConfig( 2738): Adding A2dpService
D/BtSettings.ProfileConfig( 2738): Adding HidService
D/BtSettings.ProfileConfig( 2738): Adding HealthService
,D/BtSettings.ProfileConfig( 2738): Adding PanService
D/BtSettings.ProfileConfig( 2738): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 2738): Adding SapService
D/BtSettings.ProfileConfig( 2738): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 2738): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 2738): Adding SapClientService
D/BtSettings.ProfileConfig( 2738): Adding HidDevService
I/BtSettings.ProfileConfig( 2738): *********Initializing Bluetooth Profile Settings*******
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/Mms/NotificationReceiver( 2381): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2381): handleBootCompleted()
D/FactoryTestApp( 2685): [ProtectedFactoryTestBroadcastReceiver$onReceive](2685) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2685): [ProtectedFactoryTestBroadcastReceiver$onReceive](2685) com.samsung.intent.action.SECPHONE_READY
D/FactoryTest( 2685): User mode
D/Mms/RcsOwnCapsManager( 2381): queue Uri = content://im/queue-messages?box=pending
,D/TP/ImProvider( 1481): im query match24
D/TP/ImProvider( 1481): URI_IM_QUEUED_MESSAGES
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/TP/ImProvider( 1481): ftSesstionId must be a long.
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/TP/ImProvider( 1481): getQueuedImMessages
D/SettingsProvider( 1016): ret = -1
D/TP/ImProvider( 1481): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/Mms/NotificationReceiver( 2381):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2381): Call to GET_LAST_MESSAGES_SENT
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 36727(2021KB) AllocSpace objects, 5(465KB) LOS objects, 33% free, 25MB/38MB, paused 2.808ms total 276.147ms
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = db_smartlock_supported
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/jxcore_app_log( 2654): JniHelper::setJavaVM(0xb8bef450), pthread_self() = -1189827616
,D/JX-Cordova( 2654): jxcore cordova android initializing
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AccessibilityManagerService( 1016): setmDNIeNegative (false)
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/jxcore-log( 2654): Initializing JXcore engine
W/jxcore-log( 2654): JXcore engine is ready
,W/jxcore-log( 2654): Starting JXcore engine
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 2738): make
,I/bluedroid( 2738): init
,I/BluetoothAdapterState( 2738): Entering OffState
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/bte_conf( 2738): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2738): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2738): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2738): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 2738): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 2738): get_profile_interface socket
I/bluedroid( 2738): get_profile_interface map_client
,D/BluetoothAdapterService( 2738): checkAddrForIOP: Loading from conf
,E/audit   ( 1891): type=1400 msg=audit(1449275225.530:205): avc:  denied  { ioctl } for  pid=2654 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1891):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1891): type=1300 msg=audit(1449275225.530:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=beec4d58 items=0 ppid=302 ppcomm=main pid=2654 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1891): type=1320 msg=audit(1449275225.530:205): 
I/GKI_LINUX( 2738): gki_task_entry task_id=1 [BTIF] starting,
,D/BluetoothAdapterProperties( 2738): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 2738): populateRssiValuesNative
,I/bluedroid( 2738): getModelRssiValues
E/BluetoothServiceJni( 2738): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2738): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothA2dp( 2738): doBind(): CallingUid(myUserHandle) = 0
,W/Settings( 1325): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1016): name = bluetooth_name
,D/BluetoothAdapterProperties( 2738): Name is: Thali Test (Galaxy A5),
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 2738): config_hci_snoop_log
D/SettingsProvider( 1016): name = block_emergency_message
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1016): Ble is always on enable gatt
,I/BluetoothManagerService( 1016): enableGattForLeMode, doBind called
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,I/BtGatt.JNI( 2738): classInitNative(L900): classInitNative: Success!
,D/SecContentProvider( 1016): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SettingsProvider( 1016): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/DriveInitializer( 1870): Background init thread started
,D/BluetoothAdapterState( 2738): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 2738): Setting state to 11
I/BluetoothAdapterState( 2738): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2738): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2738): updateAdapterState state is 11
,D/BluetoothAdapterService( 2738): Autoconnection is available 
D/BluetoothAdapterService( 2738): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 2738): getInstant: null
D/BluetoothSecureManager( 2738): calling getMethod for getService
D/BluetoothSecureManager( 2738): calling getService
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1016): [BT Setting State] State =11
,D/BluetoothSecureManager( 2738): getService return binder: android.os.BinderProxy@35cb80b4
,D/BluetoothSecureManagerService( 1016): isSecureModeEnabled
D/BluetoothSecureManagerService( 1016): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 2738): isSecureModeOn:false
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2738): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2738): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2738): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2738): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2738): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 2738): make
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 11
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1870): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/SamsungIME( 1802): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.gatt.GattService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/BtGatt.DebugUtils( 2738): handleDebugAction() action=null
D/BtGatt.GattService( 2738): Received start request. Starting profile...
D/BtGatt.GattService( 2738): start()
D/BtGatt.GattService( 2738): start()
I/bluedroid( 2738): get_profile_interface gatt
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
D/BtGatt.AdvertiseManager( 2738): advertise manager created
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BluetoothBondStateMachine( 2738): StableState(): Entering Off State
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/CursorWrapperInner( 2381): Cursor finalized without prior close()
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,D/BtGatt.GattService( 2738): mStartError = false
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/HeadsetService( 2738): Received start request. Starting profile...
D/HeadsetService( 2738): start()
,I/BluetoothHeadsetServiceJni( 2738): classInitNative: succeeds
,D/HeadsetStateMachine( 2738): make
W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hdp.HealthService
,E/HeadsetStateMachine( 2738): # of Max HF connection is 2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService,
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 2738): get_profile_interface handsfree
,W/jxcore-log( 2654): Platform android
W/jxcore-log( 2654): 
,W/jxcore-log( 2654): Process ARCH arm
W/jxcore-log( 2654): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/GLSActivity( 1702): [ac] getting account id
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2738): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 2738): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DualScoManager( 2738): Instantiating Dual Sco Manager
,I/DualScoManager( 2738): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 2738): createCMTIContentObservers
,D/SettingsProvider( 1016): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 2738): Enter Disconnected: -2
,D/HeadsetService( 2738): mStartError = false
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetStateMachine( 2738): Clear mHeadsetBrsf
,D/HeadsetStateMachine( 2738): map size, before remove : 0
,D/HeadsetStateMachine( 2738): map size, after remove: 0
D/A2dpService( 2738): Received start request. Starting profile...
D/A2dpService( 2738): start()
,I/BluetoothAvrcpServiceJni( 2738): classInitNative: succeeds
,I/bluedroid( 2738): get_profile_interface avrcp
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/RemoteController( 2738): Cannot set synchronization mode on an unregistered RemoteController
,I/jxcore-log( 2654): JXcore Cordova bridge is ready!
I/jxcore-log( 2654): 
,W/jxcore-log( 2654): JXcore engine is started
,I/Avrcp   ( 2738):  Updating now playing list upon AVRCP Start
,I/BluetoothA2dpServiceJni( 2738): classInitNative: succeeds
D/A2dpStateMachine( 2738): make
,D/BluetoothMediaBrowser( 2738):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/bluedroid( 2738): get_profile_interface a2dp
,I/GKI_LINUX( 2738): gki_task_entry task_id=2 [A2DP-MEDIA] starting,
E/bt-btif ( 2738): warning : media task started media_task_refcnt 1 
,D/A2dpService( 2738): mStartError = false
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,D/A2dpStateMachine( 2738): Enter Disconnected: -2
,D/BluetoothMediaBrowser( 2738): no now playing list
D/BluetoothMediaBrowser( 2738):  getNowPlayingId now playing id : -1
,I/BluetoothHidServiceJni( 2738): classInitNative: succeeds
,I/GLSUser ( 1702): [ChannelManager] Attempting to channel bind connection HttpClient.
D/HidService( 2738): Received start request. Starting profile...
D/HidService( 2738): start()
I/bluedroid( 2738): get_profile_interface hidhost
D/HidService( 2738): setHidService(): set to: null
D/HidService( 2738): mStartError = false
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,I/BluetoothHealthServiceJni( 2738): classInitNative: succeeds
I/GLSUser ( 1702): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/HealthService( 2738): Received start request. Starting profile...
D/HealthService( 2738): start()
,I/bluedroid( 2738): get_profile_interface health
,D/HealthService( 2738): mStartError = false
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,I/BluetoothPanServiceJni( 2738): classInitNative(L105): succeeds
,W/DriveInitializer( 1870): Awaiting to be initialized
,D/PanService( 2738): Received start request. Starting profile...
D/PanService( 2738): start()
D/BluetoothPanServiceJni( 2738): initializeNative(L110): pan
I/bluedroid( 2738): get_profile_interface pan
,D/PanService( 2738): mStartError = false
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
D/HeadsetStateMachine( 2738): Proxy object connected
,D/HeadsetStateMachine( 2738): Try to query the phonestate on bind
,I/Telecom ( 1450): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1450): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1450): BluetoothPhoneService: updateHeadsetWithCallState
,E/jxcore-log( 2654): >> samsung-SM-A500FU
E/jxcore-log( 2654): 
,I/jxcore-log( 2654): Total memory 1983787008
I/jxcore-log( 2654): 
,I/jxcore-log( 2654): Free memory 199905280
I/jxcore-log( 2654): 
I/jxcore-log( 2654): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2654): 
I/jxcore-log( 2654): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2654): 
,I/Telecom ( 1450): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1450): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/jxcore-log( 2654): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2654): 
,I/jxcore-log( 2654): Size 720 1280
I/jxcore-log( 2654): 
,E/SmartFaceService( 1016): onReceive: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/SmartFaceIndicator( 1016): no icon
E/SmartFaceService( 1016): mActiveServiceType: 0
E/SmartFaceService( 1016): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1016): updateClientsDone. def. do nothing.
E/SmartFaceService( 1016): Service Type to Worker: 0
E/SmartFaceService( 1016): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1016): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,I/jxcore-log( 2654): Screen Brightness 5
I/jxcore-log( 2654): 
,E/jxcore-log( 2654): Dummy Error Log.
E/jxcore-log( 2654): 
,D/BluetoothA2dp( 1016): Proxy object connected
,W/DriveInitializer( 1870): Background init thread ended
,I/Telecom ( 1450): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothPan( 1016): BluetoothPAN Proxy object connected
,V/AlarmManagerEXT( 1016): mGmsLocationBundling: false
,D/RCPManagerService( 1016): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1016):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/RCPManagerService( 1016): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1016):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
W/BluetoothHeadset( 1450): Proxy not attached to service
,I/Telecom ( 1450): BluetoothPhoneService: Result of Message : true
,I/GLSUser ( 1702): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/HeadsetPhoneState( 2738): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 2738): Disconnected process message: 11
,D/BluetoothMapService( 2738): Received start request. Starting profile...
,D/BluetoothMapService( 2738): start()
,D/BluetoothMapService( 2738): mStartError = false
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,I/BluetoothSAPServiceJni( 2738): classInitNative(L204): succeeds
,D/HeadsetPhoneState( 2738): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 2738): Signal level : previous=0 curr=0
,D/SapService( 2738): Received start request. Starting profile...
D/SapService( 2738): start()
D/BluetoothSAPServiceJni( 2738): initializeNative(L209): sap
I/bluedroid( 2738): get_profile_interface sap
D/SapService( 2738): mStartError = false
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 2738): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 2738): Proxy object connected
D/BluetoothAdapterService( 2738): Bluetooth A2dp source service connected
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 2738): Disconnected process message: 18
D/HeadsetStateMachine( 2738): Disconnected process message: 10
D/HeadsetPhoneState( 2738): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2738): Disconnected process message: 11
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true,
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/Auth.Api.Credentials( 1870): [CredentialSyncAdapter] Unknown sync event.
,D/PicasaService( 2506): start picasa sync
,D/PicasaService( 2506): end picasa sync
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000]
D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/EnterpriseDeviceManagerService( 1016): android.intent.action.BOOT_COMPLETED
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 26
,E/Zygote  ( 2848): MountEmulatedStorage()
I/libpersona( 2848): KNOX_SDCARD checking this for 10145
,E/Zygote  ( 2848): v2
I/libpersona( 2848): KNOX_SDCARD not a persona
,I/SELinux ( 2848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 1016): runAdminUpdate
,I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2848 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/EnterpriseUtils( 1016): File Not Found : /data/system/selfUpdateAdmin.conf
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
D/EnterpriseDeviceManagerService( 1016): nothing to selfUpdate
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2848): TimaSignature is unavailable,
,D/ActivityThread( 2848): Added TimaKeyStore provider
,E/Zygote  ( 2860): MountEmulatedStorage()
I/libpersona( 2860): KNOX_SDCARD checking this for 10075
E/Zygote  ( 2860): v2
I/libpersona( 2860): KNOX_SDCARD not a persona
,I/SELinux ( 2860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=2860 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2860): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 1016): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1016): refresh widget status for user 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/,ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/PhoneRestrictionPolicy( 1016): Message received - msg { when=-2ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1016): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
I/KnoxMUMContainerPolicy( 1016): MSG_REMOVE_ORPHANED_CONTAINERS received
D/TimaKeyStoreProvider( 2860): TimaSignature is unavailable
W/PhoneRestrictionPolicy( 1016):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1016): cvList size 0
W/PhoneRestrictionPolicy( 1016):  >>>> deliveryBlockedMsgs
D/ActivityThread( 2860): Added TimaKeyStore provider
W/ResourcesManager( 2848): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
W/ResourcesManager( 2848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2848): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2848): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2848): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/WifiP2pService( 1016): InactiveState{ what=143415 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143415 }
D/WifiP2pService( 1016): DefaultState{ what=143415 }
D/ConnectivityService( 1016): Got NetworkFactory Messenger for WIFI_P2P
D/WIFI_P2P( 1016): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
W/PhoneRestrictionPolicy( 1016): cvList size 0
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ConnectivityService( 1016): Got NetworkFactory Messenger for WIFI
,E/WifiStateMachine( 1016): Blacklist file delete
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Tethering( 1016): Boot complete.,
,V/EnterpriseBillingEngine( 1016): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1016): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1016): getCurrentActiveProfiles - start - 
V/EnterpriseBillingPolicyStorage( 1016): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1016): handleAllprofiles - end
,D/UsbHostNotification( 1016): boot completed
,D/UsbHostRestrictor( 1016): mBootCompletedReceiver onReceive
,D/UsbHostRestrictor( 1016): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1016): SIM was never inserted
,D/UsbHostRestrictor( 1016): writableHostSysNode[false]
D/UsbHostRestrictor( 1016): Can NOT Write Disable Sys Node to [ON]
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,D/PersonaManagerService( 1016): ACTION_BOOT_COMPLETED
D/WIFI    ( 1016): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/PersonaManagerServiceHandler( 1016):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/UsbStorageNotification( 1016): boot completed
,D/KnoxKeyguardUpdateMonitor( 1016): onBootComplete
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1016): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1016): set_capabilities_callback: 55u
,I/libmdmdetect( 1016): ESOC framework not supported
,I/libmdmdetect( 1016): Found internal modem: modem
E/PerMgrLib( 1016): Peripheral manager is not supported on this device
,D/qmi_secgps_clnt( 1016): qmi_secgps_client_init()
,E/Geofence_Adapter( 1016): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1016): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
,D/GpsLocationProvider_ex( 1016): BOOT_COMPLETED native_cleanup 
,I/KnoxKeyguardUpdateMonitor( 1016): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1016): onTrustChanged user:0, enable:false
,I/i       ( 1016): No model
,D/KeyguardViewMediator( 1177): onTrustChanged( Showing = false , userId = 0 )
D/StorageNotification( 1177): boot completed
,D/FactoryTest( 1016): Not factory mode
D/w       ( 1016): isUserBuild = true
D/FactoryTest( 1016): Not factory mode. isFactoryMode() returend false
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/StatusBarManagerService( 1016): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/PhoneStatusBar( 1177): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 1016): SIOP:: AP = 380
,E/Zygote  ( 2890): MountEmulatedStorage()
I/libpersona( 2890): KNOX_SDCARD checking this for 10099
E/Zygote  ( 2890): v2
I/libpersona( 2890): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2890 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2890): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,D/TimaKeyStoreProvider( 2890): TimaSignature is unavailable
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/ActivityThread( 2890): Added TimaKeyStore provider
D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/SensorService( 1016): [SO] currT = 32561047000, prevT = 32121104000, diff = 439943000, [0.172 0.115 10.228]
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,E/LocSvc_utils_cfg( 1016): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1016): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1016): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1016): SECGPS: Set GNSS RF CONFIG : 1
,D/SensorService( 1016): [SO] currT = 32631121000, prevT = 32121104000, diff = 510017000, [0.172 0.115 10.228]
D/SensorService( 1016): [SO] 0.172 0.115 10.228
D/SensorService( 1016): [SO] [100 -> 255]
D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1016): SECGPS: Set CERT TYPE : 15
I/jxcore-log( 2654): getBuffer is called!!!!
I/jxcore-log( 2654): 
D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1016): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityThread( 2890): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2890): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1016): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1016): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/DrmEventReceiver( 1016): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1016): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1016): DrmEventReceiver : beginStartingService
I/System.out( 1016): start Service
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 174
D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 174
,E/Zygote  ( 2917): MountEmulatedStorage(),
E/Zygote  ( 2917): v2
I/libpersona( 2917): KNOX_SDCARD checking this for 10085
I/libpersona( 2917): KNOX_SDCARD not a persona
,I/SELinux ( 2917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2917 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2917): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 2926): MountEmulatedStorage()
E/Zygote  ( 2926): v2
I/libpersona( 2926): KNOX_SDCARD checking this for 1000
I/libpersona( 2926): KNOX_SDCARD not a persona
,I/SELinux ( 2926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 2926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DrmEventService( 1016): action event :android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/TimaServiceEventReceiver( 1016): TimaServiceEventReceiver : onReceive
,I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/TimaKeyStoreProvider( 2917): TimaSignature is unavailable
,D/ActivityThread( 2917): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2926): TimaSignature is unavailable
,D/ActivityThread( 2926): Added TimaKeyStore provider
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/CscReceiver( 1481): onReceive android.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/BluetoothAdapterState( 2738): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2738): enable
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2917): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2917): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 2917): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2917): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2917): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.,
,E/Zygote  ( 2954): MountEmulatedStorage(),
I/libpersona( 2954): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2954): v2
I/libpersona( 2954): KNOX_SDCARD not a persona
,I/SELinux ( 2954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2954 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1481): onStart
,E/CscUpdateService( 1481): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1481): set_CSC_version
,E/CscParser( 1481): update(): xml file exist
,I/bt_hci_bdroid( 2738): init
,D/TimaKeyStoreProvider( 2954): TimaSignature is unavailable
,I/bt_vendor( 2738): bt-vendor : init
I/bt_vendor( 2738): bt-vendor : get_bt_soc_type
E/bt_vendor( 2738): get_bt_soc_type: Failed to get soc type
D/ActivityThread( 2954): Added TimaKeyStore provider
I/bt_vendor( 2738): init: Local BD Address : 22:18:51:0e:f9:7c
D/bt_userial_mct( 2738): userial_init
,I/bt_vendor( 2738): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 2738): Starting hciattach daemon
,I/bt_vendor( 2738): try to set false
I/libpersona( 2972): KNOX_SDCARD checking this for 10160
E/Zygote  ( 2972): MountEmulatedStorage()
I/libpersona( 2972): KNOX_SDCARD not a persona
E/Zygote  ( 2972): v2
I/GKI_LINUX( 2738): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 2738): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 2738): Starting hciattach daemon
I/bt_vendor( 2738): try to set true
,I/SELinux ( 2972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 2972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2972 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 1189:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/qcom-bluetooth( 2980): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/art     (  302): Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 29.171ms,
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.390ms,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 18.171ms
,I/CscUtil ( 1481): isWifiOnly = false
,I/System.out( 1481): HandDataNode = null
I/CscUpdateService( 1481): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1481): This is normal boot : CSC not updated
,I/qcom-bluetooth( 2995): /system/etc/init.qcom.bt.sh: Transport : smd 
D/BadgeProvider( 1596): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_1189/cgroup.procs: No such file or directory
,E/CscParser( 1481): update(): xml file exist
,I/qcom-bluetooth( 2998): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/CscGPS  ( 1481): CSCGPS.updateParameters,
D/TimaKeyStoreProvider( 2972): TimaSignature is unavailable
D/CscGPS  ( 1481): supl host : null
D/CscGPS  ( 1481): SUPL Host is null or invalid
,D/CscGPS  ( 1481): supl_ver : null
D/CscGPS  ( 1481): SUPL Ver is null or invalid
D/CscGPS  ( 1481): supl port : null
D/CscGPS  ( 1481): SUPL PORT is null or invalid
D/CscGPS  ( 1481): LPP : null
D/CscGPS  ( 1481): LPP is null or invalid,
D/CscGPS  ( 1481): CSC don't have any AGPS value.
D/ActivityThread( 2972): Added TimaKeyStore provider
,D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false,
W/ResourcesManager( 2972): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/qcom-bluetooth( 3002): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3003): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3004): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/BadgeProvider( 1596): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 1596): sendNotify, [notify] : null
D/BadgeProvider( 1596): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1596): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1596): update, [UpdateCount] : 1
,D/Launcher.Model( 1501): reloadBadges entered.
,I/qcom-bluetooth( 3005): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 27
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
I/CscUpdateService( 1481): same CSC Version
D/CscUtil ( 1481): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,D/TP/MmsProvider( 1481): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1481): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1481): need read changed broadcast:false
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/Mms:transaction( 2381): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/Mms/MessagingNotification( 2381): [start]    nonBlockingUpdateMessageIndicator() consume time = 3644.746196
,I/Mms/ReservationManager( 2381): resetAfterConnected()
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TP/MmsSmsProvider( 1481): query,matched:7, calling pid = 2381
,D/TP/MmsSmsProvider( 1481): match 7:Elapsed time : 1.954 ms
,D/Mms/MessagingNotification( 2381): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2381): isDefault true
,I/Mms/ReservationManager( 2381): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsProvider( 1481): Query uri=content://mms, match=0, calling pid = 2381
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 2860): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 3012): MountEmulatedStorage()
,E/Zygote  ( 3012): v2
I/libpersona( 3012): KNOX_SDCARD checking this for 10048
I/libpersona( 3012): KNOX_SDCARD not a persona
,I/SELinux ( 3012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3012 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BooksApp( 2860): Created application version: 3.6.9 (30609)
,D/TP/MmsSmsProvider( 1481): query,matched:200, calling pid = 2381
,D/TP/MmsSmsProvider( 1481): match 200:Elapsed time : 3.484 ms
,D/Mms/SmsReceiverService( 2381): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3012): TimaSignature is unavailable
,D/ActivityThread( 3012): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 2381): isDefault true
D/Mms/SmsReceiverService( 2381): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2381): [start]    handleBootCompleted() consume time = 102.334375
,D/TP/MmsSmsProvider( 1481): getThreadUnReadCount unreadCount=0 imUnreadCount=0
,D/TP/MmsSmsProvider( 1481): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1481): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1481): updateThread(), thread_id = 9223372036854775806
,V/TP/MmsSmsDatabaseHelper( 1481): sUpgradeVersion = 0, db.getVersion() = 81
,W/ResourcesManager( 3012): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1481): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1481): delete threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1481): need read changed broadcast:false
,D/Mms/Conversation( 2381): deleteTempConversation(),deleted=0
,W/art     ( 2848): Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 102.167ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/SettingsProvider( 1016): name = block_emergency_message
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10048
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/ActivityManager( 1016): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,I/SecureStorage( 2954): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/qcom-bluetooth( 3035): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
,I/ActivityManager( 1016): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
E/Zygote  ( 3037): MountEmulatedStorage()
E/Zygote  ( 3037): v2
I/libpersona( 3037): KNOX_SDCARD checking this for 1000
I/libpersona( 3037): KNOX_SDCARD not a persona
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings,
,I/qcom-bluetooth( 3036): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
I/WifiCredService( 1325): onCreate
I/SELinux ( 3037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/bt_vendor( 2738): bluetooth satus is on
D/bt_userial_mct( 2738): userial_open(port:0)
I/bt_vendor( 2738): bt-vendor : BT_VND_OP_USERIAL_OPEN
,D/TimaKeyStoreProvider( 3037): TimaSignature is unavailable
,I/bt_vendor( 2738): Done intiailizing UART
,D/ActivityThread( 3037): Added TimaKeyStore provider
,I/bt_vendor( 2738): Done intiailizing UART
I/bt_userial_mct( 2738): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2738): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 2738): Entering userial_read_thread()
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 60897(3MB) AllocSpace objects, 20(344KB) LOS objects, 33% free, 26MB/39MB, paused 3.405ms total 183.158ms
,D/TP/SmsProvider( 1481): query,matched:0, calling pid = 2381
,D/TP/SmsProvider( 1481): match 0:Elapsed time : 3.672 ms
,D/SmsProvider( 1481): Update uri=content://sms/outbox, match=8
,D/TP/SmsProvider( 1481): query,matched:51, calling pid = 2381
D/TP/MmsSmsProvider( 1481): need read changed broadcast:false
,D/TP/SmsProvider( 1481): match 51:Elapsed time : 1.418 ms
,D/Mms/SmsReceiverService( 2381): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2381): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2381): [SIM-1]sendFirstQueuedMessage()
,D/WifiTimerReceiver( 1325): action: android.intent.action.BOOT_COMPLETED
,D/WifiTimerReceiver( 1325): extra: Bundle[mParcelledData.dataSize=84]
,D/MY_TAG  ( 1325): Action boot completed received
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
,E/WifiNative-wlan0( 1016): invaild command id : 215
,I/Icing   ( 1870): Storage manager: low false usage 1.79MB avail 7.89GB capacity 9.93GB
,I/SecureStorage( 2954): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  352): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2954
I/SecureStorage(  352): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 2954): [INFO]: SPID(0x00000000)SS Daemon is running
,I/SecureStorage( 2954): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  352): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2954
I/SecureStorage(  352): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,D/[0]UMC:UMCContentProvider( 2972): @onCreate
,E/SQLiteLog( 1227): (283) recovered 327 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/[0]UMC:Core( 2972): onCreate(): 
D/[0]UMC:Core( 2972): @isManagedProfileUser
D/[0]UMC:Core( 2972): userId: 0
,D/[0]UMC:Core( 2972): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2972): userInfo.isManagedProfile() : false
,W/Icing   ( 1870): Received bad json for section weights override -- ignoring.
,D/NearbySettings( 1325): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1325): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1325): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/SettingsProvider( 1016): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,D/[0]UMC:DeviceInfo( 2972): USA==US==
,D/TP/SmsProvider( 1481): query,matched:26, calling pid = 2381
D/SettingsProvider( 1016): name = next_alarm_formatted
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/        ( 2738): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 2738): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2738): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2738): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 2738): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2738): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2738): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2738): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 2738): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2738): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2738): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2738): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 2738): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2738): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2738): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2738): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2738): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/TP/SmsProvider( 1481): match 26:Elapsed time : 11.847 ms
,W/Icing   ( 1870): Received bad json for corpus context scoring override -- ignoring.
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/SQLiteLog( 3037): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,W/Icing   ( 1870): Received bad json for section weights override -- ignoring.
,I/BooksSync( 2860): Starting books sync for 61035162, extras: ade
,I/art     ( 1481): Explicit concurrent mark sweep GC freed 40296(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 985us total 180.886ms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,W/Icing   ( 1870): Received bad json for corpus context scoring override -- ignoring.
,I/NearbySettings( 1325): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1325): MountReceiver.onReceive - Internal Path
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = personal_mode_enabled
,D/Mms/SmsReceiver( 2381): unregisterForServiceStateChanges, already unregistered
,D/Mms/MessagingNotification( 2381): isBlockingModeEnabled() = false, Zen mode = 0
,D/Mms/MessagingNotification( 2381): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2381): isDefault true
,D/USER_AGENT( 2972): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/TP/MmsProvider( 1481): Query uri=content://mms, match=0, calling pid = 2381
,D/BadgeProvider( 1596): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/[0]UMC:AdminManager( 2972): init - start
,D/[0]UMC:AdminManager( 2972): loadAdmins
,W/bt-l2cap( 2738): l2c_link_processs_ble_num_bufs 16
,D/[0]UMC:AdminManager( 2972): init - end
,E/bt-btm  ( 2738): BTM_SecRegister:p_cb_info->p_le_callback == 0xa44826e9 
D/GSLBManager( 2972): migrateStoredUrlFromOldPref
E/bt-btm  ( 2738): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44826e9 
,D/TP/MmsSmsProvider( 1481): query,matched:200, calling pid = 2381
,D/TP/MmsSmsProvider( 1481): match 200:Elapsed time : 2.634 ms
,D/BluetoothAdapterProperties( 2738): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 2738):                : sec
,E/bt-btif ( 2738): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 2738): Address is:7C:F9:0E:51:18:22
,E/BluetoothServiceJni( 2738): populateRssiValuesNative
,I/bluedroid( 2738): getModelRssiValues
,E/BluetoothServiceJni( 2738): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 2738): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 2738): Name is: Thali Test (Galaxy A5)
D/SettingsProvider( 1016): name = bluetooth_name
,D/Launcher.Model( 1501): reloadBadges entered.
D/BluetoothUtils( 2738): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 2738): Scan Mode:20
D/BluetoothAdapterProperties( 2738): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2738): LE Address is:FC:F3:1C:A2:30:44
E/bt-btif ( 2738): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2738): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 2738): btif_sock_init: !radio_req && !rfc_init
D/BadgeProvider( 1596): sendNotify entered. [uri] : content://com.sec.badge/apps/2
E/bt-btif ( 2738): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2738): db_open: file /etc/bluetooth/iop_bt.db
,D/BadgeProvider( 1596): sendNotify, [notify] : null
D/BadgeProvider( 1596): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1596): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1596): update, [UpdateCount] : 1
E/bt_mct  ( 2738): hci lib postload completed
,D/IOP_DB_BT( 2738): db_open: db_open : handle 3028647952l, read 13894 bytes onto local cache
D/Mms/MessagingNotification( 2381): setBadgeCount(), count=0
D/DSM     ( 3037): [Lines:107] Normal booted
D/IOP_DB_BT( 2738): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/DSM     ( 3037): [Lines:114] Boot completed
,D/IOP_DB_BT( 2738): db_query: result 1
,D/Mms/MessagingNotification( 2381): remove alarm
I/        ( 2738): iop_db_open: iop_db_open status 0
,D/bte_conf( 2738): Device ID record 1 : primary
D/bte_conf( 2738):   vendorId            = 0075
D/bte_conf( 2738):   vendorIdSource      = 0001
D/bte_conf( 2738):   product             = 0100
D/bte_conf( 2738):   version             = 0200
D/bte_conf( 2738):   clientExecutableURL = 
D/bte_conf( 2738):   serviceDescription  = 
D/bte_conf( 2738):   documentationURL    = 
D/bte_conf( 2738): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2738): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 2738): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2738): ScanMode =  20
D/BluetoothAdapterProperties( 2738): State =  11
,D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
,W/ResourcesManager( 1481): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
D/BluetoothAdapterProperties( 2738): Setting state to 12
I/BluetoothAdapterState( 2738): Bluetooth adapter state changed: 11-> 12
,D/TP/SmsProvider( 1481): query,matched:0, calling pid = 2381
,D/TP/SmsProvider( 1481): match 0:Elapsed time : 1.764 ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1481): query,matched:0, calling pid = 2381
,D/TP/SmsProvider( 1481): match 0:Elapsed time : 4.536 ms
,E/Zygote  ( 3075): MountEmulatedStorage()
I/libpersona( 3075): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3075): v2
I/libpersona( 3075): KNOX_SDCARD not a persona
,I/SELinux ( 3075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3075 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/GSLBManager( 2972):  key : segd-api
D/GSLBManager( 2972):  value : https://eu-segd-api.secb2b.com:443/v2
,D/BluetoothUtils( 2738): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2738): Scan Mode:21
D/BluetoothAdapterProperties( 2738): Discoverable Timeout:120
,D/SettingsProvider( 1016): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/MediaScanner( 1227): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/SELinux ( 3075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 2381): updateAllHistoryAsRead()
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 2738): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2738): updateAdapterState state is 12
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2738): Autoconnection is available 
D/BluetoothAdapterService( 2738): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2738): starting service from this receiver
D/BluetoothAdapter( 1461): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1461): onBluetoothStateChange: Bluetooth is on
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 1450): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1450): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1177): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1177): onBluetoothStateChange: Bluetooth is on
,I/BluetoothAdapterState( 2738): Entering On State from state = 11
,I/SmartcardBootCompleteReceiver( 1325): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1325): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/BluetoothAdapter( 2098): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2098): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 2654): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2654): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 2738): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1016): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1016): onBluetoothStateChange: Bluetooth is on
,D/Mms/MessagingNotification( 2381): [end]    nonBlockingUpdateMessageIndicator() consume time = 575.537292
,D/BluetoothAdapter( 1678): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1678): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 1016): onBluetoothStateChange: up=true
,I/BluetoothPbapService( 2738): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothAdapter( 1481): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1481): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 2738): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2738): onBluetoothStateChange: Bluetooth is on
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1016): [BT Setting State] State =12
,I/InputMethodManagerService( 1016): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/TimaKeyStoreProvider( 3075): TimaSignature is unavailable
,D/ActivityThread( 3075): Added TimaKeyStore provider
,D/GSLBManager( 2972):  key : umc-cdn
,D/GSLBManager( 2972):  value : 
,W/ContextImpl( 1325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,I/SamsungIME( 1802): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 1450): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@39b84f26, true
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 12
,D/BluetoothHeadset( 1450): registerMessageListener
,V/MediaScanner( 1227): processDirectory :  /system/media
,I/dhcpcd  ( 2293): wlan0: sending IPv6 Router Solicitation
,I/SmartcardBootCompleteReceiver( 1325): Broadcast sent with current lockscreen type
,D/GSLBManager( 2972):  key : segp-api
D/GSLBManager( 2972):  value : 
,D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/BluetoothPbapService( 2738): Handler(): got msg=1
D/HeadsetService( 2738): registerMessageListener
,D/GSLBManager( 2972):  key : myknoxapi
D/GSLBManager( 2972):  value : 
,D/HeadsetService( 2738): registerMessageListener
,D/SecContentProvider( 1016): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/HeadsetStateMachine( 2738): Disconnected process message: 70
,D/HeadsetStateMachine( 2738): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@23fda198
,I/Telecom ( 1450): BluetoothPhoneService: handleMessage(7) / param null
,I/Telecom ( 1450): BluetoothPhoneService: updateHeadsetWithCallState
,D/GSLBManager( 2972): migrateStoredUrlFromOldPref : Finished Migrating
,D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2972): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2972): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2972): isContainer : 0
,W/art     ( 2917): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 180.726ms
,V/BluetoothPbapService( 2738): PBAP Service initSocket try: 0
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/TP/SmsProvider( 1481): query,matched:51, calling pid = 2381
W/ResourcesManager( 3075): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/BluetoothSocket( 2738): bindListen(): myUserId = 0
W/BluetoothAdapter( 2738): getBluetoothService() called with no BluetoothManagerCallback
D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2972): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2972): isContainer : 0
,D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdmin - UMC App Admin deactivated
,I/Telecom ( 1450): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1450): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
D/BluetoothSocket( 2738): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2738): bindListen(), new LocalSocket 
D/BluetoothSocket( 2738): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2738): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dca4df1
D/BluetoothSocket( 2738): channel: 19
D/BluetoothPbapService( 2738): PBAP Socket is BluetoothServerSocket
D/BluetoothMapMasInstance( 2738): set MAP SDP message type : 1
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
I/Telecom ( 1450): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2972): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/[0]UMC:CoreReceiver( 2972): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2972):  check PreETag 
,D/TP/SmsProvider( 1481): match 51:Elapsed time : 23.238 ms
,D/HeadsetStateMachine( 2738): Disconnected process message: 9
,D/HeadsetStateMachine( 2738): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothSocket( 2738): bindListen(): myUserId = 0
W/BluetoothAdapter( 2738): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 2738): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2738): bindListen(), new LocalSocket 
D/BluetoothSocket( 2738): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2738): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c48cdd6
,D/BluetoothSocket( 2738): channel: 5
,D/audio_hw_primary(  282): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  282): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,E/HeadsetStateMachine( 2738): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/[SBeam] ( 1325): SBeamEnabler.initPreferenceForSbeam : 0
,I/SettingSearch/SearchIntentReceiver( 1325): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1325): search setting db init!!
,D/Mms/MessagingNotification( 2381): isBlockingModeEnabled() = false, Zen mode = 0
,W/ContextImpl( 1325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,V/MediaScanner( 1227):  prescan time: 815ms (DB items: 141)
V/MediaScanner( 1227):     scan time: 114ms (Caching mode: true), (makeEntry time: 49ms ~42%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 929ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
,D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
,I/SettingSearch/SearchIntentReceiver( 1325): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
,E/Zygote  ( 3099): MountEmulatedStorage(),
E/Zygote  ( 3099): v2
I/libpersona( 3099): KNOX_SDCARD checking this for 1000
I/libpersona( 3099): KNOX_SDCARD not a persona
,I/SELinux ( 3099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/BadgeProvider( 1596): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/ActivityManager( 1016): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3099 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
,I/SELinux ( 3099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
,W/ActivityThread( 3075): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/MediaScannerService( 1227): !@done scanning volume internal
,D/FactoryTestApp( 2685): [DummyFtClient$mBroadcastReceiver](2685) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2685): [DummyFtClient$mBroadcastReceiver](2685) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,D/FactoryTestApp( 2685): [DummyFtClient$mBroadcastReceiver](2685) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/[0]UMC:CoreReceiver( 2972): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2972): Enter loadList
,D/[0]UMC:CoreReceiver( 2972): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2972): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2972): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2972): isContainer : 0
,D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2972): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2972): isContainer : 0
,D/[0]UMC:UMCAdmin( 2972): deactivateUMCAdmin - UMC App Admin deactivated
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/TimaKeyStoreProvider( 3099): TimaSignature is unavailable
,D/ActivityThread( 3099): Added TimaKeyStore provider
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
I/libpersona( 3115): KNOX_SDCARD checking this for 10150
E/Zygote  ( 3115): MountEmulatedStorage()
,I/libpersona( 3115): KNOX_SDCARD not a persona
E/Zygote  ( 3115): v2
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3115 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,I/SELinux ( 3115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,D/[0]UMC:ByodSetupStarter( 2972): Container ID : 0
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE,
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,I/SELinux ( 3115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3115): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/Launcher.Model( 1501): reloadBadges entered.
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
E/USB_UICC(  295): Timeout! No signal received. Retry num = 28
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 3075): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/LcdtestApp( 3075): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/BadgeProvider( 1596): sendNotify entered. [uri] : content://com.sec.badge/apps/2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1596): sendNotify, [notify] : null
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1596): update, [uri] : content://com.sec.badge/apps/2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1596): update, [BadgeCount] : badgecount=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1596): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 3115): TimaSignature is unavailable
W/ResourcesManager( 3099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 3115): Added TimaKeyStore provider
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,V/[0]UMC:Utils( 2972): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2972): shutdown
,E/Zygote  ( 3131): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3131): v2
I/libpersona( 3131): KNOX_SDCARD checking this for 1000
I/libpersona( 3131): KNOX_SDCARD not a persona
,I/SELinux ( 3131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,E/SELinux ( 3131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2972): @GuardService - stopService Result = true
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 1435:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,D/Mms/MessagingNotification( 2381): setBadgeCount(), count=0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1016): Killing 1400:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,I/art     ( 2972): System.exit called, status: 0
,I/AndroidRuntime( 2972): VM exiting with result code 0, cleanup skipped.
,D/Mms/MessagingNotification( 2381): remove alarm
,D/Mms/MessagingNotification( 2381): updateAllHistoryAsRead()
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,D/TimaKeyStoreProvider( 3131): TimaSignature is unavailable
D/ActivityThread( 3131): Added TimaKeyStore provider
,D/TP/SmsProvider( 1481): query,matched:0, calling pid = 2381
,D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/ActivityManager( 1016): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2972)(adj 0) has died(65,1065)
D/TP/SmsProvider( 1481): match 0:Elapsed time : 8.720 ms
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/SmsReceiverService( 2381): [end]    handleBootCompleted() consume time = 407.140989
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/SQLiteLog( 2860): (284) automatic index on view_volumes(volume_id)
,I/ActivityManager( 1016): Killing 1666:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1294): [MSC_Daemon]>>> ====================================================================================================================,
,D/comsamsunglog( 1294): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1294): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1294): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1294): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD,
,D/SettingsProvider( 1016): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10162
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1227):  prescan time: 89ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 15ms (Caching mode: true), (makeEntry time: 8ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 107ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,I/FOTA    ( 3099): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/MediaScannerService( 1227): !@done scanning volume external
,D/FactoryTestApp( 2685): [DummyFtClient$mBroadcastReceiver](2685) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2685): [DummyFtClient$mBroadcastReceiver](2685) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2685): [DummyFtClient$sendBootCompletedAndFinish](2685) ...
D/FactoryTestApp( 2685): [Support$Values.getString](2685) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2685): [ModuleCommon$isConnectionModeNone](2685) mConnectionMode = gsm
D/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$ResponseWriter](2685) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$connectToSecPhoneService](2685)  
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,I/BooksConfig( 2860): GmsCore Version = 7.8.99 (2134222-436)
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
I/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$onServiceConnected](2685) connected done
D/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$write](2685) Send Response Message to SecPhone
D/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$write](2685) Response ��
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_1435/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10096/pid_1400/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10138/pid_1666/cgroup.procs: No such file or directory
,I/iu.UploadsManager( 1870): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/AT_Distributor(  307): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$handleMessage](2685) Send BOOTING COMPLETED done
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1294): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1294): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449275228365
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449296820000
D/daemonapp( 1294): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1294): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1294): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449296820000
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,D/daemonapp( 1294): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1294): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449296820000
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/comdaemonstockapp( 1294): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1294): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/iu.UploadsManager( 1870): End new media; added: 0, uploading: 0, time: 106 ms
,I/DIAGMON_AGENT( 3131): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/SecureStorage(  352): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/AT_Distributor(  307): SetAtdStatus(), 1_1_0
D/AT_Distributor(  307): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,W/ContextImpl( 1943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1943): Service started flags 0 startId 1
,D/SecUISvc( 1943): Thread created.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3099): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,E/Zygote  ( 3162): MountEmulatedStorage()
I/libpersona( 3162): KNOX_SDCARD checking this for 10028
E/Zygote  ( 3162): v2
I/libpersona( 3162): KNOX_SDCARD not a persona
I/SELinux ( 3162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3162 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
E/SELinux ( 3162): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/SecureStorage( 2954): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2954): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,E/Zygote  ( 3173): MountEmulatedStorage()
I/libpersona( 3173): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3173): v2
I/libpersona( 3173): KNOX_SDCARD not a persona
I/SELinux ( 3173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3162): TimaSignature is unavailable
D/ActivityThread( 3162): Added TimaKeyStore provider
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3099): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3099): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
D/OverheatReceiver( 1177): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1177): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1177): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1177): isSafeMode = false
I/DBG_DM  ( 3099): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3099): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
D/BootupListener( 1481): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1001
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
D/PhoneUtilsCommon( 1481): isSupportVoLTE is false.
,I/DBG_DM  ( 3099): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
D/TimaKeyStoreProvider( 3173): TimaSignature is unavailable
D/ActivityThread( 3173): Added TimaKeyStore provider
,I/Telecom ( 1450): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/ResourcesManager( 3173): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3099): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/Telecom ( 1450): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ContextImpl( 3099): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3194): MountEmulatedStorage()
E/Zygote  ( 3194): v2
I/libpersona( 3194): KNOX_SDCARD checking this for 10012
I/libpersona( 3194): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/SELinux ( 3194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/DBG_DM  ( 3099): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false],
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] ,
I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(155/onStartCommand)] 
I/SELinux ( 3194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3194): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3194 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/BluetoothMediaBrowser( 2738):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,I/Telecom ( 1450): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/Telecom ( 1450): InCallController: Unbinding from InCallService unbind
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BluetoothMediaBrowser( 2738): no now playing list
D/BluetoothMediaBrowser( 2738):  getNowPlayingId now playing id : -1
,D/TimaKeyStoreProvider( 3194): TimaSignature is unavailable
,D/ActivityThread( 3194): Added TimaKeyStore provider
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3099): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3099): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3099): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,E/Zygote  ( 3210): MountEmulatedStorage()
E/Zygote  ( 3210): v2
I/libpersona( 3210): KNOX_SDCARD checking this for 10003
I/libpersona( 3210): KNOX_SDCARD not a persona
,I/SELinux ( 3210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3210 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 3210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3210): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3210): TimaSignature is unavailable
,D/ActivityThread( 3210): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 1547:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/DIAGMON_AGENT( 3131): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 3131): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 3131): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 3131): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 3131): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3131): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 14441(709KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.448ms total 220.989ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1016): No numeric data
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/audio_hw_primary(  282): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  282): audio_extn_get_parameters: returns 
V/msm8974_platform(  282): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  282): adev_get_parameters: exit: returns - call_forwarding=false
W/ResourcesManager( 3194): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3194): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/str_params(  282): key: 'call_forwarding' value: ''
,E/Tethering( 1016): No numeric data
,V/InCall  ( 1957): ProximitySensor -  - screenonImmediately: false
,V/InCall  ( 1957): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1957): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1957): serviceVersion : 16908288,
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,D/InCall  ( 1957): InCallUtils - isCoverClosed false
,I/Telecom ( 1450): ProximitySensorManager: Proximity wake lock already released,
,I/DBG_DM  ( 3099): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED,
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH,
D/InCall  ( 1957): InCallUtils - isCoverClosed false
I/InCall  ( 1957): InCallPresenter -  - InCallState = NO_CALLS,
E/Tethering( 1016): No numeric data
I/InCall  ( 1957): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1957): InCallPresenter -  - dismissCoverDialog()...
,E/Zygote  ( 3227): MountEmulatedStorage(),
E/Zygote  ( 3227): v2,
I/InCall  ( 1957): CallSContextMotion - stopPutDownListening,
D/InCall  ( 1957): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
I/libpersona( 3227): KNOX_SDCARD checking this for 10086,
I/libpersona( 3227): KNOX_SDCARD not a persona
,I/SELinux ( 3227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/Tethering( 1016): No numeric data
,D/PhoneStatusBarView( 1177): setCallBackground:0
,I/ActivityManager( 1016): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3227 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1957): InCallUtils - isCoverClosed false
,I/ActivityManager( 1016): Killing 2098:com.vlingo.midas/u0a31 (adj 15): empty #31
,E/SELinux ( 3227): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  302): Explicit concurrent mark sweep GC freed 8760(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 25.353ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.389ms
,D/TimaKeyStoreProvider( 3227): TimaSignature is unavailable
,D/ActivityThread( 3227): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 706us total 17.287ms
,E/BluetoothHeadset( 2954): BTStateChangeCB is registed
,D/BluetoothHeadset( 2954): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2954): BluetoothHeadset service is binded
I/MultiDex( 3194): VM with version 2.1.0 has multidex support
I/MultiDex( 3194): install
I/MultiDex( 3194): VM has multidex support, MultiDex support library is disabled.
,E/libprocessgroup( 1016): failed to kill 1 processes for processgroup 1547
,D/BluetoothA2dp( 2954): doBind(): CallingUid(myUserHandle) = 0
,D/VideoCallManager( 1957): Instantiating VideoCallManager
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1957): took 2.399270ms for 0*0 texture 0
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 2140:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/NotificationStore( 1702): System rebooted after Notification storage file was last written
I/NotificationStore( 1702): Deleting the file
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 29
,I/GFX generate_partition_tables( 1957): took 13.484635ms for 0*0 texture 0
,V/JNIHelp ( 3194): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GFX raster( 1957): took 22.175105ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb8f95f50 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8f95820 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1957): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1957): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1957): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1957): Local Branch: 
I/Adreno-EGL( 1957): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1957): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1957):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/Icing   ( 1870): updateResources: need to parse f{com.google.android.gms}
,I/GFX GPU raster( 1957): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1957): took 0.257552ms for 320*61440 texture 37809
,D/BluetoothA2dp( 2954): Proxy object connected
,I/draw setup( 1957): took 11.389949ms for 320*240 texture 37809
E/GFX GPU raster( 1957): drawn
,I/GFX GPU raster ASTC( 1957): took 42.726303ms for 320*240 texture 12
I/GFX raster( 1957): took 42.833022ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb8f95ed0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8f95a38 counterpartCT=4 counterpartW=320 counterparth=240
,W/ActivityThread( 3194): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3194): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8cb0bb0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3194): Installed default security provider GmsCore_OpenSSL
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1957): eglCreateImageKHR: EGL_SUCCESS
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/glCompressedTexImage2D( 1957): took 0.442812ms for 480*122880 texture 37813
I/draw setup( 1957): took 0.790520ms for 480*640 texture 37813
E/GFX GPU raster( 1957): drawn
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/GFX GPU raster ASTC( 1957): took 7.304011ms for 480*640 texture 12
I/GFX raster( 1957): took 7.389323ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb8f95a38 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb91c30e8 counterpartCT=4 counterpartW=480 counterparth=640
,E/Zygote  ( 3245): MountEmulatedStorage(),
I/libpersona( 3245): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3245): v2
I/libpersona( 3245): KNOX_SDCARD not a persona
I/SELinux ( 3245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/[SBeam] ( 1325): SBeamEnabler.isSBeamSupported : [-1]
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1957): eglCreateImageKHR: EGL_SUCCESS
,D/[SBeam] ( 1325): SBeamEnabler.isSBeamSupported : EXIST
I/glCompressedTexImage2D( 1957): took 0.397239ms for 440*116864 texture 37809
I/draw setup( 1957): took 0.798593ms for 440*330 texture 37809
E/GFX GPU raster( 1957): drawn
,I/GFX GPU raster ASTC( 1957): took 4.907345ms for 440*330 texture 12
I/GFX raster( 1957): took 4.993073ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb91c7340 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb91c7700 counterpartCT=4 counterpartW=440 counterparth=330
,E/libprocessgroup( 1016): failed to kill 1 processes for processgroup 2098
,W/libprocessgroup( 1016): failed to open /acct/uid_10050/pid_2140/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3245): TimaSignature is unavailable
,D/ActivityThread( 3245): Added TimaKeyStore provider
,I/DBG_DM  ( 3099): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/ActivityManager( 1016): Killing 2157:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3099): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1957): eglCreateImageKHR: EGL_SUCCESS,
I/glCompressedTexImage2D( 1957): took 0.462812ms for 480*163840 texture 37811
I/draw setup( 1957): took 0.824635ms for 480*640 texture 37811
E/GFX GPU raster( 1957): drawn
,I/GFX GPU raster ASTC( 1957): took 6.276824ms for 480*640 texture 12
I/GFX raster( 1957): took 6.355104ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb9206d10 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb91c2ea0 counterpartCT=4 counterpartW=480 counterparth=640
,D/UserAnalysis.PlaceProvider( 3210): PlaceProvider onCreate()
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/UpdateRequestReceiver( 3227): ignoring update request
,E/UpdateRequestReceiver( 3227): ignoring update request
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1957): took 2.198854ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1957): took 7.420209ms for 0*0 texture 0
,I/GFX raster( 1957): took 11.553959ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb91c72c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb91c0900 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/UpdateRequestReceiver( 3227): ignoring update request
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3245): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
E/UpdateRequestReceiver( 3227): ignoring update request
I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !,
,E/UpdateRequestReceiver( 3227): ignoring update request
,E/        ( 1957): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4176, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
I/GFX construct_block_size_descriptor_2d second part( 1957): took 2.394063ms for 0*0 texture 0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/UserAnalysis.SecureDbManager( 3210): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3210): SecurePlaceDbHelper() 
D/UserAnalysis( 3210): Create SecureDbHelper
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
E/UpdateRequestReceiver( 3227): ignoring update request
I/GFX generate_partition_tables( 1957): took 6.141823ms for 0*0 texture 0
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/GFX raster( 1957): took 10.650052ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1957): Bitmap=0xb91c0968 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb91c0af0 counterpartCT=4 counterpartW=176 counterparth=144
,D/PowerUI ( 1177): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1177): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/ScoverManager( 1957): registerListener
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1016): registerListenerCallback : binder = android.os.BinderProxy@3e966876, pid : 1957, uid : 1001, type : 1
W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_2157/cgroup.procs: No such file or directory
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,V/HeadsetService( 2738): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2738): Disconnected process message: 10
,E/Tethering( 1016): No numeric data
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3283): MountEmulatedStorage()
,E/Zygote  ( 3283): v2
I/libpersona( 3283): KNOX_SDCARD checking this for 10094
I/libpersona( 3283): KNOX_SDCARD not a persona
,I/SELinux ( 3283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3283 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 3283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 1516:com.android.printspooler/u0a136 (adj 15): empty #31
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
D/InCall  ( 1957): InCallPresenter -  - Finished InCallPresenter.setUp
I/DBG_POLICYDM( 3245): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/IntelligenceServiceApplication( 3210): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3210): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,W/ResourcesManager( 1177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3299): MountEmulatedStorage()
E/Zygote  ( 3299): v2
I/libpersona( 3299): KNOX_SDCARD checking this for 10060
I/libpersona( 3299): KNOX_SDCARD not a persona
,I/SELinux ( 3299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3299 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 3299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 1729:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/SELinux ( 3299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/TimaKeyStoreProvider( 3283): TimaSignature is unavailable
,D/ActivityThread( 3283): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,E/Zygote  ( 3310): MountEmulatedStorage()
E/Zygote  ( 3310): v2
I/libpersona( 3310): KNOX_SDCARD checking this for 10009
I/libpersona( 3310): KNOX_SDCARD not a persona
,I/SELinux ( 3310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3310): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3299): TimaSignature is unavailable
,D/ActivityThread( 3299): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3310 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/NotificationAccessSettings( 1325): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,D/IntelligenceServiceApplication( 3210): no applications having user consent for prediction
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : 0
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/PanelView( 1177): There is/are notification(s) 
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/Finsky  ( 3162): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1325): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3310): TimaSignature is unavailable
,D/ActivityThread( 3310): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/elm:15183( 3283): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3283): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3283): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/elm:15183( 3283): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/libprocessgroup( 1016): failed to open /acct/uid_10136/pid_1516/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_1729/cgroup.procs: No such file or directory
V/PlaceDetection v1.0.19 ( 3210): [PlaceDetection::stopService] Service stopped.
V/EmergencyMode( 1420): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
E/BooksAccountManager( 2860): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
D/elm:15183( 3283): ElmAgentService : onCreate()
D/elm:15183( 3283): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 3283): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3283): BootCompletedState : startBootCompleted() call
,D/elm:15183( 3283): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3283): Get License : 0
D/elm:15183( 3283): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 2364:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/DBG_POLICYDM( 3245): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3245): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,D/ScoverManager( 1325): serviceVersion : 16908288
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2364/cgroup.procs: No such file or directory
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 34415(1962KB) AllocSpace objects, 5(140KB) LOS objects, 25% free, 10MB/13MB, paused 1.017ms total 72.452ms
,W/SQLiteConnectionPool( 1702): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/DBG_POLICYDM( 3245): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/Icing   ( 1870): Internal init done: storage state 0
,V/PlaceDetection v1.0.19 ( 3210): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3210): Constructor Preference
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,E/BooksSync( 2860): Soft error
E/BooksSync( 2860): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2860): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 2860): Sync error
E/BooksSync( 2860): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2860): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 2860): Finished books sync
,V/EmergencyMode( 1420): [EmergencyBase] setBootTime
,V/EmergencyMode( 1420): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3344): MountEmulatedStorage()
E/Zygote  ( 3344): v2
I/libpersona( 3344): KNOX_SDCARD checking this for 1000
,I/libpersona( 3344): KNOX_SDCARD not a persona
,I/SELinux ( 3344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3344): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3344 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/ActivityManager( 1016): Killing 2403:com.sec.android.omc/1000 (adj 15): empty #31
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22822, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/sCloudBackupApp( 3299): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/TimaKeyStoreProvider( 3344): TimaSignature is unavailable
I/DBG_POLICYDM( 3245): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,D/ActivityThread( 3344): Added TimaKeyStore provider
I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 3245): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/Icing   ( 1870): Post-init done
,I/DBG_POLICYDM( 3245): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,I/DBG_POLICYDM( 3245): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 3245): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 3245): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3245): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
I/DBG_POLICYDM( 3245): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 3245): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0,
I/DBG_POLICYDM( 3245): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/08/12:48:23
I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/05/01:27:09
I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,E/Zygote  ( 3364): MountEmulatedStorage()
E/Zygote  ( 3364): v2
I/libpersona( 3364): KNOX_SDCARD checking this for 10062
I/libpersona( 3364): KNOX_SDCARD not a persona
,I/SELinux ( 3364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3364 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/SELinux ( 3364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 2411:com.sec.modem.settings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3364): TimaSignature is unavailable
,D/ActivityThread( 3364): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 30
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 3245): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2403/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2411/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3245): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/USB_UICC(  295): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  295): usb_uicc_init_qmi failed ! 
I/USB_UICC(  295): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  295): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CameraApp( 3344): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3344): Feature.Feature(context)
,I/testFeature( 3344): Feature.readInternalDefaultXml()
I/testFeature( 3344): ResetFeatureValue
,I/CameraFirmware_broadcast( 3344): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3344): CameraApp.getAppFeature()...
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3390): MountEmulatedStorage()
,E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD checking this for 10100
I/libpersona( 3390): KNOX_SDCARD not a persona
,I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3390 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Killing 2435:com.sec.tcpdumpservice/1000 (adj 15): empty #31
E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3245): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,D/Finsky  ( 3162): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,D/ActivityThread( 3390): Added TimaKeyStore provider
I/ExternalOEMControlProvider( 3364): onCreate
E/Zygote  ( 3408): MountEmulatedStorage()
E/Zygote  ( 3408): v2
I/libpersona( 3408): KNOX_SDCARD checking this for 1000
I/libpersona( 3408): KNOX_SDCARD not a persona
I/SELinux ( 3408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3408): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3408 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2531:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 1596:com.sec.android.provider.badge/u0a72 (adj 15): empty #32
I/ActivityManager( 1016): Killing 2447:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #33
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3245): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3099): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/LockPatternUtils( 1325): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 3408): TimaSignature is unavailable
,D/ActivityThread( 3408): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Settings_Utils( 1325): isSupportVNFestival SM-A500FU XEO
,E/Zygote  ( 3425): MountEmulatedStorage()
E/Zygote  ( 3425): v2
I/libpersona( 3425): KNOX_SDCARD checking this for 1000
I/libpersona( 3425): KNOX_SDCARD not a persona
,I/SELinux ( 3425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3425 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2556:com.wsomacp/u0a25 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageIntentReceiver( 3390): ACTION_BOOT_COMPLETED
,I/ActivityManager( 1016): Killing 2571:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3425): TimaSignature is unavailable
,D/ActivityThread( 3425): Added TimaKeyStore provider
,D/PackageIntentReceiver( 3390): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1016): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2435/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_1596/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3425): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/DBG_FMMDM( 3408): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/libpersona( 3446): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3446): MountEmulatedStorage()
I/libpersona( 3446): KNOX_SDCARD not a persona
E/Zygote  ( 3446): v2
I/GoogleHttpClient( 1702): GMS http client unavailable, use old client
I/SELinux ( 3446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceMode( 3425): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3425): setReferenceIsDumpState : 0
,I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3446 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/DBG_FMMDM( 3408): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3408): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/DBG_FMMDM( 3408): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3446): TimaSignature is unavailable
,D/ActivityThread( 3446): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,E/Zygote  ( 3460): MountEmulatedStorage()
E/Zygote  ( 3460): v2
I/libpersona( 3460): KNOX_SDCARD checking this for 1000
I/libpersona( 3460): KNOX_SDCARD not a persona
,I/SELinux ( 3460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3460 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
D/SettingsProvider( 1016): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/art     (  302): Explicit concurrent mark sweep GC freed 8778(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 766us total 22.982ms
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/ActivityManager( 1016): Killing 2355:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3460): TimaSignature is unavailable
,D/ActivityThread( 3460): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 18.903ms
,W/Settings( 3162): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3162): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_2447/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_2531/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_2571/cgroup.procs: No such file or directory
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.931ms
,I/DBG_POLICYDM( 3245): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,E/Zygote  ( 3478): MountEmulatedStorage()
I/libpersona( 3478): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3478): v2
I/libpersona( 3478): KNOX_SDCARD not a persona
I/SELinux ( 3478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3478 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3478): TimaSignature is unavailable
D/ActivityThread( 3478): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_2556/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2355/cgroup.procs: No such file or directory
,D/Volley  ( 3162): [376] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3162): [383] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1016): Killing 2636:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,V/GLSUser ( 1702): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_LOG( 3460): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3460): DEFAULT_LOGLEVEL : 3
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3478): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,V/GmsCoreStatsServiceLauncher( 1870): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3460): new DMDBOpenHelper instance
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3478): [] Service onCreate!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2636/cgroup.procs: No such file or directory
,E/Zygote  ( 3498): MountEmulatedStorage()
E/Zygote  ( 3498): v2
I/libpersona( 3498): KNOX_SDCARD checking this for 1000
I/libpersona( 3498): KNOX_SDCARD not a persona
I/SELinux ( 3498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PCWCLIENTTRACE_DMContentProvider( 3460): [URIMatcher] - result : 2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/NPS_WSSNPS( 3478): [50.150321] NpsServiceTask Start
,I/DBG_FMMDM( 3408): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3408): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,D/NPS_WSSNPS( 3478): [50.150321] smlDBHelper
I/DBG_FMMDM( 3408): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3498): TimaSignature is unavailable
,D/ActivityThread( 3498): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3162): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3162): [1] 2.run: Finished loading 1 libraries.
,I/NPS_WSSNPS( 3478): [50.150321] AsyncBulkFlagCheck
,E/Zygote  ( 3517): MountEmulatedStorage()
I/libpersona( 3517): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3517): v2
I/libpersona( 3517): KNOX_SDCARD not a persona
,I/SELinux ( 3517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3478): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3478): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3478): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/TimaKeyStoreProvider( 3517): TimaSignature is unavailable
,E/Zygote  ( 3531): MountEmulatedStorage()
E/Zygote  ( 3531): v2
I/libpersona( 3531): KNOX_SDCARD checking this for 1000
I/libpersona( 3531): KNOX_SDCARD not a persona
,I/SELinux ( 3531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityThread( 3517): Added TimaKeyStore provider
I/SELinux ( 3531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3531 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2667:com.android.calendar/u0a135 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3478): [50.150321] Service onDestroy
,I/NPS_WSSNPS( 3478): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRCallLogDelete
,D/Finsky  ( 3162): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/NPS_WSSNPS( 3478): [50.150321] smlBRMiniDiaryDelete
D/TimaKeyStoreProvider( 3531): TimaSignature is unavailable
I/NPS_WSSNPS( 3478): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3478): [50.150321] smlBRSMemoDelete
D/ActivityThread( 3531): Added TimaKeyStore provider
I/NPS_WSSNPS( 3478): [50.150321] cpuBooster release : false
,D/NPS_WSSNPS( 3478): [50.150321] dsServerSocket close
,D/PersistentNotificationBroadcastReceiver( 1702): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/SettingsProvider( 1016): name = access_control_enabled
,I/ActivityManager( 1016): Killing 2762:com.android.keychain/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_2667/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/KnoxSetupWizardDbHelper( 3531): dbMigrationFlag : false
,E/Zygote  ( 3552): MountEmulatedStorage()
E/Zygote  ( 3552): v2
I/libpersona( 3552): KNOX_SDCARD checking this for 10069
I/libpersona( 3552): KNOX_SDCARD not a persona
,I/SELinux ( 3552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3552 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2506:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/DBG_FMMDS( 3517): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3517): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/ShortcutReceiver( 3531):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KnoxShortcutUtil( 3531): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3531):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3531):  shortcut migration not required 
,D/TimaKeyStoreProvider( 3552): TimaSignature is unavailable
,D/ActivityThread( 3552): Added TimaKeyStore provider
,D/PCWCLIENTTRACE_DMContentProvider( 3460): [URIMatcher] - result : 2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3571): MountEmulatedStorage()
,I/libpersona( 3571): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3571): v2
I/libpersona( 3571): KNOX_SDCARD not a persona
I/SELinux ( 3571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapter( 2654): disable()
,D/SettingsProvider( 1016): name = bluetooth_on
,D/TimaKeyStoreProvider( 3571): TimaSignature is unavailable
,D/ActivityThread( 3571): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2762/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_2506/cgroup.procs: No such file or directory
,E/DBG_FMMDS( 3517): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
I/LockPatternUtils( 1325): isSmartCardAuthenticationAvailable: false
D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: false pid=2654, uid=10174
,D/SettingsProvider( 1016): name = wifi_on
,D/BluetoothAdapterState( 2738): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/Finsky  ( 3162): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/BluetoothAdapterProperties( 2738): Setting state to 13
,I/BluetoothAdapterState( 2738): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2738): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2738): updateAdapterState state is 13
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2738): Autoconnection is available 
D/BluetoothAdapterService( 2738): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2738): terminating service from this receiver
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
I/BluetoothPbapService( 2738): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothSocket( 2738): close() in, this: android.bluetooth.BluetoothSocket@33b0857, channel: 19, state: LISTENING
W/InstanceID/Rpc( 1870): Found 10012
D/BluetoothSocket( 2738): close() this: android.bluetooth.BluetoothSocket@33b0857, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dca4df1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26f73f44mSocket: android.net.LocalSocket@1f24d82d impl:android.net.LocalSocketImpl@1c5bf162 fd:FileDescriptor[74]
D/BluetoothSocket( 2738): Closing mSocket: android.net.LocalSocket@1f24d82d impl:android.net.LocalSocketImpl@1c5bf162 fd:FileDescriptor[74]
,I/ActivityManager( 1016): Killing 2890:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 2848:com.android.email/u0a145 (adj 15): empty #32
,D/BluetoothAdapterProperties( 2738): onBluetoothDisable()
D/BluetoothAdapterProperties( 2738): mDiscovering is false
,D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 2738): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothUtils( 2738): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2738): Scan Mode:20
,D/BluetoothAdapterState( 2738): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2738): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2738): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 2738): cmd socket is not created
,E/bt-btm  ( 2738): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2738): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2738): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x001b not found for deregistration
,D/btif_config_util( 2738): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/DBG_FMMDS( 3517): [50.18.150420][Line:43][xdbDBInit] 
,E/SMD     (  287): DCD OFF
,E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
I/jxcore-log( 2654): ****TEST TOOK:  5121  ms ****
I/jxcore-log( 2654): 
,I/jxcore-log( 2654): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 2654): 
I/wpa_supplicant( 2127): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2127): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2127): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2127): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =13
D/FileShare-Server( 3552): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,E/KnoxSetupWizardClient( 3571): isShipMode : 1
I/KnoxSetupWizardClient( 3571): onReceive : android.intent.action.BOOT_COMPLETED
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/BluetoothSocket( 2738): close() in, this: android.bluetooth.BluetoothSocket@8cb0bb0, channel: 5, state: LISTENING
,I/SamsungIME( 1802): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothSocket( 2738): close() this: android.bluetooth.BluetoothSocket@8cb0bb0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c48cdd6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1623ca29mSocket: android.net.LocalSocket@198bc1ae impl:android.net.LocalSocketImpl@3018ab4f fd:FileDescriptor[76]
D/BluetoothSocket( 2738): Closing mSocket: android.net.LocalSocket@198bc1ae impl:android.net.LocalSocketImpl@3018ab4f fd:FileDescriptor[76]
,D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/ServiceManager(  312): Waiting for service AtCmdFwd...
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1702): Read error: ssl=0xb9142308: I/O error during system call, Connection timed out
,W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_2848/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1702): SSL shutdown failed: ssl=0xb9142308: I/O error during system call, Broken pipe
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_2890/cgroup.procs: No such file or directory
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/qtaguid ( 1016): Tagging socket 363 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1016, getuid(): 1000
,I/qtaguid ( 1016): Untagging socket 363
D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1481): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1481): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,E/Zygote  ( 3603): MountEmulatedStorage()
I/libpersona( 3603): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3603): v2
I/libpersona( 3603): KNOX_SDCARD not a persona
,W/bt-l2cap( 2738): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_userial_mct( 2738): exiting userial_read_thread
W/bt-l2cap( 2738): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 2738): Leaving userial_evt_read_thread()
W/bt-l2cap( 2738): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2738): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2738): ag scb idx 1 not allocated
W/bt-btif ( 2738): ag scb idx 2 not allocated
E/bt-btif ( 2738): BTA AG is already disabled, ignoring ...
D/bt_userial_mct( 2738): userial_close_reader Joined userial reader thread: 0
,I/bt_vendor( 2738): hw_epilog_process
D/bt_userial_mct( 2738): userial_close
I/bt_vendor( 2738): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3603 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
I/ActivityManager( 1016): Killing 2245:flipboard.app/u0a98 (adj 15): empty #31
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/SELinux ( 3603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3603): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/WifiP2pService( 1016): InactiveState{ what=131204 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
D/WifiP2pService( 1016): P2pEnabledState{ what=131204 }
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/WifiP2pService( 1016): sending p2p connection changed broadcast: FAILED
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiScanningService( 1016): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1016): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
V/NetworkStats( 1016): updateIfacesLocked()
D/RttService( 1016): SCAN_AVAILABLE : 1
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/RttService( 1016): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1016): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 4ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1016): updateNetworkInfo()
D/WifiP2pService( 1016): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1016): onP2pDisconnected
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
,E/WifiStateMachine( 1016): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1016): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1016): disconnect
D/WifiDisplayController( 1016): updateConnection
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 1016): P2pDisablingState
,D/WifiP2pService( 1016): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1016): p2p socket connection lost
,D/WifiP2pService( 1016): P2pDisabledState
,D/WifiP2pService( 1016): P2pDisabledState{ what=143375 },
D/WifiP2pService( 1016): DefaultState{ what=143375 }
,D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1016): onP2pDisconnected
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,I/FactoryTestApp( 2685): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3157)  
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,I/DBG_DM  ( 3099): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
D/TimaKeyStoreProvider( 3603): TimaSignature is unavailable
,D/ActivityThread( 3603): Added TimaKeyStore provider
I/wpa_supplicant( 2127): p2p0: State: DISCONNECTED -> DISCONNECTED
,I/DBG_FMMDS( 3517): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 37504(2015KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 10.495ms total 228.036ms
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,I/ActivityManager( 1016): Killing 2926:com.sec.usbsettings/1000 (adj 15): empty #31
,D/SecContentProvider2( 1016): mCursor = null
,I/DBG_FMMDS( 3517): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3517): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3517): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3517): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/AndroidRuntime( 3597): 
D/AndroidRuntime( 3597): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_FMMDS( 3517): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/AndroidRuntime( 3597): CheckJNI is OFF
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_FMMDS( 3517): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AndroidRuntime( 3597): readGMSProperty: start
D/AndroidRuntime( 3597): readGMSProperty: already setted!!
D/AndroidRuntime( 3597): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3597): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3597): readGMSProperty: end
D/AndroidRuntime( 3597): addProductProperty: start
,I/bt_vendor( 2738): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2738): bluetooth satus is on
I/bt_vendor( 2738): bt-vendor : resetting BT status
I/bt_vendor( 2738): Starting hciattach daemon
I/bt_vendor( 2738): try to set false
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,W/System.err( 3571): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
I/bt_vendor( 2738): Starting hciattach daemon
I/bt_vendor( 2738): try to set false
W/System.err( 3571): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3571): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3571): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3571): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3571): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3571): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/bt_vendor( 2738): cleanup
,I/GKI_LINUX( 2738): gki_task task_id=0 [BTU] terminating
D/HotspotTile( 1177): onReceive : 0, 0
,I/GKI_LINUX( 2738): GKI_exit_task 0 done
I/GKI_LINUX( 2738): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2738): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 2738): isSecureModeOn:false
D/BluetoothAdapterService( 2738): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.gatt.GattService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
V/Finsky  ( 3162): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/BtGatt.DebugUtils( 2738): handleDebugAction() action=null
,D/BtGatt.GattService( 2738): Received stop request...Stopping profile...
,D/BtGatt.GattService( 2738): stop()
D/BtGatt.AdvertiseManager( 2738): advertise clients cleared
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/wpa_supplicant( 2127): Blacklist: Clear (all) 
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,D/HeadsetService( 2738): Received stop request...Stopping profile...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hid.HidService
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.hdp.HealthService
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 2127): p2p0: CTRL-EVENT-TERMINATING ,
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/StatusChecker( 3603): onReceive : android.intent.action.BOOT_COMPLETED
W/BluetoothAdapterService( 2738): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,I/StatusChecker( 3603): onReceive : net.mt.init : DONE
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2738): Not skipping com.broadcom.bt.service.sap.SapService
,I/ActivityManager( 1016): Killing 2381:com.android.mms/u0a46 (adj 15): empty #31
,I/wpa_supplicant( 2127): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 2127): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2127): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2127): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2127): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): InitialState.processMessage what=4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/FOTA_Client( 3310): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,E/Tethering( 1016): No numeric data
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2738): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2738): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2738): Stopping profile services that were post enabled
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 2738): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2738): Exit Disconnected: -1
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/libprocessgroup( 1016): failed to kill 1 processes for processgroup 2245
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2926/cgroup.procs: No such file or directory
,E/Zygote  ( 3635): MountEmulatedStorage()
,I/libpersona( 3635): KNOX_SDCARD checking this for 10116
E/Zygote  ( 3635): v2
I/libpersona( 3635): KNOX_SDCARD not a persona
I/SELinux ( 3635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3635 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/SELinux ( 3635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3635): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/CountryDetector( 1016): No listener is left
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 7ms
,I/ActivityManager( 1016): Killing 3012:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
E/AffinityControl( 3597): AffinityControl: registerfunction enter
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2738): Profile still running: com.android.bluetooth.hid.HidService
W/ContextImpl( 1016): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
D/BluetoothA2dp( 2954): Proxy object disconnected
D/HidService( 2738): Received stop request...Stopping profile...
D/HidService( 2738): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2738): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2738): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2738): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,D/TimaKeyStoreProvider( 3635): TimaSignature is unavailable
,D/AndroidRuntime( 3597): Calling main entry com.android.commands.pm.Pm
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityThread( 3635): Added TimaKeyStore provider
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,W/FOTA_Client( 3310): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{945966608}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
,D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1016): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1016): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3653 uid=10014 gids={50014, 9997} abi=armeabi-v7a
E/Zygote  ( 3653): MountEmulatedStorage()
I/libpersona( 3653): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3653): v2
I/libpersona( 3653): KNOX_SDCARD not a persona
I/SELinux ( 3653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Killing 3037:com.sec.dsm.system/1000 (adj 15): empty #31
I/SELinux ( 3653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3653): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 2127): Blacklist: Clear (all) 
,D/TimaKeyStoreProvider( 3653): TimaSignature is unavailable
,D/ActivityThread( 3653): Added TimaKeyStore provider
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2127): wlan0: CTRL-EVENT-TERMINATING 
W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_2381/cgroup.procs: No such file or directory
,D/FileApkUtils( 1870): Spent 34ms computing apk sha1.
,D/FileApkUtils( 1870): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1870): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/PackageSettings( 1016): Skipping PackageSetting{2040961d com.test.thalitest/10175} due to missing metadata
,D/DexOptUtils( 1870): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1870): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1870): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1870): Primary ABI of odexing process is armeabi-v7a
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 2654:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1016): Force removing ActivityRecord{289b9b4b u0 com.example.hello/.MainActivity t228}: app died, no saved state
,D/FocusedStackFrame( 1016): Set to : 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 2654
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
,I/dex2oat ( 3669): ----------------------------------------------------
I/dex2oat ( 3669): <SS>: S T A R T I N G . . .
I/dex2oat ( 3669): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3669): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=91 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3671): MountEmulatedStorage()
E/Zygote  ( 3671): v2
I/libpersona( 3671): KNOX_SDCARD checking this for 1000
I/libpersona( 3671): KNOX_SDCARD not a persona
,I/SELinux ( 3671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3671 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/BluetoothA2dp( 1016): Proxy object disconnected
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 2
,E/SELinux ( 3671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,D/Launcher( 1501): onRestart, Launcher: 800972203
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=0: pkg removed
,I/PageBuddyNotiSvc( 3635): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3671): TimaSignature is unavailable
,W/ContextImpl( 3635): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityThread( 3671): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3037/cgroup.procs: No such file or directory
,V/OneTimeInitializerReceiver( 3653): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,W/libprocessgroup( 1016): failed to open /acct/uid_10048/pid_3012/cgroup.procs: No such file or directory
,D/Launcher( 1501): onStart, Launcher: 800972203
D/Launcher.HomeView( 1501): onStart
,D/Launcher( 1501): onResume, Launcher: 800972203
,D/SettingsProvider( 1016): name = kids_home_mode
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/ContextImpl( 1325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
D/Launcher.HomeView( 1501): onResume
,D/Launcher( 1501): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/BluetoothHeadsetServiceJni( 2738): Cleaning up Bluetooth Handsfree Interface...
E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [21]
,E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
W/BluetoothHeadsetServiceJni( 2738): Cleaning up Bluetooth Handsfree callback object
,V/OneTimeService( 3653): OneTimeService.onHandleIntent
,D/HealthService( 2738): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,I/SettingSearch/SearchIntentReceiver( 1325): InitSerachDBThread thread end!
,D/MenuAppsGridFragment( 1501): onResume
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 3635): onCreate mCpBitFlag=0
,D/PanService( 2738): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,I/ActivityManager( 1016): Killing 3075:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1016): handle home activity for 0
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 1501
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1501): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Launcher( 1501): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1016): Got RemoteException sending setActive(false) notification to pid 2654 uid 10174
,W/GeofencerStateMachine( 1678): Ignoring removeGeofence because network location is disabled.
,D/SamsungIME( 1802): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/SamsungIME( 1802): mOCRHelper is null
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 1678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HotspotTile( 1177): onReceive : 1, 0
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/Timeline( 1501): Timeline: Activity_idle id: android.os.BinderProxy@238c5492 time:38128
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3099): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3698): MountEmulatedStorage()
E/Zygote  ( 3698): v2
I/libpersona( 3698): KNOX_SDCARD checking this for 10015
I/libpersona( 3698): KNOX_SDCARD not a persona
,I/SELinux ( 3698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3698): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3698 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a,
,I/art     (  302): Explicit concurrent mark sweep GC freed 8790(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 670us total 26.431ms,
,D/BluetoothMapService( 2738): Received stop request...Stopping profile...,
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/Atfwd_Sendcmd(  312): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 28.024ms
,D/TimaKeyStoreProvider( 3698): TimaSignature is unavailable
D/ActivityThread( 3698): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.001ms total 20.648ms
D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/RCPManagerService( 1016): PackageReceiver onReceive(),
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED,
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0,
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3724 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter,
,E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
,E/Zygote  ( 3724): MountEmulatedStorage(),
E/Zygote  ( 3724): v2
I/libpersona( 3724): KNOX_SDCARD checking this for 10125,
I/libpersona( 3724): KNOX_SDCARD not a persona
,I/SELinux ( 3724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Displayed Component not be shown by security: +456ms
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10174
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/ActivityManager( 1016): Killing 2917:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/RegisteredComponentCache( 1461): Collect Tech packages for Knox
,W/ResourcesManager( 1481): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,D/PanelView( 1177): There is/are notification(s) 
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 30005(2014KB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 26MB/40MB, paused 12.075ms total 357.275ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/TimaKeyStoreProvider( 3724): TimaSignature is unavailable
,D/ActivityThread( 3724): Added TimaKeyStore provider
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=228_task.xml
,D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,V/EnterpriseBillingPolicy( 1016): uID is 10174
,V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
D/PersonaManager( 1461): isKioskContainerExistOnDevice
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/GAV2    ( 2860): Thread[GAThread,5,main]: No campaign data found.
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000]
D/SensorService( 1016): [SO] activate (ident=0xb9477ef8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SapService( 2738): Received stop request...Stopping profile...
,D/SapService( 2738): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2738): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f9578f
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/PhoneApp( 1481): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/BluetoothPan( 1016): BluetoothPAN Proxy object disconnected
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,E/Zygote  ( 3747): MountEmulatedStorage()
E/Zygote  ( 3747): v2
I/libpersona( 3747): KNOX_SDCARD checking this for 1000
I/libpersona( 3747): KNOX_SDCARD not a persona
,I/SELinux ( 3747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/PackageManager( 1016): delete codoeFile: 
,D/Tethering( 1016): interfaceRemoved wlan0
E/Tethering( 1016): attempting to remove unknown iface (wlan0), ignoring
I/SELinux ( 3747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 3099): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3747 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1016): UID=10174 Target=com.example.hello
,D/PackageManager( 1016): result of delete: 1{945966608}
,W/ResourcesManager( 3724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3724): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3724): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2738): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2738): Proxy object disconnected
D/BluetoothAdapterService( 2738): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2738): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2738): GKI_exit_task 2 done
D/AndroidRuntime( 3597): Shutting down VM
,I/GKI_LINUX( 2738): GKI_shutdown(): task [A2DP-MEDIA] terminated,
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2738): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2738): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2738): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2738): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2738): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2738): Cleaning up Bluetooth PAN Interface...
D/PersonaManager( 1461): isKioskContainerExistOnDevice
W/BluetoothPanServiceJni( 2738): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2738): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2738): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(670652303)( 2738): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2738): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2738): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/RegisteredServicesCache( 1461): empty dynamic service
,D/BluetoothAdapterState( 2738): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 2738): Setting state to 10
I/BluetoothAdapterState( 2738): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2738): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2738): updateAdapterState state is 10
,D/BluetoothAdapterService( 2738): Autoconnection is available 
D/BluetoothAdapterService( 2738): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2738): Entering OffState
,D/BluetoothAdapter( 1461): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1461): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2954): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2954): Bluetooth is turned off, stop adv and scan
,D/TimaKeyStoreProvider( 3747): TimaSignature is unavailable
,D/ActivityThread( 3747): Added TimaKeyStore provider
,D/BluetoothAdapter( 1450): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1450): Bluetooth is turned off, stop adv and scan
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ResourcesManager( 3747): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/BluetoothA2dp( 2954): onBluetoothStateChange: up=false
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,D/BluetoothA2dp( 2738): onBluetoothStateChange: up=false
,I/GAv4-SVC( 1870): Google Analytics 7.8.99 is starting up.
,D/BluetoothAdapter( 1016): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1016): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1678): onBluetoothStateChange: up=false
W/TextServicesManagerService( 1016): no available spell checker services found
D/BluetoothAdapter( 1678): Bluetooth is turned off, stop adv and scan
,D/Tethering( 1016): interfaceRemoved p2p0
E/Tethering( 1016): attempting to remove unknown iface (p2p0), ignoring
,I/ApplicationPolicy( 1016): updateDataUsageMap
,D/BluetoothA2dp( 1016): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1481): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1481): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2738): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2738): Bluetooth is turned off, stop adv and scan
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,D/BluetoothAdapter( 1177): 887636924: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1177): 887636924: getState() :  mService = null. Returning STATE_OFF
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 10
,D/BluetoothAdapter( 1177): 887636924: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1177): 887636924: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 887636924: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/SamsungIME( 1802): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/QuickConnect( 3724): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3724): Util.setSCRunningSetting - [value]0
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{335d65d0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t227} time:38693
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/art     ( 3597): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/SettingsProvider( 1016): name = scon_is_running
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/GKI_LINUX( 2738): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2738): GKI_exit_task 1 done
I/GKI_LINUX( 2738): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2738): cleanupNative: return from cleanup
,I/art     ( 2738): System.exit called, status: 0
,I/AndroidRuntime( 2738): VM exiting with result code 0, cleanup skipped.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaService( 1016): TIMA: in getTimaVersion,
,E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1016): TIMA3: KeyStore3_init
I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
D/TimaService( 1016): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/Zygote  ( 3772): MountEmulatedStorage()
I/libpersona( 3772): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3772): v2
I/libpersona( 3772): KNOX_SDCARD not a persona
I/SELinux ( 3772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3772 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb9288f70, comm = 0xb950adb8, sendmsg = 0xa14c5000, recvmsg = 0xa14c5440
I/TZ_init: ( 1016): TZ_init: sending initialization request...
I/QuickConnect( 3724): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
,D/SensorService( 1016): [SO] currT = 38811085000, prevT = 38371106000, diff = 439979000, [0.153 0.115 10.228]
,D/SensorService( 1016): [SO] 0.153 0.115 10.228
D/SensorService( 1016): [SO] [100 -> 255]
,I/QuickConnect( 3724): PeriphStartReceiver.onReceive - no need to start
,I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1016): TZ_init: successful initialization
D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 9
,E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
,D/TimaKeyStoreProvider( 3772): TimaSignature is unavailable
,D/ActivityThread( 3772): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 3789): MountEmulatedStorage()
I/libpersona( 3789): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3789): v2
I/libpersona( 3789): KNOX_SDCARD not a persona
I/SELinux ( 3789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =10
I/InputMethodManagerService( 1016): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3789 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2060:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,I/SELinux ( 3789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Process com.android.bluetooth (pid 2738)(adj 0) has died(150,1095)
,D/TimaKeyStoreProvider( 3789): TimaSignature is unavailable
,D/ActivityThread( 3789): Added TimaKeyStore provider
,E/SQLiteLog( 3698): (28) failed to open "/data/data/com.google.android.partnersetup/databases/rlz_data.db" with flag (131138) and mode_t (0) due to error (30)
,W/ResourcesManager( 3789): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 3698): Failed to open database '/data/data/com.google.android.partnersetup/databases/rlz_data.db'.
E/SQLiteDatabase( 3698): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3698): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3698): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3698): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3698): 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
E/SQLiteDatabase( 3698): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/SQLiteDatabase( 3698): 	at android.content.ContentResolver.update(ContentResolver.java:1386)
E/SQLiteDatabase( 3698): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
E/SQLiteDatabase( 3698): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
E/SQLiteDatabase( 3698): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3698): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3698): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3698): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 3698): FATAL EXCEPTION: IntentService[GooglePartnerSetup]
E/AndroidRuntime( 3698): Process: com.google.android.partnersetup, PID: 3698
E/AndroidRuntime( 3698): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 3698): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 3698): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3698): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3698): 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
E/AndroidRuntime( 3698): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/AndroidRuntime( 3698): 	at android.content.ContentResolver.update(ContentResolver.java:1386)
E/AndroidRuntime( 3698): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
E/AndroidRuntime( 3698): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
E/AndroidRuntime( 3698): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3698): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3698): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 3698): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ResourcesManager( 3789): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3789): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3789): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0

```
