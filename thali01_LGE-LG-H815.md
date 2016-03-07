#### Test 6170335106d974e_thali01_LGE-LG-H815 Logs


```
--------- beginning of main
D/MtpService( 5873): addStorageLocked 65537 /storage/emulated/0
I/[SystemUI]QSlideListController( 3398): setLowProfile : false from com.lge.camera
E/MtpStorageEx( 5873): setAccessCapability false
D/MtpServerEx( 5873): ANR FIX - addStorage!
D/LGMtpServerJNI( 5873): android_mtp_LGMtpServer_run
D/BluetoothAdapterService(221810696)( 4484): onBind()
V/DownloadManager( 5873): Received broadcast intent for android.intent.action.BOOT_COMPLETED
V/WfdStateTracker( 4057): Camera Event: 1, -1
D/LGInCallFloatingReceiver( 4118): received action : [com.lge.camera.action.STOP_CAMERA_APP], UserId = 0
D/LGInCallFloatingReceiver( 4118): startCallFloatingService command =SHOW_IN_CALL_BUBBLE, UserId = 0
D/MediaScannerService( 5873): [MediaScanner] done scanning volume internal
D/BluetoothManagerService( 1280): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1280): Message: 40
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
V/DownloadManager( 5873): DownloadService onCreate
D/MediaScannerService( 5873): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
I/NotificationManager( 5873): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/MusicBrowser( 4588): [MediaPlaybackService.java:3256:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
V/LGMediaProvider( 5873): insertInternal: content://media/none/media_scanner, initValues=volume=external
I/MusicBrowser( 4588): [MediaPlaybackService.java:3274:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 4588): [MusicUtils.java:9479:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/LGInCallFloatingBridgeService( 4118): onStartCommand() is called
I/bluedroid( 4484): config_hci_snoop_log
D/BluetoothManagerService( 1280): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1280): Broadcasting onBluetoothServiceUp() to 8 receivers.
I/LIA_S4URecommender_LogCore( 7293): LIA Log Open() - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_LogTracer( 7293): [Log Tracer - Service State Transition] onCreate()...... 
D/MediaScannerService( 5873): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
--------- beginning of system
V/LGMDMManagerInternal( 4484): Create singleton instance
,I/ActivityManager( 1280): Start proc 7339:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
I/[LGHome]EVENT( 4311): onResume
D/InputDispatcher( 1280): Focus entered window: Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothAdapterService(221810696)( 4484): enable() - Enable called with quiet mode status =  false
D/BluetoothAdapterState( 4484): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4484): Setting state to 11
I/BluetoothAdapterState( 4484): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(221810696)( 4484): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothAdapterService(221810696)( 4484): processStart()
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BluetoothManagerService( 1280): Message: 60
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1280): Bluetooth State Change Intent: 10 -> 11
V/DownloadManager( 5873): DownloadService onStartCommand
D/LGMediaProvider( 5873): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
V/LGMediaProvider( 5873): insertInternal: content://media/, initValues=name=external
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/MusicWidget( 5805): _mediaDataObserver onChange()
D/SplitWindowPolicy( 4057): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 4057): topRunningActivity=ActivityInfo{10cadbe9 co.....Launcher}, taskId=51, activityType=1, bIsSplit=false
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/MusicWidget( 5805): getFavoriteValue()
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/ActivityManager( 1280): Killing 6748:com.qualcomm.timeservice/1000 (adj 15): empty #22
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.pan.PanService
V/DownloadManager( 5873): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@37653677 on behalf of 5873
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
I/LIA_S4URecommender_LIARemoteService( 7293): [LIA Remote Service Info] ------------------------
W/BluetoothAdapterService( 4484): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): processStart() - Make Bond State Machine
I/LIA_S4URecommender_LIARemoteService( 7293):  - UID : 10031
I/LIA_S4URecommender_LIARemoteService( 7293):  - LIA Core Version Name : 0.8.24
I/LIA_S4URecommender_LIARemoteService( 7293):  - LIA Core Release Date : 2014.12.16
I/LIA_S4URecommender_LIARemoteService( 7293):  - LIA S4URecommender Task Version Name : 4.22.15
I/LIA_S4URecommender_LIARemoteService( 7293):  - LIA Service Version Name : 0.8.20.2
I/LIA_S4URecommender_LIARemoteService( 7293): --------------------------------------------------
D/LIA_S4URecommender_LIARemoteService( 7293): onCreate()
D/BluetoothBondStateMachine( 4484): make
I/LIA_S4URecommender_S4URecommenderService( 7293): getTaskPropertiesAtFirstStarting()
I/LIA_S4URecommender_S4URecommenderService( 7293): isNowInActivationCondition()
D/MediaScannerEx( 5873): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 5873): [MediaScanner] scanDirectories()[1] = /storage/external_SD
D/BluetoothAdapterService( 4484): setAdapterService() - set to: null
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/LGBluetoothServiceAdapter( 4484): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 4484): StableState(): Entering Off State
I/LIA_S4URecommender_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_S4URecommender_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
W/PeerForAndroidWear( 4141): onConnectionFailed: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/PeerInterfaceDuplicator( 4141): all Peer implementations have failed to activate.
D/PeerForWman( 4141): isActivated() return false: mIsActivated=false, mPeerContext=null
D/PeerForWman( 4141): sendMessage() message=Bundle[{remote-shutter=finish-activity}]
D/PeerForWman( 4141): isActivated() return false: mIsActivated=false, mPeerContext=null
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
V/MediaScannerClient( 5873): [MediaScanner]setLocale: = en_GB
I/LGDrmClient( 5873): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  472): eDRM_IsSupportedExtension +++
V/ILGDrmService(  472): eDRM_IsSupportedExtension ---
D/LGInCallFloatingBridgeService( 4118): received MSG_REQUEST_SHOW_IN_CALL_BUBBLE, UserId = 0
D/InCallFloatingView( 4118): requestShowInCallBubble() called...
V/ILGDrmService(  472): eDRM_IsDRMByHnd +++
D/LGDRM   (  472): [DRM]drmUtilCmpPreloadID start : DRM_PRELOAD_CODEC
D/LGDRM   (  472): [DRM]drmUtilCmpPreloadID end : DRM_PRELOAD_CODEC
V/ILGDrmService(  472): eDRM_IsDRMByHnd ---#2
V/ILGDrmService(  472): eDRM_IsDRMByHnd +++
V/ILGDrmService(  472): eDRM_IsDRMByHnd ---#2
V/ILGDrmService(  472): eDRM_ContentInfoByHnd +++
V/ILGDrmService(  472): eDRM_ContentInfoByHnd ---#2
I/MSM-irqbalance(  680): Decided to move IRQ215 from CPU0 to CPU3
D/MediaScannerEx( 5873): [MediaScanner] beginFile() path = /storage/emulated/0/Quickset Setup/data
V/MediaScannerClient( 5873): [MediaScanner]setLocale: = en_GB
W/MediaScanner( 5873): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 5873): [MediaScanner] delete() uri = content://media/external/file
D/LGMediaProvider( 5873): [MediaScanner] delete() completed notifyChange, uri = content://media/external
V/MediaScanner( 5873): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3baa2e4
V/MediaScanner( 5873): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3baa2e4
D/MediaScanner( 5873): [MediaScanner] prescan time: 32ms
D/MediaScanner( 5873): [MediaScanner] scan time: 51ms
D/MediaScanner( 5873): [MediaScanner] postscan time: 5ms
D/MediaScanner( 5873): [MediaScanner] total time: 88ms
D/LGMediaProvider( 5873): [MediaScanner] delete() uri = content://media/none/media_scanner
D/MediaScannerService( 5873): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
D/AndroidRuntime( 7364): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 7364): CheckJNI is OFF
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/[LGHome]LGActivityUtil( 4311): [LGActivityUtil.java:204:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/PhoneUtils( 4118): [Call Alerting] getTopActivity() : com.lge.launcher2.Launcher
D/PhoneUtils( 4118): getInCallActivityName: com.android.incallui.InCallActivity
D/InCallFloatingView( 4118): onResume() called...
D/InCallFloatingView( 4118): existsCallConnection() called...
D/InCallFloatingView( 4118): isCallStateOffHook called
D/LGBluetoothAPIService( 4057): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BleQmManagerService( 4057): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
I/[LGHome]EVENT( 4311): onResume end
I/Activity( 4311): Activity.onPostResume() called 
D/PowerService( 4057): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 4057): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 4057): Battery Level Remaining: 100%
D/LEDHandler( 4057): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
V/DownloadManager( 5873): DownloadService onDestroy
D/LGMediaProvider( 5873): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
D/MediaScannerService( 5873): [MediaScanner] done scanning volume external
D/WifiController( 1280): battery changed pluggedType: 2
D/HeadsetService( 4484): Received start request. Starting profile...
D/LGBluetoothFeatureConfig( 4484): isPrivacyLogsEnabled : true
I/LGBluetoothHeadsetServiceJni( 4484): classInitNative: succeeds
D/LGDMClient( 7175): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 7175): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[LGHome]EVENT( 4311): [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/[LGHome]EVENT( 4311): [Launcher.java:5476:setEnableShakeHandlers()]enableShakeHandlers
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/[Concierge][ConciergeWidgetLayout]( 4311): notifyExtViewAvailable
D/PowerService( 4057): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
I/LIA_S4URecommender_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_S4URecommender_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_S4URecommender_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 3398): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
I/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/LGBluetoothFeatureConfig( 4484): isPrivacyLogsEnabled : true
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/BluetoothHeadsetServiceJni( 4484): classInitNative: succeeds
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/HeadsetStateMachine( 4484): make
W/InputMethodManagerService( 1280): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@7b13fa4 attribute=null, token = android.os.BinderProxy@29a1c463
D/MusicBrowser( 4588): [MediaPlaybackService.java:3514:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 4588): [MediaPlaybackService.java:3516:notifyChange()] oooooo 
D/MusicBrowser( 4588): [MediaPlaybackService.java:3546:notifyChange()] oooooo id : 0
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
I/MusicWidgetView4x2( 5805): getFavorite cursor null
D/InCallFloatingView( 4118): HJY mTelephonyManager.isOffhook() : false
D/MusicBrowser( 4588): [MediaPlaybackService.java:3547:notifyChange()] oooooo artist : null
I/MusicWidget( 5805): isNeedUpdateByDBChange() result::false
I/MusicWidget( 5805): _mediaDataObserver onChange()
D/MusicBrowser( 4588): [MediaPlaybackService.java:3548:notifyChange()] oooooo album : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3549:notifyChange()] oooooo track : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3550:notifyChange()] oooooo playing : false
D/MusicBrowser( 4588): [MediaPlaybackService.java:3551:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3552:notifyChange()] oooooo position() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3553:notifyChange()] oooooo ListSize : 0
I/LIA_S4URecommender_MrGServiceBase( 7293): Version Update Check : CASE2 - This is not the first task launching after installing the first version APK or updated version APK
I/LIA_S4URecommender_LIARemoteService( 7293): checkTaskInitialization() : needResetTaskPropertyInSharedPreference() is false, so maintain SharedPreference
D/LIA_S4URecommender_LIARemoteService( 7293): getTaskPreparation()
I/LIA_S4URecommender_S4URecommenderService( 7293): getTaskPropertiesAtFirstStarting()
I/LIA_S4URecommender_S4URecommenderService( 7293): isNowInActivationCondition()
D/LGSubScriptionUtilsWrapper_MR1( 4118): getSubIdUsingSlotId() slotId:0 -> subId:2147483643
D/InCallFloatingView( 4118): HJY mTelephonyManager.isRinging() : false
D/InCallFloatingView( 4118): hide() called...
D/InCallFloatingView( 4118): onRemove() called...
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
I/LIA_S4URecommender_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_S4URecommender_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/MusicWidget( 5805): getFavoriteValue()
I/MusicBrowser( 4588): [MediaPlaybackService.java:2140:saveQueue()] oooooo {full=true}
I/MusicBrowser( 4588): [MediaPlaybackService.java:2145:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/Timeline( 4311): Timeline: Activity_idle id: android.os.BinderProxy@2c54b562 time:41266
D/MusicBrowser( 4588): [MediaPlaybackService.java:2225:saveQueue()] oooooo {queue=}
D/MusicBrowser( 4588): [MediaPlaybackService.java:2227:saveQueue()] oooooo {mCardId=-1}
D/HeadsetStateMachine( 4484): max_hf_connections = 2
I/bluedroid( 4484): get_profile_interface handsfree
I/bt-btif ( 4484): btif_hf_get_interface
I/bt-btif ( 4484): init
D/bt-btif ( 4484): max_hf_clients = 2
D/bt-btif ( 4484): btif_max_hf_clients = 2
D/bt-btif ( 4484): btif_enable_service: current services:0xdde7e348
D/MusicBrowser( 4588): [MediaPlaybackService.java:2272:saveQueue()] oooooo {curpos=-1}
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/MusicBrowser( 4588): [MediaPlaybackService.java:3514:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 4588): [MediaPlaybackService.java:3516:notifyChange()] oooooo 
D/MusicBrowser( 4588): [MediaPlaybackService.java:3546:notifyChange()] oooooo id : 0
D/MusicBrowser( 4588): [MediaPlaybackService.java:3547:notifyChange()] oooooo artist : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3548:notifyChange()] oooooo album : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3549:notifyChange()] oooooo track : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3550:notifyChange()] oooooo playing : false
D/MusicBrowser( 4588): [MediaPlaybackService.java:3551:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3552:notifyChange()] oooooo position() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3553:notifyChange()] oooooo ListSize : 0
I/LIA_S4URecommender_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_S4URecommender_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_S4URecommender_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LIA_S4URecommender_LIARemoteService( 7293): updateTaskProperties()
D/LIA_S4URecommender_LIARemoteService( 7293): --> Getting task property of activation from Shared preferences ...
D/LIA_S4URecommender_LIARemoteService( 7293): --> Task property for activation for S4URecommender is true
D/LIA_S4URecommender_LIARemoteService( 7293): --> Getting activation properties done!
D/KeyguardUpdateMonitor( 3398): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
D/LIA_S4URecommender_LIARemoteManager( 7293): init()
I/MusicBrowser( 4588): [MediaPlaybackService.java:3565:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 4588): [MediaPlaybackService.java:2140:saveQueue()] oooooo {full=false}
I/MusicBrowser( 4588): [MediaPlaybackService.java:2145:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/LIA_S4URecommender_LIARemoteService( 7293): prepare() : Tasks are registering ...
D/LIA_S4URecommender_LIARemoteService( 7293): --> Task name : S4URecommender
I/[SystemUI]LGPowerUI( 3398): onReceive = android.intent.action.BATTERY_CHANGED
V/ToneGenerator( 4484): ToneGenerator constructor: streamType=8, volume=1.000000
I/[SystemUI]LGPowerUI( 3398): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LIA_S4URecommender_TaskLauncher( 7293): register() - main launcher : false
D/LIA_S4URecommender_LIARemoteService( 7293): prepare() : Tasks have been registered.
I/LIA_S4URecommender_LogCore( 7293): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
D/LIA_S4URecommender_LIARemoteService( 7293): onBind()
D/LIA_S4URecommender_LIARemoteManager( 7293): getBinder()
V/AudioPolicyService(  466): registerClient() client 0xf21553a0, uid 1002
I/[SystemUI]BatterySaverHandler( 3398): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3398): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 3398): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 3398): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3398): On Skip Timer : true
D/KeyguardUpdateMonitor( 3398): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 3398): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 3398): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3398): On Skip Timer : true
V/AudioPolicyManager(  466): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  466): getOutput() returns output 2
V/AudioFlinger(  466): registerClient() client 0xf1c33118, pid 4484
V/AudioFlinger(  466): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  466): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  466): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  466): thread 0xf5fab000 type 0 TID 3230 waking up
V/AudioFlinger(  466): thread 0xf2047000 type 0 TID 3231 waking up
V/AudioFlinger(  466): thread 0xf2091000 type 0 TID 3233 waking up
V/AudioSystem( 4484): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  466): processConfigEvents_l() remaining events 1
V/AudioFlinger(  466): PlaybackThread::audioConfigChanged, thread 0xf2091000, event 0, param 0
V/audio_hw_primary(  466): out_get_latency: Latency 64
V/AudioSystem(  466): ioConfigChanged() opening already existing output! 6
I/MusicBrowser( 4588): [MediaPlaybackService.java:10362:run()] oooooo AlbumImageUpdater() run :: Start
V/AudioSystem( 1280): ioConfigChanged() opening already existing output! 6
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
V/ToneGenerator( 4484): Create Track: 0xf491ec00
V/AudioTrack( 4484): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/LocationManagerService( 1280): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1280): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1280): JNI:system_update. Event-4
I/MusicBrowser( 4588): [MediaPlaybackService.java:10428:run()] oooooo AlbumImageUpdater() run :: End
V/AudioSystem( 3398): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 4588): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  466): processConfigEvents_l() DONE thread 0xf2091000
V/AudioSystem( 4118): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 4484): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioFlinger(  466): processConfigEvents_l() remaining events 1
V/AudioFlinger(  466): PlaybackThread::audioConfigChanged, thread 0xf5fab000, event 0, param 0
V/audio_hw_primary(  466): out_get_latency: Latency 10
V/AudioSystem(  466): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1280): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  466): processConfigEvents_l() DONE thread 0xf5fab000
V/AudioSystem( 3398): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  466): processConfigEvents_l() remaining events 1
V/AudioFlinger(  466): PlaybackThread::audioConfigChanged, thread 0xf2047000, event 0, param 0
V/audio_hw_primary(  466): out_get_latency: Latency 100
V/AudioSystem(  466): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 4484): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioFlinger(  466): processConfigEvents_l() DONE thread 0xf2047000
V/AudioSystem( 3398): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1280): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 4484): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 100
V/AudioSystem( 4118): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 4118): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 4588): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 4588): ioConfigChanged() opening already existing output! 4
D/AudioTrack( 4484): createTrack_l()... isAudioHookOn = 0, mStreamType = 8
D/AudioTrack( 4484): TrackOffload: AudioTrack Offload disabled by property, returning false
D/LIA_Service_RemoteProxy( 4268): onServiceConnected() : com.lge.ia.task.s4urecommender
V/AudioPolicyManager(  466): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  466): getOutputForAttr() device 0x2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  466): getOutput() returns output 2
V/AudioSystem( 4484): getLatency() output 2, latency 50
V/AudioSystem( 4484): getFrameCount() output 2, frameCount 960
V/AudioTrack( 4484): createTrack_l() output 2 afLatency 50
V/AudioTrack( 4484): Create normal PCM 0x1 Track
D/LIA_S4URecommender_LIARemoteService( 7293): onStartCommand() : LIARemoteService started! - (Id :1), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
V/AudioFlinger(  466): createTrack() lSessionId: 18
V/AudioFlinger(  466): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  466): sendConfigEvent_l() num events 1 event 1
D/LIA_S4URecommender_LIARemoteManager( 7293): getProperties()
D/LIA_S4URecommender_TaskLauncher( 7293): getTaskPropertyList() - main launcher : false
D/LocationManagerService( 1280): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1280): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1280): JNI:system_update. Event-4
I/MusicWidgetView4x2( 5805): getFavorite cursor null
V/AudioFlinger(  466): processConfigEvents_l() remaining events 1
V/AudioFlinger(  466): processConfigEvents_l() DONE thread 0xf5fab000
V/AudioTrack( 4484): Flags here  0x4 
V/AudioTrack( 4484): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/LIA_Service_RemoteProxy( 4268): onServiceConnected() : Task Property for S4URecommender - Activation:true, AutoExecution:true
D/MusicBrowser( 4588): [MediaPlaybackService.java:2272:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 4588): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 4588): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
V/AudioFlinger(  466): acquiring 18 from 4484, for 4484
V/AudioFlinger(  466):  added new entry for 18
V/ToneGenerator( 4484): ToneGenerator INIT OK, time: 41301
I/MusicBrowser( 4588): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 4588): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicWidget( 5805): isNeedUpdateByDBChange() result::false
I/MusicWidget( 5805): intentReceiver onReceive() action::com.lge.music.queuechanged
D/LIA_Service_RemoteSessionManager( 4268): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 4268): Added task & RemoteProxy: S4URecommender, com.lge.ia.manager.remote.RemoteProxy@105857fa
V/LIA_Service_RemoteSessionManager( 4268): Trying to register task(s) to LIACore ...
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/LIA_Service_TaskLauncher( 4268): register() - main launcher : true
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/LIA_Service_TaskLauncher( 4268): --> S4URecommender is registered on LIACores
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/LIA_Service_TaskLauncher( 4268): --> S4URecommender is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4268): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4268): runTask() : S4URecommender
D/LIA_Service_RemoteProxy( 4268): runTask() : Task name & RemoteProxy - S4URecommender, com.lge.ia.manager.remote.RemoteProxy@105857fa
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/LIA_Service_LogTracer( 4268): [Log Tracer - Task State Transition] runTask(S4URecommender)...... 
D/LIA_S4URecommender_LIARemoteManager( 7293): runTask() : S4URecommender
D/LIA_S4URecommender_TaskLauncher( 7293): runTask - main launcher : false
V/LIA_S4URecommender_TaskContext( 7293): runSession() : S4URecommender
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
D/LIA_S4URecommender_LIARemoteService( 7293): getTask()
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/LIA_S4URecommender_TaskSession( 7293): TaskSession.of() - thread id : 264, thread name : Binder_1
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
I/MusicBrowser( 4588): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 4484): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
V/BluetoothPbapReceiver( 4484): PbapReceiver onReceive 
D/HeadsetStateMachine( 4484): Enter Disconnected: -2, size: 0
V/BluetoothPbapReceiver( 4484): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/HeadsetPhoneState( 4484): [BTUI] listenForPhoneState : start = false
V/BluetoothPbapReceiver( 4484): ***********state = 11
D/LGBluetoothHfpManager( 4484): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 4484): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  466): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4484
V/SRS_Proc(  466): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  466): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  466): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: exit
V/voice   (  466): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  466): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  466): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  466): platform_set_parameters: exit with code(0)
V/platform_param(  466): lge_platform_factory_set_parameters: enter: bt_samplerate=8000
D/audio_hw_extn(  466): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  466): adev_set_parameters: exit with code(0)
I/MusicWidget( 5805): send mDelayedStopHandler
I/MusicWidget( 5805): intentReceiver onReceive() action::com.lge.music.metachanged
W/MusicBrowser( 4588): - Start trace [MusicUtils.query]---------------------------------------------------------------
V/ToneGenerator( 4484): ToneGenerator destructor
V/ToneGenerator( 4484): stopTone
V/ToneGenerator( 4484): Delete Track: 0xf491ec00
V/AudioTrack( 4484): ~AudioTrack, releasing session id from 4484 on behalf of 4484
V/AudioFlinger(  466): remove track (4097) and delete from mixer
V/AudioFlinger(  466): releasing 18 from 4484 for 4484
V/AudioFlinger(  466):  decremented refcount to 0
V/AudioFlinger(  466): purging stale effects
V/AudioPolicyService(  466): AudioCommandThread() adding release output 2
V/AudioPolicyService(  466): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  466): PlaybackThread::Track destructor
V/AudioFlinger(  466): removeClient_l() pid 4484, calling pid 466
V/AudioPolicyService(  466): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  466): releaseOutput() 2
W/MusicBrowser( 4588): [Line 003776] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 4588): [Line 003786] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 4588): [Line 001971] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 4588): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 4588): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
I/LIA_S4URecommender_LogTracer( 7293): [Log Tracer - Task State Transition] create(S4URecommender)...... Request
I/MusicBrowser( 4588): [MediaPlaybackService.java:1975:onChange()] oooooo 
I/MusicWidget( 5805): send mDelayedStopHandler
I/LIA_Informant_LogCore( 7293): LIA Log Open() - prefix : LIA_Informant_
I/MusicBrowser( 4588): [MusicWearUtils.java:64:isWearSyncEnabled()] oooooo isWearSyncEnabled() = false
W/MusicBrowser( 4588): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 4588): [Line 003776] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 4588): [Line 003786] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 4588): [Line 001971] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 4588): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 4588): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Service State Transition] onCreate()...... 
D/LIA_S4URecommender_AsyncChannel( 7293): Send Order (17)
D/LIA_S4URecommender_S4URecommenderTask( 7293): registerRunBatchStarterAlarm entered
W/LIA_S4URecommender_S4URecommenderTask( 7293): unregisterRunBatchStarterAlarm
D/LIA_S4URecommender_AndroidDBHelper( 7293): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_S4URecommenderTask( 7293): registerRunBatch start alarm time : Tue Mar 08 00:00:00 CET 2016
D/LIA_S4URecommender_AndroidDBHelper( 7293): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_AndroidDBHelper( 7293): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_AsyncChannel( 7293): Receive Order (17)
D/LIA_S4URecommender_S4URecommenderTask( 7293): Prepare Done Callback ~~~ !!!!!!!!!!!
I/ActivityManager( 1280): Start proc 7390:com.android.settings/1000 for broadcast com.lge.bluetoothsetting/.DockEventReceiver
D/BluetoothA2dp( 4684): Proxy object connected
D/BluetoothA2dp( 1280): Proxy object connected
V/SoundPool( 4141): Sample::destructor sampleID=2, fd=-1
V/SoundPool( 4141): SoundPool destructor
V/SoundPool( 4141): awake
V/SoundPool( 4141): goodbye
D/LIA_S4URecommender_CommunicationRankCallLogCollector( 7293): CommunicationRankCallLogCollector Creator
D/LIA_S4URecommender_S4URecommenderTask( 7293): registerListener
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
V/SoundPool( 4141): return from quit
V/SoundPool( 4141): SoundChannel destructor 0xeec4f41c
V/SoundPool( 4141): SoundChannel destructor 0xeec4f3c0
V/SoundPool( 4141): SoundChannel destructor 0xeec4f364
V/SoundPool( 4141): SoundChannel destructor 0xeec4f308
V/SoundPool( 4141): clear samples
V/SoundPool( 4141): Sample::destructor sampleID=1, fd=-1
V/SoundPool( 4141): SoundPool destructor
V/SoundPool( 4141): awake
V/SoundPool( 4141): goodbye
V/SoundPool( 4141): return from quit
V/SoundPool( 4141): SoundChannel destructor 0xeec4f71c
V/SoundPool( 4141): SoundChannel destructor 0xeec4f6c0
V/SoundPool( 4141): SoundChannel destructor 0xeec4f664
V/SoundPool( 4141): SoundChannel destructor 0xeec4f608
V/SoundPool( 4141): clear samples
V/SoundPool( 4141): SoundPool destructor
V/SoundPool( 4141): awake
V/SoundPool( 4141): goodbye
V/SoundPool( 4141): return from quit
V/SoundPool( 4141): SoundChannel destructor 0xeec464e4
V/SoundPool( 4141): SoundChannel destructor 0xeec46488
V/SoundPool( 4141): clear samples
I/MusicWidget( 5805): performViewUpdater handleMessage() msg.what::0
I/LIA_S4URecommender_LogTracer( 7293): [Log Tracer - Task State Transition] create(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 7293): S4URecommender task is created !!
I/LIA_S4URecommender_TaskSession( 7293): S4URecommender create() process time = 39 msec
D/LIA_S4URecommender_TaskSession( 7293): enable() - enable state : false, thread id : 264, thread name : Binder_1
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
I/LIA_S4URecommender_LogTracer( 7293): [Log Tracer - Task State Transition] start(S4URecommender)...... Request
D/A2dpService( 4484): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 4484): classInitNative: succeeds
V/Avrcp   ( 4484): make
D/Avrcp   ( 4484): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 4484): get_profile_interface avrcp
I/bt-btif ( 4484): btif_rc_get_interface
I/bt-btif ( 4484): ## init ##
V/SoundPool( 4141): SoundPool constructor: maxChannels=4, attr.usage=13, attr.flags=0x1, attr.tags=
I/LGBluetoothAvrcpServiceJni( 4484): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 4484): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 4484): initNative: succeeds
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 4484): Not skipping com.broadcom.bt.service.opp.OppService
I/BluetoothAvrcpBrcmAdapterJni( 4484): classInitBrcmNative
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
I/BluetoothAvrcpBrcmAdapterJni( 4484): initBrcmNative
V/LGMDMManager( 4484): Create singleton instance
I/LIA_S4URecommender_TaskSession( 7293): S4URecommender start() result: true, process time = 0 msec
I/LIA_S4URecommender_LogTracer( 7293): [Log Tracer - Task State Transition] start(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 7293): enable() - enable state : true
D/LIA_S4URecommender_TaskContext( 7293): runSeesion() succeeded.
D/LIA_S4URecommender_TaskLauncher( 7293): runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap Size : 1
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.s4urecommender [key: S4URecommender]
V/SoundPool( 4141): SoundPool constructor: maxChannels=4, attr.usage=1, attr.flags=0x0, attr.tags=
I/MusicBrowser( 4588): [MediaPlaybackService.java:1975:onChange()] oooooo 
I/MusicBrowser( 4588): [MusicWearUtils.java:64:isWearSyncEnabled()] oooooo isWearSyncEnabled() = false
I/MusicBrowser( 4588): [MediaPlaybackService.java:3256:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 4588): [MediaPlaybackService.java:3274:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 4588): [MusicUtils.java:9479:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/LGNetworkSettings( 4118): onCreate: 
I/MusicBrowser( 4588): [MediaPlaybackService.java:3256:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
V/SoundPool( 4141): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
I/BluetoothAdapterState( 4484): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/MusicBrowser( 4588): [MediaPlaybackService.java:3274:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 4588): [MusicUtils.java:9479:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/AndroidRuntime( 7364): Calling main entry com.android.commands.am.Am
D/ActionManager( 7293): connecting to ActionManagerService...
I/ActivityManager( 1280): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 4588): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 4588): [MediaPlaybackService.java:3514:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 4588): [MediaPlaybackService.java:3516:notifyChange()] oooooo 
D/MusicBrowser( 4588): [MediaPlaybackService.java:3546:notifyChange()] oooooo id : 0
D/MusicBrowser( 4588): [MediaPlaybackService.java:3547:notifyChange()] oooooo artist : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3548:notifyChange()] oooooo album : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3549:notifyChange()] oooooo track : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3550:notifyChange()] oooooo playing : false
D/MusicBrowser( 4588): [MediaPlaybackService.java:3551:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3552:notifyChange()] oooooo position() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3553:notifyChange()] oooooo ListSize : 0
V/SplitWindowPolicy( 4057): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1280): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0x0/ state=NATIVE]
V/SoundPool( 4141): load: fd=28, offset=0, length=6891, priority=1
V/SoundPool( 4141): load: fd=28, offset=0, length=6788, priority=1
V/SoundPool( 4141): Start decode
V/MediaPlayer[Native]( 4141): decode(30, 0, 6891)
V/MediaPlayerService(  466): decode(46, 0, 6891)
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{14263417 #53 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
V/MediaPlayerService(  466): player type = 4
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{14263417 #53 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/VendorSourceMaster(  466): libvendorsourcemaster v1.0.0.15.f563fd1
E/LocalMessageHandler(  466): create LocalMessageHandler
V/NuPlayer(  466): kWhatSetAudioSink
V/NuPlayer(  466): kWhatSetDataSource
I/ExtendedUtils(  466): printFileName fd(46) -> /system/media/audio/ui/cam_snap_0.ogg
V/MediaPlayerService(  466): prepare
V/MediaPlayerService(  466): wait for prepare
D/WindowStateEx( 1280): AppWindowTokenEx init.. 
V/WindowManager( 1280): addAppToken: AppWindowToken{2382e022 token=Token{376b49ed ActivityRecord{18ed6004 u0 com.example.hello/.MainActivity t53}}} to stack=1 task=53 at 0
I/art     ( 4141): Explicit concurrent mark sweep GC freed 20682(1546KB) AllocSpace objects, 17(455KB) LOS objects, 46% free, 36MB/68MB, paused 1.242ms total 42.052ms
D/ContextHelper( 1280): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 4311): onPause
D/InputDispatcher( 1280): Focus left window: Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/SplitWindowPolicy( 4057): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 4057): topRunningActivity=ActivityInfo{3acc730f co.....Launcher}, taskId=51, activityType=1, bIsSplit=false
D/AndroidRuntime( 7364): Shutting down VM
V/LGParserOSAL(  466): SniffLGParser start
V/LGParserOSAL(  466): MainType:5, SubType=0
V/LGParserOSAL(  466): #### check Mime : application/ogg
V/LGParserOSAL(  466): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  466): Use LGExtractor :application/ogg 
I/LIA_Informant_LIARemoteService( 7293): [LIA Remote Service Info] ------------------------
I/LIA_Informant_LIARemoteService( 7293):  - UID : 10031
I/LIA_Informant_LIARemoteService( 7293):  - LIA Core Version Name : 0.8.25
I/LIA_Informant_LIARemoteService( 7293):  - LIA Core Release Date : 2015.05.12
I/LIA_Informant_LIARemoteService( 7293):  - LIA Informant Task Version Name : 4.22.22
I/LIA_Informant_LIARemoteService( 7293):  - LIA Service Version Name : 0.8.20.2
I/LIA_Informant_LIARemoteService( 7293): --------------------------------------------------
D/LIA_Informant_LIARemoteService( 7293): onCreate()
D/PhoneGlobalsNet( 4118): networksettings : PhoneGlobals.java[157] : onCreate()...
I/LIA_Informant_InformantService( 7293): [main] getTaskPropertiesAtFirstStarting()
I/LIA_Informant_InformantService( 7293): [main] isNowInActivationCondition()
V/LGParserOSAL(  466): supported mime: application/ogg
I/GenericSource(  466): mPlayerInfo :VIDEO_TRACK_NOT_EXIST 
V/AudioCache(  466): notify(0xf215b080, 200, 1, 9120)
V/AudioCache(  466): ignored
V/AudioCache(  466): notify(0xf215b080, 1, 0, 0)
V/AudioCache(  466): prepared
V/AudioCache(  466): wait - success
V/MediaPlayerService(  466): start
D/NuPlayerDriver(  466): start(0xf5c715c0)
V/MediaPlayerService(  466): wait for playback complete
V/NuPlayer(  466): kWhatStart
I/GenericSource(  466): start
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
I/ExtendedUtils(  466): No channel mask, try channel count
W/ExtendedUtils(  466): No bitrate info
I/ExtendedUtils(  466): decision 0 mime audio/vorbis
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
I/NuPlayer(  466): Could not offload audio decode, pcm offload decided :0
V/NuPlayer(  466): scanning sources haveAudio=0, haveVideo=0
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
V/LGCodecAdapter(  466): LG Codec Adapter start
V/LGCodecOSAL(  466): Called LGCodeConvertMetaDataToMessage
V/LocalMessageHandler(  466): kWhatRegisterRendererInvoker
V/LGCodecAdapter(  466): LG Codec Adapter start
V/ACodec  (  466): ACodec
V/ACodec  (  466): Now uninitialized
V/ACodec  (  466): initiateAllocateComponent
V/ACodec  (  466): onAllocateComponent
I/LIA_Informant_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
V/AudioService( 1280): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService( 1280): No RCC entry present to update
V/OMXCodec(  466): findMatchingCodecs()
E/RemoteController( 4484): Cannot set synchronization mode on an unregistered RemoteController
V/OMXCodec(  466): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
I/BluetoothA2dpServiceJni( 4484): classInitNative
I/BluetoothA2dpServiceJni( 4484): classInitNative: succeeds
D/A2dpStateMachine( 4484): make
W/ResourcesManager( 7390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7390): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ACodec  (  466): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded
I/bluedroid( 4484): get_profile_interface a2dp
I/bt-btif ( 4484): btif_av_get_src_interface
I/bt-btif ( 4484): init
D/bt-btif ( 4484): btif_enable_service: current services:0xdde7e348
E/MediaCodec(  466): >>>>> MediaCodec::configure
E/MediaCodec(  466): >>>>> MediaCodec::configure flags is 0
V/LGCodecAdapter(  466): called getLGCodecSpecificData
V/LGCodecOSAL(  466): Called LGgetCodecSpecificDataMSG
V/ACodec  (  466): initiateConfigureComponent
V/ACodec  (  466): onConfigureComponent
V/ACodec  (  466): configureCodec
V/ACodec  (  466): setComponentRole called
V/LGCodecOSAL(  466): Called LGconfigureCodecMSG
V/LGCodecOSAL(  466): Not support LGCodec
I/LGBluetoothA2dpServiceJni( 4484): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 4484): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
V/ACodec  (  466): initiateStart
V/ACodec  (  466): onStart
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded->Idle
V/ACodec  (  466): allocateBuffersOnPort is portIndex=0
D/LGBluetoothPowerControlManager( 4484): [BTUI] getInstance
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 8192 on input port
V/ACodec  (  466): allocateBuffersOnPort is portIndex=1
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Idle->Executing
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
D/LGBluetoothPowerControlManager( 4484): [BTUI] init
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now handling output port settings change
V/ACodec  (  466): [OMX.google.vorbis.decoder] Output port now disabled.
V/ACodec  (  466): allocateBuffersOnPort is portIndex=1
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
V/ACodec  (  466): [OMX.google.vorbis.decoder] Output port now reenabled.
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
D/LGBluetoothSettingApp( 7390): REFCOUNT: Constructed com.lge.bluetoothsetting.LGBluetoothSettingApp@235696a2 Instance Count = 1
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
V/FormManager( 7339): App version changed.
V/LGCodecAdapter(  466): LG Codec Adapter start
V/LGCodecOSAL(  466): Called LGCodeConvertMetaDataToMessage
V/AudioCache(  466): open(48000, 1, 0x0, 1, 8)
W/ResourceType( 7390): ResTable_typeSpec entry count inconsistent: given 1, previously 845
W/ResourcesManager( 7390): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7390): Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
W/ResourcesManager( 7390): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7390): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/NuPlayer(  466): media rendering started
V/AudioCache(  466): notify(0xf215b080, 6, 0, 0)
V/AudioCache(  466): ignored
I/NuPlayerRenderer(  466): write audio internal buffering data : 512
D/SplitWindow( 1280): check instance of lgWin Window{3e458f0f u0 Starting com.example.hello}
V/WindowManager( 1280): Based on layer: Adding window Window{3e458f0f u0 Starting com.example.hello} at 2 of 9
D/ConfigUtils( 4118): COUNTRY : EU
D/ConfigUtils( 4118): OPERATOR : 1
D/ConfigUtils( 4118): ALTERNATIVE CARRIER : OPEN
D/ConfigUtils( 4118): MODEL NAME : LG-H815
D/ConfigUtils( 4118): REGION : EU
D/ConfigUtils( 4118): TARGET PLATFORM : msm8992
D/ConfigUtils( 4118): DEVICE_UNKNOWN : p1
D/ConfigUtils( 4118): MODEL NAME : LG-H815
I/ActivityManager( 1280): Start proc 7441:com.example.hello/u0a361 for activity com.example.hello/.MainActivity
V/ACodec  (  466): [OMX.google.vorbis.decoder] Signalled EOS on the input port
I/NuPlayerRenderer(  466): boost first writing of the audio frames
I/MusicWidget( 5805): intentReceiver onReceive() action::com.lge.music.queuechanged
D/LGBluetoothPowerControlManager( 4484): [BTUI] init : getProfileProxy
I/MusicBrowser( 4588): [MediaPlaybackService.java:2140:saveQueue()] oooooo {full=true}
I/MusicBrowser( 4588): [MediaPlaybackService.java:2145:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/BluetoothManagerService( 1280): Message: 30
I/[LGHome]EVENT( 4311): [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 4311): [Launcher.java:5479:setEnableShakeHandlers()]disableShakeHandlers
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
V/ACodec  (  466): [OMX.google.vorbis.decoder] saw output EOS
I/LGNetworkSettings( 4118): setUse4gNetwork
D/MusicBrowser( 4588): [MediaPlaybackService.java:2225:saveQueue()] oooooo {queue=}
I/networksettings : ( 4118): LGNetworkSettings.java[68] : disable LteGsmUmtsSettings
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/A2dpStateMachine( 4484): Enter Disconnected: -2
D/LGBluetoothDeviceModeControllManager( 4484): onServiceStarted - isSink : false mWaitingForService : false
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
I/BluetoothHidServiceJni( 4484): classInitNative: succeeds
D/MusicBrowser( 4588): [MediaPlaybackService.java:2227:saveQueue()] oooooo {mCardId=-1}
V/NuPlayer(  466): reached audio EOS
V/AudioCache(  466): notify(0xf215b080, 2, 0, 0)
V/AudioCache(  466): playback complete
V/AudioCache(  466): wait - success
V/MediaPlayerService(  466): return size 14448, sampleRate=48000, channelCount = 1, format = 1
D/NuPlayerDriver(  466): reset(0xf5c715c0) 6 ++ 
V/AudioCache(  466): notify(0xf215b080, 8, 0, 0)
V/AudioCache(  466): ignored
V/NuPlayer(  466): source disconnect ++ 
V/NuPlayer(  466): source disconnect -- 
V/NuPlayer(  466): kWhatReset
V/NuPlayer(  466): performDecoderFlush audio=2, video=2
V/NuPlayer(  466): [audio] flushDecoder needShutdown=1
V/NuPlayer(  466): postponing action mFlushingAudio=2, mFlushingVideo=0
V/ACodec  (  466): [OMX.google.vorbis.decoder] signalFlush
V/NuPlayer(  466): renderer audio flush completed.
V/ACodec  (  466): [OMX.google.vorbis.decoder] ExecutingState flushing now (codec owns 0/4 input, 1/4 output).
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Flushing
V/ACodec  (  466): [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
V/ACodec  (  466): [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
V/NuPlayer(  466): decoder audio flush completed
V/NuPlayer(  466): initiating audio decoder shutdown
D/MusicBrowser( 4588): [MediaPlaybackService.java:2272:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 5805): send mDelayedStopHandler
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing->Idle
I/MusicWidget( 5805): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Idle->Loaded
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded
I/ActivityManager( 1280): Killing 6721:com.lge.email/u0a56 (adj 15): empty #22
V/ACodec  (  466): Now uninitialized
V/PhoneGlobalsNet( 4118): Action intent recieved:android.intent.action.SIM_STATE_CHANGED
V/PhoneGlobalsNet( 4118): Action intent recieved:android.intent.action.SERVICE_STATE
V/ACodec  (  466): ~ACodec
V/NuPlayer(  466): audio shutdown completed
V/NuPlayer(  466): both audio and video are flushed now.
V/NuPlayer(  466): performReset
V/NuPlayer(  466): Source stop
V/NuPlayer(  466): Source clear ++ 
D/MusicBrowser( 4588): [MediaPlaybackService.java:3514:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 4588): [MediaPlaybackService.java:3516:notifyChange()] oooooo 
D/MusicBrowser( 4588): [MediaPlaybackService.java:3546:notifyChange()] oooooo id : 0
V/NuPlayer(  466): Source clear -- 
D/NuPlayerDriver(  466): notifyResetComplete(0xf5c715c0)
D/NuPlayerDriver(  466): reset(0xf5c715c0) 0 -- 
V/NuPlayer(  466): ~NuPlayer
V/SoundPool( 4141): close(30)
V/SoundPool( 4141): pointer = 0xdd5de000, size = 14448, sampleRate = 48000, numChannels = 1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3547:notifyChange()] oooooo artist : null
V/SoundPool( 4141): Start decode
V/MediaPlayer[Native]( 4141): decode(33, 0, 6788)
V/MediaPlayerService(  466): decode(46, 0, 6788)
D/MusicBrowser( 4588): [MediaPlaybackService.java:3548:notifyChange()] oooooo album : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3549:notifyChange()] oooooo track : null
D/MusicBrowser( 4588): [MediaPlaybackService.java:3550:notifyChange()] oooooo playing : false
D/HidService( 4484): Received start request. Starting profile...
D/MusicBrowser( 4588): [MediaPlaybackService.java:3551:notifyChange()] oooooo duration() : -1
I/bluedroid( 4484): get_profile_interface hidhost
I/bt-btif ( 4484): btif_hh_get_interface
I/bt-btif ( 4484): init
D/bt-btif ( 4484): btif_enable_service: current services:0xdde7e348
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/MusicBrowser( 4588): [MediaPlaybackService.java:3552:notifyChange()] oooooo position() : -1
D/MusicBrowser( 4588): [MediaPlaybackService.java:3553:notifyChange()] oooooo ListSize : 0
I/BluetoothHealthServiceJni( 4484): classInitNative: succeeds
D/NotificationMgrNet( 4118): updateNetworkSelection()...state = 2 new network 
D/NotificationMgrNet( 4118): cancelNetworkSelection()...
I/NotificationManager( 4118): com.lge.networksettings: cancel(6) by com.lge.networksettings
V/MediaPlayerService(  466): player type = 4
D/VendorSourceMaster(  466): libvendorsourcemaster v1.0.0.15.f563fd1
E/LocalMessageHandler(  466): create LocalMessageHandler
V/NuPlayer(  466): kWhatSetAudioSink
V/NuPlayer(  466): kWhatSetDataSource
I/ExtendedUtils(  466): printFileName fd(46) -> /system/media/audio/ui/camstart.ogg
V/MediaPlayerService(  466): prepare
V/MediaPlayerService(  466): wait for prepare
D/HealthService( 4484): Received start request. Starting profile...
I/[LGHome]EVENT( 4311): onStop
V/LGParserOSAL(  466): SniffLGParser start
V/LGParserOSAL(  466): MainType:5, SubType=0
V/LGParserOSAL(  466): #### check Mime : application/ogg
I/bluedroid( 4484): get_profile_interface health
I/bt-btif ( 4484): btif_hl_get_interface
I/bt-btif ( 4484): init
D/bt-btif ( 4484): Process name (droid.bluetooth)
D/bt-btif ( 4484): btif_hl_soc_thread_init
D/bt-btif ( 4484): create_thread: entered
D/bt-btif ( 4484): create_thread: thread created successfully
D/bt-btif ( 4484): entered btif_hl_select_thread
D/bt-btif ( 4484): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 4484): classInitNative: succeeds
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/bt-btif ( 4484): btif_hl_select_wakeup_init signal_fds[0]=58 signal_fds[1]=59
D/bt-btif ( 4484): max_s=58 
D/bt-btif ( 4484): set curr_set = org_set 
D/HeadsetStateMachine( 4484): Proxy object connected
D/LGBluetoothHfpAdapter( 4484): [BTUI] queryPhoneState
I/BluetoothPanServiceJni( 4484): classInitNative(L105): succeeds
V/LGParserOSAL(  466): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  466): Use LGExtractor :application/ogg 
D/PanService( 4484): Received start request. Starting profile...
D/BluetoothPanServiceJni( 4484): initializeNative(L110): pan
I/bluedroid( 4484): get_profile_interface pan
D/bt-btif ( 4484): stack_initialized = 0, btpan_cb.enabled:0
V/LGParserOSAL(  466): supported mime: application/ogg
I/GenericSource(  466): mPlayerInfo :VIDEO_TRACK_NOT_EXIST 
V/AudioCache(  466): notify(0xf5c74b80, 200, 1, 9120)
V/AudioCache(  466): ignored
V/AudioCache(  466): notify(0xf5c74b80, 1, 0, 0)
V/AudioCache(  466): prepared
V/AudioCache(  466): wait - success
V/MediaPlayerService(  466): start
D/NuPlayerDriver(  466): start(0xf5c71b70)
V/MediaPlayerService(  466): wait for playback complete
V/NuPlayer(  466): kWhatStart
I/GenericSource(  466): start
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
I/ExtendedUtils(  466): No channel mask, try channel count
W/ExtendedUtils(  466): No bitrate info
I/ExtendedUtils(  466): decision 0 mime audio/vorbis
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
I/NuPlayer(  466): Could not offload audio decode, pcm offload decided :0
V/LocalMessageHandler(  466): kWhatRegisterRendererInvoker
V/NuPlayer(  466): scanning sources haveAudio=0, haveVideo=0
I/AudioFlinger(  466): isAudioPlaybackHookOn() false
D/AudioPolicyManager(  466): isOffloadSupported: stream_type != MUSIC, returning false
V/LGCodecAdapter(  466): LG Codec Adapter start
V/LGCodecOSAL(  466): Called LGCodeConvertMetaDataToMessage
V/LGCodecAdapter(  466): LG Codec Adapter start
V/ACodec  (  466): ACodec
V/ACodec  (  466): Now uninitialized
V/ACodec  (  466): initiateAllocateComponent
V/ACodec  (  466): onAllocateComponent
V/OMXCodec(  466): findMatchingCodecs()
V/OMXCodec(  466): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
D/ACodec  (  466): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded
E/MediaCodec(  466): >>>>> MediaCodec::configure
E/MediaCodec(  466): >>>>> MediaCodec::configure flags is 0
D/LGBluetoothSettingsSearchIndexablesProvider( 7390): onCreate()
V/LGCodecAdapter(  466): called getLGCodecSpecificData
V/LGCodecOSAL(  466): Called LGgetCodecSpecificDataMSG
V/ACodec  (  466): initiateConfigureComponent
V/ACodec  (  466): onConfigureComponent
V/ACodec  (  466): configureCodec
V/ACodec  (  466): setComponentRole called
V/LGCodecOSAL(  466): Called LGconfigureCodecMSG
V/LGCodecOSAL(  466): Not support LGCodec
V/ACodec  (  466): initiateStart
V/ACodec  (  466): onStart
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded->Idle
V/ACodec  (  466): allocateBuffersOnPort is portIndex=0
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 8192 on input port
V/ACodec  (  466): allocateBuffersOnPort is portIndex=1
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Idle->Executing
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
I/IndexDatabaseHelper( 7390): Using schema version: 115
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now handling output port settings change
I/IndexDatabaseHelper( 7390): Index is fine
V/ACodec  (  466): [OMX.google.vorbis.decoder] Output port now disabled.
V/ACodec  (  466): allocateBuffersOnPort is portIndex=1
V/ACodec  (  466): [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
V/ACodec  (  466): [OMX.google.vorbis.decoder] Output port now reenabled.
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
V/LGCodecAdapter(  466): LG Codec Adapter start
V/LGCodecOSAL(  466): Called LGCodeConvertMetaDataToMessage
V/AudioCache(  466): open(48000, 1, 0x0, 1, 8)
V/NuPlayer(  466): media rendering started
V/AudioCache(  466): notify(0xf5c74b80, 6, 0, 0)
V/AudioCache(  466): ignored
I/NuPlayerRenderer(  466): write audio internal buffering data : 256
V/ACodec  (  466): [OMX.google.vorbis.decoder] Signalled EOS on the input port
V/ACodec  (  466): [OMX.google.vorbis.decoder] saw output EOS
V/NuPlayer(  466): reached audio EOS
V/AudioCache(  466): notify(0xf5c74b80, 2, 0, 0)
V/AudioCache(  466): playback complete
V/AudioCache(  466): wait - success
V/MediaPlayerService(  466): return size 47472, sampleRate=48000, channelCount = 1, format = 1
D/NuPlayerDriver(  466): reset(0xf5c71b70) 6 ++ 
V/AudioCache(  466): notify(0xf5c74b80, 8, 0, 0)
V/AudioCache(  466): ignored
V/NuPlayer(  466): source disconnect ++ 
V/NuPlayer(  466): source disconnect -- 
V/NuPlayer(  466): kWhatReset
V/NuPlayer(  466): performDecoderFlush audio=2, video=2
V/NuPlayer(  466): [audio] flushDecoder needShutdown=1
V/NuPlayer(  466): postponing action mFlushingAudio=2, mFlushingVideo=0
V/NuPlayer(  466): renderer audio flush completed.
V/ACodec  (  466): [OMX.google.vorbis.decoder] signalFlush
V/ACodec  (  466): [OMX.google.vorbis.decoder] ExecutingState flushing now (codec owns 0/4 input, 1/4 output).
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Flushing
V/ACodec  (  466): [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
V/ACodec  (  466): [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing
V/NuPlayer(  466): decoder audio flush completed
V/NuPlayer(  466): initiating audio decoder shutdown
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Executing->Idle
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Idle->Loaded
V/ACodec  (  466): [OMX.google.vorbis.decoder] Now Loaded
V/ACodec  (  466): Now uninitialized
V/ACodec  (  466): ~ACodec
V/NuPlayer(  466): audio shutdown completed
V/NuPlayer(  466): both audio and video are flushed now.
V/NuPlayer(  466): performReset
V/NuPlayer(  466): Source stop
V/NuPlayer(  466): Source clear ++ 
V/NuPlayer(  466): Source clear -- 
D/NuPlayerDriver(  466): notifyResetComplete(0xf5c71b70)
D/NuPlayerDriver(  466): reset(0xf5c71b70) 0 -- 
V/NuPlayer(  466): ~NuPlayer
V/SoundPool( 4141): close(33)
V/SoundPool( 4141): pointer = 0xdcafe000, size = 47472, sampleRate = 48000, numChannels = 1
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
I/LIA_Informant_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
I/WindowStateAnimator( 1280): Starting window displayed
I/SystemUI[Framework]( 1280): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 3398): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx( 1280): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1280): setLGSystemUiVisibility(0x0)
I/SystemUI[Framework]( 1280): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ba56745,  pkg=Window{3e458f0f u0 Starting com.example.hello}
D/StatusBarManagerServiceEx( 1280): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{3e458f0f u0 Starting com.example.hello}
I/SystemUI[Framework]( 1280): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 3398): NavigationKey Color is changed(WHITE_WITH_SHADOW -> WHITE)
I/[SystemUI]NavigationThemeResource( 3398):  BarMode=0, Theme=BLACK, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 3398): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MusicBrowser( 4588): [MediaPlaybackService.java:3565:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/LGBluetoothPanAdapter( 4484): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/ActionManagerService( 4204): notifyUserLog: 1000004
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
W/ActivityThread( 4311): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 4311): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 4311): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3450)
W/ActivityThread( 4311): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3539)
W/ActivityThread( 4311): 	at android.app.ActivityThread.access$1100(ActivityThread.java:162)
W/ActivityThread( 4311): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1378)
W/ActivityThread( 4311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 4311): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 4311): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
W/ActivityThread( 4311): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 4311): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 4311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
W/ActivityThread( 4311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
I/MusicBrowser( 4588): [MediaPlaybackService.java:2140:saveQueue()] oooooo {full=false}
I/BtGatt.JNI( 4484): classInitNative(L901): classInitNative: Success!
D/BarTransitions( 3398): draw background and invalidate : color = 8000000
I/MusicBrowser( 4588): [MediaPlaybackService.java:2145:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/LGBluetoothSettingApp( 7390): onCreate
I/MusicBrowser( 4588): [MediaPlaybackService.java:10362:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 4588): [MediaPlaybackService.java:10428:run()] oooooo AlbumImageUpdater() run :: End
D/BarTransitions( 3398): draw background and invalidate : color = b000000
I/MusicWidget( 5805): intentReceiver onReceive() action::com.lge.music.metachanged
D/BtGatt.DebugUtils( 4484): handleDebugAction() action=null
D/BtGatt.GattService( 4484): Received start request. Starting profile...
D/BtGatt.GattService( 4484): start()
I/bluedroid( 4484): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 4484): advertise manager created
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
D/SplitWindowPolicy( 4057): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 4057): topRunningActivity=ActivityInfo{20b5bf9c co.....MainActivity}, taskId=53, activityType=0, bIsSplit=false
I/MusicWidget( 5805): send mDelayedStopHandler
I/MusicWidget( 5805): performViewUpdater handleMessage() msg.what::0
D/MusicBrowser( 4588): [MediaPlaybackService.java:2272:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 4588): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 4588): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 4588): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 4588): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicWidget( 5805): beingMusicWidget_4x1() result::false
D/MusicBrowser( 4588): [MediaPlaybackService.java:3046:onReceive()] oooooo [BTUI] onReceive() : com.lge.bluetooth.getNowPlayingEntries
I/MusicBrowser( 4588): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/ActivityManager( 1280): Start proc 7476:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
I/ActivityManager( 1280): Killing 6821:com.lge.lpd/1000 (adj 15): empty #22
E/MusicBrowser( 4588): [GroupingIndexDataProvider.java:381:onCancelled()] oooooo ASYNCTASK is canceled
I/MusicBrowser( 4588): [MediaPlaybackService.java:2028:handleMessage()] oooooo mGroupIndexHandler msg.what : 1
I/ActivityManager( 1280): Activity reported stop, but no longer stopping: ActivityRecord{9628d4c u0 com.lge.launcher2/.Launcher t51}
V/MusicBrowser( 4588): [MediaPlaybackService.java:6108:getPath()] oooooo {mFileToPlay=null}
I/LGBluetoothGattAdapter( 4484): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 4484): setGattService:  set to: null
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/ContextHelper( 7441): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
I/LGBluetoothMapAdapter( 4484): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 4484): BluetoothMapBinder()
D/BluetoothMapService( 4484): Received start request. Starting profile...
D/BluetoothMapService( 4484): start()
I/NotificationManager( 7019): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
D/BluetoothMapEmailSettingsLoader( 4484): Found 0 applications
D/BluetoothMapEmailAppObserver( 4484): createReceiver()
D/BluetoothMapEmailAppObserver( 4484): initObservers()
D/BluetoothMapEmailAppObserver( 4484): getEnabledAccountItems()
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/LIA_Informant_MrGServiceBase( 7293): Version Update Check : CASE2 - This is not the first task launching after installing the first version APK or updated version APK
I/LIA_Informant_LIARemoteService( 7293): checkTaskInitialization() : needResetTaskPropertyInSharedPreference() is false, so maintain SharedPreference
D/LIA_Informant_LIARemoteService( 7293): getTaskPreparation()
I/LIA_Informant_InformantService( 7293): [main] getTaskPropertiesAtFirstStarting()
I/LIA_Informant_InformantService( 7293): [main] isNowInActivationCondition()
I/LIA_Informant_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 4484): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 4484): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 4484): Disconnected process message: 11, size: 0
I/BluetoothSAPServiceJni( 4484): classInitNative(L170): succeeds
D/SapService( 4484): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 4484): initializeNative(L175): sap
I/bluedroid( 4484): get_profile_interface sap
I/bt-btif ( 4484): btif_sc_get_interface
I/bt-btif ( 4484): init
D/bt-btif ( 4484): btif_enable_service: current services:0xdde7e348
I/LGBluetoothSapAdapter( 4484): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 4484): [BTUI] Create LGBluetoothSapManager Instance
V/LIA_AppRecommendContentProvider( 7476): MrGContentProvider onCreate()
D/LGBluetoothSapManager( 4484): [BTUI] initSapManager
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LgeBluetoothSimManager( 4118): [BTUI] SAP_ENABLE_EVT
I/ActivityManager( 1280): Killing 6269:com.android.contacts/u0a18 (adj 15): empty #22
I/LIA_Informant_BoardStateUtil( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : LGHome condition is true
I/NotificationManager( 1280): android: cancelAsUser(2145784878) by android
I/WebViewFactory( 7441): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
I/MusicWidget( 5805): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 5805): category == AppWidgetProviderInfo.WIDGET_CATEGORY_HOME_SCREEN
I/MusicWidget( 5805): beingMusicWidget_4x2() result::true
I/MusicWidget( 5805): performUpdate()
I/MusicWidget( 5805): defaultAppWidget()_4x2
I/MusicWidget( 5805): setRemoteView ( true ) 
I/MusicWidget( 5805): setViewLayoutId()_4x2
I/MusicWidget( 5805): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 5805): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 5805): res :: null 4x2_currentTheme :: null
I/MusicWidget( 5805): setDefaultViewmLayoutId()
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/LGBluetoothFeatureConfig( 4484): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 4484): classInitNative
I/BluetoothOPPServiceJni( 4484): classInitNative(L373): succeeds
I/MusicWidget( 5805): no_Image :: android.graphics.Bitmap@15c75820
I/MusicWidget( 5805): appWidgetViewUpdate()_4x2
I/MusicWidget( 5805): linkButtons()_4x2
I/LIA_SmartSetting(4.50.6)_LogCore( 7476): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
V/MusicBrowser( 4588): [MediaPlaybackService.java:6108:getPath()] oooooo {mFileToPlay=null}
V/OppService( 4484): Opp initBinder
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7476): onReceive state= 11
W/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): setting value is undefined.
D/**OppService( 4484): Received start request. Starting profile...
D/OppService( 4484): Starting OppService 
D/LGBluetoothOppAdapter( 4484): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7293): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7293): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LIA_Informant_LIARemoteService( 7293): updateTaskProperties()
D/LIA_Informant_LIARemoteService( 7293): --> Getting task property of activation from Shared preferences ...
D/LIA_Informant_LIARemoteService( 7293): --> Task property for activation for Informant is true
D/LIA_Informant_LIARemoteService( 7293): --> Task property for activation for SmartMoment is true
D/LIA_Informant_LIARemoteService( 7293): --> Task property for activation for TermExtraction is true
D/LIA_Informant_LIARemoteService( 7293): --> Task property for activation for UIMAgent is true
D/LIA_Informant_LIARemoteService( 7293): --> Getting activation properties done!
I/MusicWidget( 5805): getFavoriteValue()
I/NotificationManager( 4484): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 4484): send message
D/LIA_Informant_LIARemoteManager( 7293): init()
D/BluetoothOppPreference( 4484): Dumping Names:  
D/BluetoothOppPreference( 4484): {}
D/BluetoothOppPreference( 4484): Dumping Channels:  
D/BluetoothOppPreference( 4484): {}
D/OppService( 4484): Start()
W/BluetoothOPPServiceJni( 4484): initOppNative
D/BluetoothOPPServiceJni( 4484): initOppNative(L383): OPP
I/bluedroid( 4484): get_profile_interface opp
I/bt-btif ( 4484): btif_op_get_interface
D/BluetoothOPPServiceJni( 4484): initOppNative(L411): mOppCallbacksObj 2100202
D/BluetoothOPPServiceJni( 4484): initOppNative(L413): calling OPP init
I/bt-btif ( 4484): btif_opp_init
D/bt-btif ( 4484): btif_enable_service: current services:0xdde7e348
D/BluetoothOPPServiceJni( 4484): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 4484): initOppNative(L430): mOppCallbacksObj 2100202
V/OppService( 4484): setOppService(): set to: com.broadcom.bt.service.opp.OppService@4f65e29
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 4484): pendingUpdate is :  true
I/MusicWidgetView4x2( 5805): getFavorite cursor null
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): onReceive(), ConnectedDeviceName : null , Num : 0
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 4484): Proxy object connected
D/LGBluetoothPowerControlManager( 4484): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@2a4cc5ae
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/LIA_Informant_LIARemoteService( 7293): prepare() : Tasks are registering ...
D/LIA_Informant_LIARemoteService( 7293): --> Task name : Informant
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/MusicWidget( 5805): pushUpdate()_4x2
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
D/LIA_Informant_TaskLauncher( 7293): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7293): --> Task name : SmartMoment
D/LIA_Informant_TaskLauncher( 7293): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7293): --> Task name : TermExtraction
D/LIA_Informant_TaskLauncher( 7293): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7293): --> Task name : UIMAgent
D/LIA_Informant_TaskLauncher( 7293): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7293): prepare() : Tasks have been registered.
I/LIA_Informant_LogCore( 7293): LIA Log setTagPrefix - prefix : LIA_Informant_
I/LIA_Informant_Tips_ModelReleaseConfig( 7293): isSupportModel() : SmartTips App Installed - true
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/LIA_Informant_Tips_ModelReleaseConfig( 7293): isSupportModel() : SmartTips App Installed - true
I/LIA_Informant_Tips_ModelReleaseConfig( 7293): isSupportModel() : SmartTips App Installed - true
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information - BluetoothSettings
I/LibraryLoader( 7441): Time to load native libraries: 1 ms (timestamps 1880-1881)
I/LibraryLoader( 7441): Expected native library version number "",actual native library version number ""
I/ActivityManager( 1280): Killing 6846:com.android.keychain/1000 (adj 15): empty #22
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 4484): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 4484): Deleted complete outbound shares, number =  0
V/OppService( 4484): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 4484): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@21a38eba on behalf of 
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@5fca16b on behalf of 
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 4484): Handler(): got msg=1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 4484): update too frequent, put in queue
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 4484): pendingUpdate is :  false
E/OppService( 4484): UpdateThread is Completed
D/BluetoothAdapterService( 4484): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 4484): new notify threadi!
V/BluetoothOppNotification( 4484): send delay message
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - All profile services started.
V/OppService( 4484): ContentObserver received notification
D/BluetoothAdapterState( 4484): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 4484): enable
I/bt-btif ( 4484): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 4484): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 4484): ContentObserver received notification
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 4484): pendingUpdate is :  true
I/bt_hci_bdroid( 4484): init
I/bt_vendor( 4484): init
I/bt_vnd_conf( 4484): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
I/bt_vnd_conf( 4484): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_vendor( 4484): op for 5
I/GKI_LINUX( 4484): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 4484): btu_task pending for preload complete event
I/bt-btif ( 4484): libbt-hci init returns 0
D/bt_vendor( 4484): op for 0
D/bt_vendor( 4484): op for 0
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@98184c8 on behalf of 
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@3d4aa961 on behalf of 
V/BluetoothOppNotification( 4484): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/OppService( 4484): pendingUpdate is :  false
E/OppService( 4484): UpdateThread is Completed
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@3a6bdc86 on behalf of 
V/WebViewChromiumFactoryProvider( 7441): Binding Chromium to main looper Looper (main, tid 1) {7c0ae1c}
I/LibraryLoader( 7441): Expected native library version number "",actual native library version number ""
I/chromium( 7441): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/BluetoothOppNotification( 4484): outbound: succ-0  fail-0
I/NotificationManager( 4484): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 4484): outbound notification was removed.
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@12c1e947 on behalf of 
V/BluetoothOppNotification( 4484): inbound: succ-0  fail-0
I/NotificationManager( 4484): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 4484): inbound notification was removed.
I/BrowserStartupController( 7441): Initializing chromium process, singleProcess=true
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
W/art     ( 7441): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7441): ApplicationContext is null in ApplicationStatus
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@58e2574 on behalf of 
W/chromium( 7441): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 7441): QUALCOMM build                   : 7fcf94b, Ib2e715f795
I/Adreno  ( 7441): Build Date                       : 07/03/15
I/Adreno  ( 7441): OpenGL ES Shader Compiler Version: E031.25.03.09
I/Adreno  ( 7441): Local Branch                     : 
I/Adreno  ( 7441): Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
I/Adreno  ( 7441): Remote Branch                    : NONE
I/Adreno  ( 7441): Reconstruct Branch               : NOTHING
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
V/AudioPolicyService(  466): registerClient() client 0xf2155260, uid 10361
D/BluetoothManagerService( 1280): Message: 20
D/BluetoothManagerService( 1280): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43214da:true
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/LIA_Informant_TimeAlarmHandler( 7293): setRepeating() : 2016-03-07 14:41:45
D/LIA_Informant_LIARemoteService( 7293): onStartCommand() : LIARemoteService started! - (Id :1), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
D/LIA_Informant_LIARemoteService( 7293): onBind()
D/LIA_Informant_LIARemoteManager( 7293): getBinder()
V/BluetoothSapReceiver( 4484): [BTUI] checkServiceStart
D/ActionManager( 7293): connected to ActionManagerService.
D/LIA_Service_RemoteProxy( 4268): onServiceConnected() : com.lge.ia.task.informant
D/LIA_S4URecommender_S4URecommenderTask( 7293): handleMessage : 1002
D/LIA_S4URecommender_S4URecommenderTask( 7293): Connected to ActionManager Service
D/LIA_Informant_LIARemoteManager( 7293): getProperties()
D/LIA_Informant_TaskLauncher( 7293): getTaskPropertyList() - main launcher : false
V/LIA_Service_RemoteProxy( 4268): onServiceConnected() : Task Property for TermExtraction - Activation:true, AutoExecution:false
V/LIA_Service_RemoteProxy( 4268): onServiceConnected() : Task Property for UIMAgent - Activation:true, AutoExecution:false
V/LIA_Service_RemoteProxy( 4268): onServiceConnected() : Task Property for Informant - Activation:true, AutoExecution:true
V/LIA_Service_RemoteProxy( 4268): onServiceConnected() : Task Property for SmartMoment - Activation:true, AutoExecution:true
D/LIA_Service_RemoteSessionManager( 4268): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 4268): Added task & RemoteProxy: TermExtraction, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
I/LIA_Service_RemoteSessionManager( 4268): Added task & RemoteProxy: UIMAgent, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
I/LIA_Service_RemoteSessionManager( 4268): Added task & RemoteProxy: Informant, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
I/LIA_Service_RemoteSessionManager( 4268): Added task & RemoteProxy: SmartMoment, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
V/LIA_Service_RemoteSessionManager( 4268): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 4268): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4268): --> TermExtraction is registered on LIACores
D/LIA_Service_TaskLauncher( 4268): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4268): --> UIMAgent is registered on LIACores
D/LIA_Service_TaskLauncher( 4268): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4268): --> Informant is registered on LIACores
D/LIA_Service_TaskLauncher( 4268): --> Informant is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4268): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4268): runTask() : Informant
D/LIA_Service_RemoteProxy( 4268): runTask() : Task name & RemoteProxy - Informant, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
I/LIA_Service_LogTracer( 4268): [Log Tracer - Task State Transition] runTask(Informant)...... 
D/LIA_Informant_LIARemoteManager( 7293): runTask() : Informant
D/LIA_Informant_TaskLauncher( 7293): runTask - main launcher : false
V/LIA_Informant_TaskContext( 7293): runSession() : Informant
D/LIA_Informant_LIARemoteService( 7293): getTask()
D/LIA_Informant_TaskSession( 7293): TaskSession.of() - thread id : 264, thread name : Binder_1
D/bt_vendor( 4484): op for 3
I/bt_userial_vendor( 4484): userial vendor open: opening /dev/ttyHS0
I/bt_userial_vendor( 4484): device fd = 73 open
D/bt_vendor( 4484): set_bluetooth_preproto set on
D/bt_vendor( 4484): op for 1
D/bt_vendor( 4484): op for 10
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] create(Informant)...... Request
I/LIA_Informant_InformantTask( 7293): [Binder_1] create!!!!!!
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] create(Informant)...... Success
I/LIA_Informant_TaskSession( 7293): Informant task is created !!
I/LIA_Informant_TaskSession( 7293): Informant create() process time = 1 msec
D/LIA_Informant_TaskSession( 7293): enable() - enable state : false, thread id : 264, thread name : Binder_1
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] start(Informant)...... Request
I/LIA_Informant_InformantTask( 7293): [pool-3-thread-1] task start!!!!
D/LIA_Informant_InformantManager( 7293): [pool-3-thread-1] start
D/LIA_Informant_ActionManagerMessageHandler( 7293): [pool-3-thread-1] start
D/LIA_Informant_ActionManagerMessageHandler( 7293): [pool-3-thread-1] new actionCategoryID = 17053184
D/LIA_Informant_ActionManagerMessageHandler( 7293): [pool-3-thread-1] connectActionManager
I/LIA_Informant_ActionManagerMessageHandler( 7293): [ActionManagerHandler] connect ActionManager: action id mask = 0x1043600
I/ActivityManager( 1280): Start proc 7533:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
D/ActionManager( 7293): connecting to ActionManagerService...
D/LIA_Informant_UIMAgent( 7293): UIMAgent Alarm: android.intent.action.BOOT_COMPLETED
D/ActionManagerService( 4204): Messenger is registered - action id mask=0x43e00
D/bt_hwcfg( 4484): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 4484): hw_config_cback state=1
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_UIMAgent( 7293): isInFormantOn!!; true
I/LIA_Informant_UIMAgent( 7293): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_UIMAgent( 7293): LG HOME!!; true
D/LIA_Informant_UIMAgent( 7293): UIMAgent Register Alarm
D/LIA_Informant_UIMAgent( 7293): Alarm does not exist. Register Long Term Alarm
D/LIA_Informant_UIMAgent( 7293): Batch will start tomorrow
D/ActionManager( 7293): connected to ActionManagerService.
D/LIA_Informant_ActionManagerMessageHandler( 7293): [ActionManagerHandler] handleMessage: what(1002) actionID(0x0)
D/LIA_Informant_ActionManagerMessageHandler( 7293): [ActionManagerHandler] ActionManager connected!!!!
D/LIA_Informant_InformantManager( 7293): [ActionManagerHandler] ActionManager onConnected
I/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] start
I/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] setState = 0
I/LIA_Informant_TaskSession( 7293): Informant start() result: true, process time = 32 msec
D/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] registerActionEventListener
I/LIA_Informant_ActionManagerMessageHandler( 7293): [ActionManagerHandler] registerListener = concierge_card
I/LIA_Informant_ActionManagerMessageHandler( 7293): [ActionManagerHandler] after add numListener = 1
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] start(Informant)...... Success
I/LIA_Informant_TaskSession( 7293): enable() - enable state : true
D/LIA_Informant_TaskContext( 7293): runSeesion() succeeded.
D/LIA_Informant_TaskLauncher( 7293): runTask - succeeded.
D/LIA_Service_TaskLauncher( 4268): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4268): --> SmartMoment is registered on LIACores
D/LIA_Service_TaskLauncher( 4268): --> SmartMoment is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4268): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4268): runTask() : SmartMoment
D/LIA_Service_RemoteProxy( 4268): runTask() : Task name & RemoteProxy - SmartMoment, com.lge.ia.manager.remote.RemoteProxy@25c7d1ab
I/LIA_Service_LogTracer( 4268): [Log Tracer - Task State Transition] runTask(SmartMoment)...... 
D/LIA_Informant_LIARemoteManager( 7293): runTask() : SmartMoment
D/LIA_Informant_TaskLauncher( 7293): runTask - main launcher : false
V/LIA_Informant_TaskContext( 7293): runSession() : SmartMoment
D/LIA_Informant_LIARemoteService( 7293): getTask()
D/LIA_Informant_TaskSession( 7293): TaskSession.of() - thread id : 266, thread name : Binder_2
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] create(SmartMoment)...... Request
D/LIA_Informant_SmartMomentTask( 7293): create
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] create(SmartMoment)...... Success
I/LIA_Informant_TaskSession( 7293): SmartMoment task is created !!
I/LIA_Informant_TaskSession( 7293): SmartMoment create() process time = 0 msec
D/LIA_Informant_TaskSession( 7293): enable() - enable state : false, thread id : 266, thread name : Binder_2
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] start(SmartMoment)...... Request
D/LIA_Informant_SmartMomentTask( 7293): start
D/LIA_Informant_BirthdayTimeNoticeFlowManager( 7293): BirthdayTimeNoticeFlowManager
D/LIA_Informant_LDBAccessManager( 7293): LDBAccessManager
D/LIA_Informant_BirthdayDBManager( 7293): BirthdayDBManager
D/LIA_Informant_BirthdayDBHelper( 7293): BirthdayDBHelper
D/LIA_Informant_CTP_DBConnectionManagerAndroid( 7293):  setAndroidResource:  null
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7293): CallbackTimePredictorCore Engine start
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7293): mode: 0, null
D/LIA_Informant_CTP_DBConnectionManagerAndroid( 7293):  setAndroidResource:  null
D/bt_hwcfg( 4484): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 4484): hw_config_cback state=4
D/bt_hwcfg( 4484): Chipset Name: BCM4335C0
D/bt_hwcfg( 4484): Change chipset Name: BCM4339
D/bt_hwcfg( 4484): Chipset BCM4339
D/bt_hwcfg( 4484): Target name = [BCM4339]
I/bt_hwcfg( 4484): Found patchfile: /system/bin//BCM4339_003.001.009.0108.0501_LGE_P1-EU_FM_ORC.hcd
W/art     ( 7441): Attempt to remove local handle scope entry from IRT, ignoring
D/LIA_Informant_CTP_PredictorThread( 7293):  creator!!
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7293): startPredictorThread enters!!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7293): /data/data/com.lge.ia.task.informant/  is created!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7293): /data/data/com.lge.ia.task.informant/  is created!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7293): /data/data/com.lge.ia.task.informant/SmartMoment/CallbackTiming.db
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 4484): hw_config_cback state=2
W/AwContents( 7441): onDetachedFromWindow called when already detached. Ignoring
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 4484): hw_config_cback state=3
I/bt_hwcfg( 4484): bt vendor lib: set UART baud 4000000
D/SystemWebViewEngine( 7441): CordovaWebView is running on device made by: LGE
D/LIA_Informant_CTP_PredictorThread( 7293): init() enters!!
D/LIA_Informant_CTP_NaiveBayes( 7293): CallbackTimePredictorDBAccess: com.lge.s4u.DB.Android.CallbackTimePredictorDBAccessAndroid@1b139695
I/ActivityManager( 1280): Start proc 7561:com.lge.lpd/1000 for broadcast com.lge.lpd/.receiver.LPDBootCompletedReceiver
D/ActionManagerService( 4204): Messenger is registered - action id mask=0x1043600
I/LIA_Informant_BoardStateUtil( 7293): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] ConciergeBoard On!!!
I/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] getState = 0
I/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] setState = 1
D/LIA_Informant_ConciergeCardManager( 7293): [ActionManagerHandler] startFlowManager key = concierge_weather_briefing
D/LIA_Informant_FlowManagerPlant( 7293): [ActionManagerHandler] WEATHER_BRIEFING
D/LIA_Informant_CTP_MaxTimeConstraintReceiver( 7293): MaxTimeConstraintReceiver creator!!
D/LIA_Informant_CTP_PredictorThread( 7293): initPrefereces start!!
W/art     ( 7441): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7441): Attempt to remove local handle scope entry from IRT, ignoring
D/LIA_Informant_CTP_PredictorThread( 7293): initPrefereces end
D/LIA_Informant_CTP_PredictorThread( 7293): threshold: 0.7
D/LIA_Informant_CTP_PredictorThread( 7293): trackingIdArray:
D/LIA_Informant_CTP_MultipleSensorDetector( 7293): MultipleSensorDetector Start!!! OK~
I/LIA_Informant_FlowManagerPlant( 7293): [ActionManagerHandler] ConciergeScript serverMode = OP_SERVER
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 4484): hw_config_cback state=5
D/LIA_Informant_ArchiveManager( 7293): ArchiveManager
W/ResourcesManager( 7533): Asset path '/system/framework/com.lge.locksettings.jar' does not exist or contains no resources.
W/ResourcesManager( 7533): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LIA_Informant_CTP_PredictorThread( 7293):  run() enters!!!! Looper.prepare() is done 
I/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : without handler
D/SensorManager( 7293): found sensor: LGE Accelerometer, handle=0
D/SensorManager( 7293): found sensor: LGE Magnetometer, handle=10
D/SensorManager( 7293): found sensor: LGE Magnetometer Uncalibrated, handle=11
D/SensorManager( 7293): found sensor: LGE Gyroscope, handle=2
D/SensorManager( 7293): found sensor: LGE Gyroscope Uncalibrated, handle=8
D/SensorManager( 7293): found sensor: LGE Proximity, handle=48
D/SensorManager( 7293): found sensor: LGE Knock-on Proximity Sensor, handle=74
D/SensorManager( 7293): found sensor: LGE Virtual Proximity Sensor, handle=75
D/SensorManager( 7293): found sensor: LGE Light, handle=1
D/SensorManager( 7293): found sensor: LGE Pressure, handle=3
D/SensorManager( 7293): found sensor: LGE Accelerometer -Wakeup Secondary, handle=17
D/SensorManager( 7293): found sensor: LGE Magnetometer -Wakeup Secondary, handle=26
D/SensorManager( 7293): found sensor: LGE Magnetometer Uncalibrated -Wakeup Secondary, handle=27
D/SensorManager( 7293): found sensor: LGE Gyroscope -Wakeup Secondary, handle=19
D/SensorManager( 7293): found sensor: LGE Gyroscope Uncalibrated -Wakeup Secondary, handle=24
D/SensorManager( 7293): found sensor: LGE Proximity -Non Wakeup Secondary, handle=67
D/SensorManager( 7293): found sensor: LGE Light -Wakeup Secondary, handle=18
D/SensorManager( 7293): found sensor: LGE Pressure -Wakeup Secondary, handle=20
D/SensorManager( 7293): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7293): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7293): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7293): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7293): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7293): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7293): found sensor: LGE Game Rotation Vector Sensor, handle=50
D/SensorManager( 7293): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7293): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7293): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7293): found sensor: Gravity -Wakeup Secondary, handle=60
D/SensorManager( 7293): found sensor: Linear Acceleration -Wakeup Secondary, handle=61
D/SensorManager( 7293): found sensor: Rotation Vector -Wakeup Secondary, handle=62
D/SensorManager( 7293): found sensor: Step Detector -Wakeup Secondary, handle=65
D/SensorManager( 7293): found sensor: Step Counter -Wakeup Secondary, handle=66
D/SensorManager( 7293): found sensor: Game Rotation Vector -Wakeup Secondary, handle=63
D/SensorManager( 7293): found sensor: GeoMagnetic Rotation Vector -Wakeup Secondary, handle=64
D/SensorManager( 7293): found sensor: Orientation -Wakeup Secondary, handle=59
D/SensorManager( 7293): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7293): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7293): found sensor: Motion Accel, handle=46
I/SensorManager( 7293): registerListenerImpl() [Sensor: LGE Step Counter Sensor, Rate: 30000000, SensorEventListener: com.lge.s4u.core.algorithm.detector.sensor.android.StepCounterDetected@27e40711] by com.lge.s4u.core.algorithm.detector.sensor.android.StepCounterDetected.start():84
D/LIA_Informant_CTP_PredictorThread( 7293): run()  - startCallStateReceiver is instantiated!!
D/sensors_hal_SAM( 1280): batch:sensor(android.sensor.step_counter) handle:44 freq:1.000000 report_rate_f:0.003333                        report_rate_Q16:218 batch_rate:218 max:1.000000 min:0.000275
D/sensors_hal_StepCounter( 1280): enable: handle=44, freq=1.000000 report_rate=65536 batch_rate=218                     batched=1 wakeup 0
I/sensors_hal_SAM( 1280): sendEnableReq:sensor(android.sensor.step_counter) Sending enable to svc no:37
D/sensors_hal_Util( 1280): waitForResponse: timeout=1000
D/sensors_hal_StepCounter( 1280): processResp: Received SNS_SAM_PED_ENABLE_RESP_V01
D/sensors_hal_StepCounter( 1280): enable: Received Response: 0
I/sensors_hal_StepCounter( 1280): sendGetReportReq: handle:44
I/LIA_Informant_CTP_StepCounterDetected( 7293): StepCounter sensor available! ==> true and isBatchModeSupported ==> true
D/LIA_Informant_LDBAccessManager( 7293): LDBAccessManager
D/sensors_hal_StepCounter( 1280): processResp: Received SNS_SAM_PED_GET_REPORT_RESP_V01
D/sensors_hal_StepCounter( 1280): processInd: SNS_SAM_PED_GET_REPORT_RESP_V01
I/sensors_hal_StepCounter( 1280): processInd: STEP COUNTER: step is 0, running_total 0 TS:42101668733
D/sensors_hal_Ctx( 1280): poll:polldata:1, sensor:44, type:19, x:0.000000 y:0.000000 z:0.000000
D/sensors_hal_Util( 1280): waitForResponse: timeout=0
D/LIA_Informant_CTP_StepCounterDetected( 7293): currentStep: 0.0
D/LIA_Informant_CTP_StepCounterDetected( 7293): currentStep: 0.0
D/LIA_Informant_CTP_PredictorThread( 7293): createSensorConditionDetector()  - MultipleSensorDetector.start() is called!!
I/LIA_Informant_TaskSession( 7293): SmartMoment start() result: true, process time = 54 msec
I/LIA_Informant_LogTracer( 7293): [Log Tracer - Task State Transition] start(SmartMoment)...... Success
I/LIA_Informant_TaskSession( 7293): enable() - enable state : true
D/LIA_Informant_TaskContext( 7293): runSeesion() succeeded.
D/LIA_Informant_TaskLauncher( 7293): runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap Size : 5
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.informant [key: TermExtraction]
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.s4urecommender [key: S4URecommender]
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.informant [key: UIMAgent]
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.informant [key: Informant]
I/LIA_Service_RemoteSessionManager( 4268): RemoteProxyMap : com.lge.ia.task.informant [key: SmartMoment]
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f258fb14-5c4a-4724-a87f-42e177b4cb27
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f258fb14-5c4a-4724-a87f-42e177b4cb27 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/ActivityManager( 1280): Start proc 7590:com.lge.settings.easy/1000 for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b1009337-1c5e-41c7-b3be-dd08f876b9ad
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b1009337-1c5e-41c7-b3be-dd08f876b9ad / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
I/Activity( 7441): Activity.onPostResume() called 
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 27740ffc-92e1-444b-b834-7b48aa475f14
D/OpenGLRenderer( 7441): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 27740ffc-92e1-444b-b834-7b48aa475f14 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/SplitWindow( 1280): check instance of lgWin Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity}
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 52ec428d-7393-4001-afb9-0ba5819a88c6
V/WindowManager( 1280): Adding window Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity} at 2 of 10 (before Window{3e458f0f u0 Starting com.example.hello})
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 52ec428d-7393-4001-afb9-0ba5819a88c6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
W/chromium( 7441): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 32799bcb-e93d-4f84-bdd1-ebb2c0c28d2b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 32799bcb-e93d-4f84-bdd1-ebb2c0c28d2b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/ActivityManager( 1280): Killing 6549:com.lge.hiddenmenu/1000 (adj 15): empty #22
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
W/ContextImpl( 7561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.lpd.receiver.LPDBootCompletedReceiver.onReceive:42 android.app.ActivityThread.handleReceiver:2701 
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
W/ResourcesManager( 7590): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7590): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 64141475-5e7b-4eb6-a8c8-b4680e8ae087
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 64141475-5e7b-4eb6-a8c8-b4680e8ae087 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3bc70a07-f049-40ba-9a79-d76bd725487e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3bc70a07-f049-40ba-9a79-d76bd725487e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/OpenGLRenderer( 7441): Initialized EGL, version 1.4
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/InputDispatcher( 1280): Focus entered window: Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity}
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/OpenGLRenderer( 7441): Enabling debug mode 0
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/ActivityManager( 1280): Start proc 7615:com.lge.task/u0a20 for broadcast com.lge.task/.database.TasksReceiver
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 57119a5b-8761-41b6-bb70-94581d8a6581
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 57119a5b-8761-41b6-bb70-94581d8a6581 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothPermissionRequest( 7390): onReceive
D/LGBluetoothFeatureConfig( 7390):  get() - isFeatureLoaded : false
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f6271f92-ed41-4c69-84f5-606c892300d1
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f6271f92-ed41-4c69-84f5-606c892300d1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
V/sensors_hal_Light( 1280): processReportInd: 0 0.000000
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2e22a147-f7a8-4b2b-a14e-bea09727a0ae
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2e22a147-f7a8-4b2b-a14e-bea09727a0ae / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/BluetoothManagerService( 1280): Message: 20
D/BluetoothManagerService( 1280): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@242b7e63:true
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/ActivityManager( 1280): Displayed com.example.hello/.MainActivity: +940ms (total +2s704ms)
I/Timeline( 1280): Timeline: Activity_windows_visible id: ActivityRecord{18ed6004 u0 com.example.hello/.MainActivity t53} time:42345
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a549f1df-1fe2-40b4-8635-2c81bd3cac8d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a549f1df-1fe2-40b4-8635-2c81bd3cac8d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c542ba5a-0592-4bfd-8bf5-cfac37a860d7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c542ba5a-0592-4bfd-8bf5-cfac37a860d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 7390): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1ff642a8-b124-4df5-b3c1-33d817a4e60e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1ff642a8-b124-4df5-b3c1-33d817a4e60e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/TasksProvider( 7615): [onCreate]
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
W/BindingManager( 7441): Cannot call determinedVisibility() - never saw a connection for the pid: 7441
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/MusicBrowser( 4588): [MediaPlaybackService.java:2028:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 4588): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 4588): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 4588): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 4588): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
I/Timeline( 7441): Timeline: Activity_idle id: android.os.BinderProxy@27e40711 time:42373
D/bt_hwcfg( 4484): hw_config_cback state=6
,I/MusicBrowser( 4588): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/chromium( 7441): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/ActivityManager( 1280): Start proc 7641:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
I/ActivityManager( 1280): Killing 6457:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
V/sensors_hal_Light( 1280): processReportInd: 0 0.000000
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/JsMessageQueue( 7441): Set native->JS mode to OnlineEventsBridgeMode
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
E/AndroidProtocolHandler( 7441): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4484): hw_config_cback state=6
,D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 4484): hw_config_cback state=6
,V/sensors_hal_Light( 1280): processReportInd: 20000 2.000000
D/sensors_hal_Ctx( 1280): poll:polldata:1, sensor:1, type:5, x:2.000000 y:0.000000 z:0.000000
D/sensors_hal_Util( 1280): waitForResponse: timeout=0
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d4a43d35-4df8-45ad-b61c-eda0af248a43
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d4a43d35-4df8-45ad-b61c-eda0af248a43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/TasksReceiver( 7615): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.task/.database.TasksReceiver (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b8208147-f5ec-4164-8055-a2468ab10f20
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b8208147-f5ec-4164-8055-a2468ab10f20 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/TasksReceiver( 7615): [onReceive] WakeLock new : TasksReceiver, ReferenceCounted = true
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bd4db121-0001-4931-89ef-88b98a345bd6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bd4db121-0001-4931-89ef-88b98a345bd6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/TasksReceiver( 7615): [onReceive] WakeLock acquire : TasksReceiver
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/TasksReceiver( 7615): [onReceive] android.intent.action.BOOT_COMPLETED
,D/AsyncAlarmTask( 7615): [AsyncAlarmTask]
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ec633e7c-a5f5-44af-8f55-576dc760628f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ec633e7c-a5f5-44af-8f55-576dc760628f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/TasksReceiver( 7615): [onReceive] WakeLock release : TasksReceiver_Provider
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5904f973-cb93-457e-ace8-f5c17155a91b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5904f973-cb93-457e-ace8-f5c17155a91b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/jxcore_app_log( 7441): JniHelper::setJavaVM(0xf489d200), pthread_self() = -429684608
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 41f56ba5-fe4e-4635-92f8-e32f4b1dcc33
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 41f56ba5-fe4e-4635-92f8-e32f4b1dcc33 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/AsyncAlarmTask( 7615): [doInBackground] cursor.getCount() = 0
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0f9b97a4-1484-4249-974c-965230f18910
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0f9b97a4-1484-4249-974c-965230f18910 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/SmsReceiverService( 6389): call onStartCommand
I/SmsReceiverService( 6389): getEnableForeGroundService = false
I/[SystemUI]LGBootReceiver( 3398): onReceive = android.intent.action.BOOT_COMPLETED
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e1cce721-867f-4e81-bb7b-0da00da8de38
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e1cce721-867f-4e81-bb7b-0da00da8de38 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/MmsConfig( 6389): isNotAllowedSms: currentUser:0
D/MmsConfig( 6389): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 6389): isUserMode:false
D/SmsReceiverService( 6389): handleMessage isUserMode:false
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/[SystemUI]LGPowerUI( 3398): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 3398): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 3398): got ACTION_STICKY_BOOT_COMPLETED
D/StoreModeReceiver( 7390): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 7390): sim state :null
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1a58bab3-b209-4d0d-b3cc-fd9746b13604
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1a58bab3-b209-4d0d-b3cc-fd9746b13604 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
W/ResourcesManager( 6389): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/StoreModeReceiver( 7390): Back LED don't supported.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 23e25e28-2482-444d-a297-1e28d403844e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 23e25e28-2482-444d-a297-1e28d403844e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a3134ff3-9cdf-48e0-ad40-d6f420a5ce40
V/SettingsProvider( 1280): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a3134ff3-9cdf-48e0-ad40-d6f420a5ce40 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/SettingsProvider( 1280): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/SettingsProvider( 1280): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1280): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1280): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1280): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
W/jxcore-log( 7441): Initializing JXcore engine
W/jxcore-log( 7441): JXcore engine is ready
V/SmsReceiverService( 6389): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
,V/SettingsProvider( 1280): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/sensors_hal_Light( 1280): processReportInd: 50000 5.000000
D/sensors_hal_Ctx( 1280): poll:polldata:1, sensor:1, type:5, x:5.000000 y:0.000000 z:0.000000
D/sensors_hal_Util( 1280): waitForResponse: timeout=0
V/SettingsProvider( 1280): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 673d67a7-2d43-4961-b400-d3ed5b8e61e8
,V/SettingsProvider( 1280): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 673d67a7-2d43-4961-b400-d3ed5b8e61e8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/bt_hwcfg( 4484): bt vendor lib: set UART baud 115200
D/Mms     ( 6389): Cache dir: /data/data/com.android.mms/cache/imgcache
V/SettingsProvider( 1280): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
D/bt_hwcfg( 4484): Settlement delay -- 100 ms
I/bt_hwcfg( 4484): Setting fw settlement delay to 100 
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/SettingsProvider( 1280): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 7390): SystemProperty Default brightness value [0-255] : 145
D/StoreModeReceiver( 7390): Default brightness[0-255] : 145
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3132b7ca-fa19-4d73-9705-2cb57fbec8df
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3132b7ca-fa19-4d73-9705-2cb57fbec8df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8fbc4b27-668a-45d0-b0d4-fe7617f7a9a0
,W/ResourcesManager( 7390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8fbc4b27-668a-45d0-b0d4-fe7617f7a9a0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/SmsReceiverService( 6389): getEnableForeGroundService = false
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/StoreModeReceiver( 7390): Default Screen off timeout value : 30000
D/StoreModeReceiver( 7390): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 7390): Default brightness Mode [0/1] : 0
,D/StoreModeReceiver( 7390): Set MaxBrightness : 255
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1182da2f-bc57-43c4-910b-613712644e30
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1182da2f-bc57-43c4-910b-613712644e30 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/PhoneInterfaceManager( 4118): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0de30ba8-3b34-491e-86a1-f1c530b51d64
D/StoreModeReceiver( 7390): getPhoneNumber is empty
D/StoreModeReceiver( 7390): go to StoreModeCheck()
D/StoreModeReceiver( 7390): isStoremode not null
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0de30ba8-3b34-491e-86a1-f1c530b51d64 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/PhoneInterfaceManager( 4118): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 48df9194-53e8-4edc-954b-96b4e091b2fc
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 48df9194-53e8-4edc-954b-96b4e091b2fc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/SettingsProvider( 1280): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c56e0e67-3470-499c-9b17-142622005681
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c56e0e67-3470-499c-9b17-142622005681 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/jxcore-log( 7441): Starting JXcore engine
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/StoreModeReceiver( 7390): product_name : p1_global_com
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d19c611a-6540-426e-9814-f39d7cbf3168
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d19c611a-6540-426e-9814-f39d7cbf3168 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/StoreModeReceiver( 7390): Store mode start!
,V/SettingsProvider( 1280): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
,V/SettingsProvider( 1280): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a61d74fd-f974-4b1b-b660-4ada594333e2
D/PowerManagerServiceEx( 1280): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=148769 (in 106143 ms)
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a61d74fd-f974-4b1b-b660-4ada594333e2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/StoreModeReceiver( 7390): setBrightness() : NoMultiALC=255
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ContextImpl( 7390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.StoreModeReceiver.sendBroadcast:480 com.android.settings.StoreModeReceiver.setMode:452 
V/SettingsProvider( 1280): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
,D/SettingsProvider( 1280): Set screen_off_timeout in entry value : 120000
V/SettingsProvider( 1280): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider( 1280): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
,V/SettingsProvider( 1280): call_put(system:Retail_Mode=1) for 0 calling package = com.android.settings
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b9bec2d5-cc2b-4662-a72c-2711fe638f2b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b9bec2d5-cc2b-4662-a72c-2711fe638f2b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a608db5e-bafe-4ae9-909e-afed114d9b9e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a608db5e-bafe-4ae9-909e-afed114d9b9e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/PowerManagerService( 1280): updateBatteryLowStatus : lowPowerModeEnabled = false, autoLowPowerModeConfigured = false
D/PowerManagerServiceEx( 1280): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=148769 (in 106128 ms)
,I/PowerManagerServiceEx( 1280): [WiseScreen] mWiseScreenEnable = 0
I/PowerManagerServiceEx( 1280): [WiseScreen] mWirelessChargingEnable = 0
D/LPWGController( 1280): [updateSettings] mKnockOnSetting = true, mKnockCodeSetting = false, tapcount = 0, mIsSame1st2ndTap =false
D/PowerManagerServiceEx( 1280): setRetailMode, Mode : 1
D/PowerManagerServiceEx( 1280): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=148769 (in 106124 ms)
D/SettingBootReceiver( 7390): onReceive
D/SettingBootReceiver( 7390): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 7390): boot completed process end time=1
D/SettingBootReceiver( 7390): setStyle()
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 08c542e6-6376-481f-be62-611270405932
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 08c542e6-6376-481f-be62-611270405932 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/SettingBootReceiver( 7390): SettingStyle=1
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2b91e03f-7dbf-4be9-888c-dc0f20376a68
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2b91e03f-7dbf-4be9-888c-dc0f20376a68 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/SettingBootReceiver( 7390): setAccountMenu()
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/TAG     ( 7390): setKidsMode
D/TAG     ( 7390): mIsOwner, setKidsMode
D/SettingBootReceiver( 7390): setAccountMenu()
,D/SettingBootReceiver( 7390): timezoneID is null
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8a3a7f6c-76a5-4731-ba75-430b3844617f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8a3a7f6c-76a5-4731-ba75-430b3844617f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/SettingBootReceiver( 7390): disable au
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 65bb3c86-a9db-4604-a1c9-d9fe50ef6790
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 65bb3c86-a9db-4604-a1c9-d9fe50ef6790 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/TAG     ( 7390): disable WirelessSettingsActivity
I/TAG     ( 7390): disable SKTPhoneMode
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5afde72d-f0d8-468e-8ea1-b1a9c2e76738
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5afde72d-f0d8-468e-8ea1-b1a9c2e76738 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Utils   ( 7390): Exception config_folder_phone
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b8d79fa1-9a6c-4130-9053-79db6eb1747d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b8d79fa1-9a6c-4130-9053-79db6eb1747d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ddc94ad9-b03a-476f-9dfe-e5807eb53531
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ddc94ad9-b03a-476f-9dfe-e5807eb53531 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/jxcore-log( 7441): Platform android
W/jxcore-log( 7441): 
W/jxcore-log( 7441): Process ARCH arm
W/jxcore-log( 7441): 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 664cfe23-0b15-46f7-bb60-7cb96f1bd038
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 664cfe23-0b15-46f7-bb60-7cb96f1bd038 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ce6e3e2a-4afe-4b30-b4a8-a3e3d19a896e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ce6e3e2a-4afe-4b30-b4a8-a3e3d19a896e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 4484): hw_config_cback state=2
,D/UsbSettingsControl( 7390): [AUTORUN] setTetherStatus() : status=false
D/SettingBootReceiver( 7390): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 7390): [AUTORUN] sys.usb.config = ptp_only,adb
D/SettingBootReceiver( 7390): [AUTORUN] sys.usb.state = ptp_only,adb
D/SettingBootReceiver( 7390): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/SettingBootReceiver( 7390): [Nightmode] Enter receiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c1d2622f-b7fc-4ee5-8ba9-f25cce3faf02
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c1d2622f-b7fc-4ee5-8ba9-f25cce3faf02 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/mission ( 7390): isglobe in receiver false
I/ApnSelectReceiver( 7390): ApnSelectReceiver onReceive : android.intent.action.BOOT_COMPLETED
I/ApnSelectReceiver( 7390): persist.sys.cupss.changed is : 0
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/mission ( 7390):  current numeric is 
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 4484): hw_config_cback state=7
I/bt_hwcfg( 4484): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 4484): Setting local bd addr to F8:95:C7:87:3C:51
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d6ac4177-228c-4ca3-96fe-aa24c4bfc4a2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d6ac4177-228c-4ca3-96fe-aa24c4bfc4a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/jxcore-log( 7441): JXcore Cordova bridge is ready!
I/jxcore-log( 7441): 
,W/jxcore-log( 7441): JXcore engine is started
,D/StrictMode( 7641): StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7641): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7641): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7641): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
D/StrictMode( 7641): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
D/StrictMode( 7641): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1072)
D/StrictMode( 7641): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 7641): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 7641): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7641): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
D/StrictMode( 7641): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(Activ,ityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 7641): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 7641): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7641): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
D/StrictMode( 7641): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7641): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7641): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7641): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7641): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7641): 	at com.google.r.k.d(PG:1187)
D/StrictMode( 7641): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 7641): 	at com.google.w.a.a.do.<init>(PG:23)
D/StrictMode( 7641): 	at com.google.w.a.a.do.a(PG:405)
D/StrictMode( 7641): 	at com.google.r.v.a(PG:1161)
D/StrictMode( 7641): 	at com.google.r.y.a(PG:2188)
D/StrictMode( 7641): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7641): 	at com.google.r.e.b(PG:15188)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMo,de( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7641): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7641): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7641): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7641): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7641): 	at com.google.r.k.d(PG:1187)
D/StrictMode( 7641): 	at com.google.r.k.c(PG:18147)
D/StrictMode( 7641): 	at com.google.r.k.d(PG:583)
D/StrictMode( 7641): 	at com.google.w.a.a.do.<init>(PG:40)
D/StrictMode( 7641): 	at com.google.w.a.a.do.a(PG:405)
D/StrictMode( 7641): 	at com.google.r.v.a(PG:1161)
D/StrictMode( 7641): 	at com.google.r.y.a(PG:2188)
D/StrictMode( 7641): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7641): 	at com.google.r.e.b(PG:15188)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7641): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7641): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7641): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
D/StrictMode( 7641): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
D/StrictMode( 7641): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1238)
D/StrictMode( 7641): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:192)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7641): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7641): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7641): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7641): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7641): 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
D/StrictMode( 7641): 	at java.io.File.lastModified(File.java:571)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7641): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7641): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7641): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7641): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7641): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/bt_hwcfg( 4484): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 4484): hw_config_cback state=8
I/bt_hwcfg( 4484): vendor lib fwcfg completed
I/bt-btif ( 4484): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 4484): btu_task received preload complete event
I/        ( 4484): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 4484): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 4484): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 4484): BTE_InitTraceLevels -- TRC_PROTOCOL,0
I/ActivityManager( 1280): Start proc 7684:com.lge.voicerecorder/u0a41 for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver
I/ActivityManager( 1280): Killing 6795:com.lge.eodengine/1000 (adj 15): empty #22
E/jxcore-log( 7441): >> LGE-LG-H815
E/jxcore-log( 7441): 
I/jxcore-log( 7441): Total memory 2968948736
I/jxcore-log( 7441): 
I/jxcore-log( 7441): Free memory 88543232
I/jxcore-log( 7441): 
I/jxcore-log( 7441): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7441): 
I/jxcore-log( 7441): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7441): 
I/jxcore-log( 7441): userPath [ 'www', 'www' ]
I/jxcore-log( 7441): 
I/jxcore-log( 7441): Size 1440 2392
I/jxcore-log( 7441): 
,I/jxcore-log( 7441): Screen Brightness 255
I/jxcore-log( 7441): 
E/jxcore-log( 7441): Dummy Error Log.
E/jxcore-log( 7441): 
W/ActivityThread( 7641): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/libc-netbsd( 7641): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7641): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/com.google.a.a.b.d.a( 7641): Application name is not set. Call Builder#setApplicationName.
D/libc-netbsd( 7641): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7641): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  461): [LG DATA] No such appUid: 10119
D/DnsProxyListener(  461): App 10119 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  461): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  461): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  461): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  461): res_queryN name = xxxxx, class = 1, type = 1
D/BluetoothManagerService( 1280): Message: 20
D/BluetoothManagerService( 1280): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6f74af:true
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/AuthorizationBluetoothService( 5205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1a792a83-e47d-4c90-a2a2-4937c8dfcafb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1a792a83-e47d-4c90-a2a2-4937c8dfcafb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c74543a1-23ee-4138-851d-816543e2f882
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c74543a1-23ee-4138-851d-816543e2f882 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4190378c-4811-410a-bbf1-4c014a1380f0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4190378c-4811-410a-bbf1-4c014a1380f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/NotificationManager( 7641): com.google.android.apps.maps: cancel(10436) by com.google.android.apps.maps
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 287b97d5-2c50-4bee-bf54-890c05d714f3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 287b97d5-2c50-4bee-bf54-890c05d714f3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a0ff4247-5118-4d66-90eb-7df8baa0f1fe
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a0ff4247-5118-4d66-90eb-7df8baa0f1fe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c858f754-bfc3-44f5-8d8e-5794e530e624
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c858f754-bfc3-44f5-8d8e-5794e530e624 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c1750b9a-5a54-4cc3-944a-fad793c4c259
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c1750b9a-5a54-4cc3-944a-fad793c4c259 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/libc-netbsd(  461): res_queryN name = xxxxx succeed
,I/System.out( 7641): propertyValue:false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8f8092b3-c00f-4529-9fa0-ccee6a777255
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8f8092b3-c00f-4529-9fa0-ccee6a777255 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1af933bf-8670-451c-87e8-7c1b7ae9486a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1af933bf-8670-451c-87e8-7c1b7ae9486a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a275957e-facb-4980-a59f-1e9453f4cafa
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a275957e-facb-4980-a59f-1e9453f4cafa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a6a5fcb3-8518-4985-8a0c-7ad44e963154
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a6a5fcb3-8518-4985-8a0c-7ad44e963154 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e74ed1c1-8ac9-40ce-88c2-d6a654574c60
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e74ed1c1-8ac9-40ce-88c2-d6a654574c60 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/BluetoothOppNotification( 4484): new notify threadi!
V/BluetoothOppNotification( 4484): send delay message
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 55d6b5cf-0708-4575-8ef0-65a5f6e1ff0d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 55d6b5cf-0708-4575-8ef0-65a5f6e1ff0d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@18a77a9d on behalf of 
,V/BluetoothOppNotification( 4484): mUpdateCompleteNotification = true
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5a73105e-90d9-4e0b-93a4-2d5eb53d45bb
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5a73105e-90d9-4e0b-93a4-2d5eb53d45bb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/VRBookmarkProvider( 7684): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5e812aab-280e-4435-b506-ed5a3f9f9580
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5e812aab-280e-4435-b506-ed5a3f9f9580 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/VRBookmarkProvider( 7684): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 99c097ff-6324-4404-8a7b-36ad2e9099ba
V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 99c097ff-6324-4404-8a7b-36ad2e9099ba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/VRBookmarkProvider( 7684): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@39193b12 on behalf of 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 44ac4a1b-f7df-434f-9acb-340a4c8bf53a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 44ac4a1b-f7df-434f-9acb-340a4c8bf53a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/VRBootCompletedReceiver( 7684): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/BluetoothOppNotification( 4484): outbound: succ-0  fail-0
,I/NotificationManager( 4484): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 4484): outbound notification was removed.
,V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cf6e9aa1-8414-4f1f-9735-4f1ed185f03b
D/VRBootCompletedReceiver( 7684): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cf6e9aa1-8414-4f1f-9735-4f1ed185f03b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@1a9d2e3 on behalf of 
,V/BluetoothOppNotification( 4484): inbound: succ-0  fail-0
I/ActivityManager( 1280): Killing 6911:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #22
,I/NotificationManager( 4484): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,V/BluetoothOppNotification( 4484): inbound notification was removed.
,V/BluetoothOppProvider( 4484): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 4484): created cursor android.database.sqlite.SQLiteCursor@322224e0 on behalf of 
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/LAlarm  ( 1280): Service started flags 0 startId 3
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bc6cabce-23cf-44cf-be8c-8e683e2a6511
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bc6cabce-23cf-44cf-be8c-8e683e2a6511 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LGBootCompleteReceiver( 4118): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 4118): setContext: android.app.ReceiverRestrictedContext@7fbae48
D/ConfigUtils( 4118): setUsimOperator() : card operator = 
D/ConfigUtils( 4118): setUsimOperator() : result = null
D/ConfigUtils( 4118): setUsimOperator() : simOperator = 
D/ConfigUtils( 4118): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 4118): setSupportedUsimMobilityForVoLTE() : false
I/ConfigUtils( 4118): getNoiseSuppressionDefaultValueOff() : true
D/LGBootCompleteReceiver( 4118): ACTION_BOOT_COMPLETED - NOISE_SUPPRESSION_KEY : false
V/AudioFlinger(  466): setParameters(): io 0, keyvalue ns_enable=OFF, calling pid 4118
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1f14cdd0-97be-4b45-9914-f08fc4b3c8d2
V/SRS_Proc(  466): ParamSet string: ns_enable=OFF
D/audio_hw_primary(  466): adev_set_parameters: enter: ns_enable=OFF
V/voice   (  466): voice_set_parameters: enter: ns_enable=OFF
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: enter: ns_enable=OFF
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: exit
V/voice   (  466): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  466): LGE_platform_set_parameters: enter: ns_enable=OFF
V/msm8974_platform(  466): platform_set_parameters: enter: ns_enable=OFF
V/msm8974_platform(  466): platform_set_parameters: exit with code(0)
V/platform_param(  466): lge_platform_factory_set_parameters: enter: ns_enable=OFF
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1f14cdd0-97be-4b45-9914-f08fc4b3c8d2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/audio_hw_extn(  466): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  466): adev_set_parameters: exit with code(0)
D/LGBootCompleteReceiver( 4118): ACTION_BOOT_COMPLETED - VOICE_CLARITY_KEY : false
V/AudioFlinger(  466): setParameters(): io 0, keyvalue voice_clarity=off, calling pid 4118
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2e924b26-5222-4f81-a202-762c1e34be4c
V/SRS_Proc(  466): ParamSet string: voice_clarity=off
D/audio_hw_primary(  466): adev_set_parameters: enter: voice_clarity=off
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2e924b26-5222-4f81-a202-762c1e34be4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/voice   (  466): voice_set_parameters: enter: voice_clarity=off
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: enter: voice_clarity=off
V/compress_voip(  466): voice_extn_compress_voip_set_parameters: exit
V/voice   (  466): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  466): LGE_platform_set_parameters: enter: voice_clarity=off
V/msm8974_platform(  466): platform_set_parameters: enter: voice_clarity=off
V/msm8974_platform(  466): platform_set_parameters: exit with code(0)
V/platform_param(  466): lge_platform_factory_set_parameters: enter: voice_clarity=off
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ef3f3e5c-b8d3-4cad-b358-1b2cb4884687
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ef3f3e5c-b8d3-4cad-b358-1b2cb4884687 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - dfd63267-835a-4eda-a321-3bee2c8b0b88
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - dfd63267-835a-4eda-a321-3bee2c8b0b88 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/audio_hw_extn(  466): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  466): adev_set_parameters: exit with code(0)
D/LGBootCompleteReceiver( 4118): onReceive : updateCallrejectNotify rejectCallOption : 1
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a94f9dab-0d80-46d2-b5ff-7278318a3d4b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a94f9dab-0d80-46d2-b5ff-7278318a3d4b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/CallRejectInfoToNotify( 4118): update : tPhoneMode : false
I/NotificationManager( 4118): com.android.phone: cancel(2131493555) by com.android.phone
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/PhoneApp( 4118): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/52
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4dee7d54-b854-40ef-b8b5-907c814bc96b
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4dee7d54-b854-40ef-b8b5-907c814bc96b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 4311): [LGUnreadLgeEmailsBadge.java:86:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 4311): [LGUnreadLgeEmailsBadge.java:87:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]NumberBadge.LGBroadCastBadge( 4311): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 4311): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 4311): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,D/libc-netbsd( 7641): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7641): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager( 1280): Start proc 7711:com.android.managedprovisioning/u0a43 for broadcast com.android.managedprovisioning/.BootReminder
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 31ad7790-e021-4968-87de-a06f51f364de
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 31ad7790-e021-4968-87de-a06f51f364de / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 87b243b2-e8d3-455c-868c-bd0320642af1
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 87b243b2-e8d3-455c-868c-bd0320642af1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 98226e59-5a46-4292-a127-573e15c4338c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 98226e59-5a46-4292-a127-573e15c4338c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 81cddcee-bbfd-4ad8-97bd-faa0b5301fef
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 81cddcee-bbfd-4ad8-97bd-faa0b5301fef / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b03ef931-562d-405f-b5d0-ae590e52163b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b03ef931-562d-405f-b5d0-ae590e52163b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4eb008ee-9019-49cc-b88a-fb85c90f6601
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4eb008ee-9019-49cc-b88a-fb85c90f6601 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a201ffd3-d058-4684-8e23-9745806819de
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a201ffd3-d058-4684-8e23-9745806819de / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 927d41e6-ace1-435a-b6a1-b1430777d4dc
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 927d41e6-ace1-435a-b6a1-b1430777d4dc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2bc2feae-76de-41b3-96cb-29aef1d82d46
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2bc2feae-76de-41b3-96cb-29aef1d82d46 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6f350c72-efc6-4e61-8ca9-128590ada4c3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6f350c72-efc6-4e61-8ca9-128590ada4c3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d025c2dc-2403-4c58-8afb-b7044c47e6f0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d025c2dc-2403-4c58-8afb-b7044c47e6f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7e755399-2d1e-46f7-b555-ac5717c782a5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7e755399-2d1e-46f7-b555-ac5717c782a5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 62861828-0857-4aee-9bca-b3c50b3ba7db
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 62861828-0857-4aee-9bca-b3c50b3ba7db / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ed6f533b-2544-4fa4-9f59-0d7e78288932
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ed6f533b-2544-4fa4-9f59-0d7e78288932 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 596750fc-8a2c-4df2-aedf-9bbdbd307a46
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 596750fc-8a2c-4df2-aedf-9bbdbd307a46 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 94f48549-6edc-479c-bbdd-8817250b778f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 94f48549-6edc-479c-bbdd-8817250b778f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 31b72c81-9a22-4b2b-a6aa-a47b47514c93
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 31b72c81-9a22-4b2b-a6aa-a47b47514c93 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7732:com.lge.cloudhub/u0a73 for broadcast com.lge.cloudhub/.service.CloudHubReceiver
,I/ActivityManager( 1280): Killing 6940:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,I/art     (  498): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 139us total 13.254ms
,I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 4484): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,I/GKI_LINUX( 4484): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 4484): warning : media task started media_task_refcnt 1 
E/bt-btif ( 4484): Calling BTA_HhEnable
E/bt-btif ( 4484): btif_storage_get_adapter_property service_mask:0x1200c8
I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 4484): Address is:F8:95:C7:87:3C:51
,D/BT_PROF_AUDIO( 4484): created moving average (N=100)
D/BT_PROF_AUDIO( 4484): reset rate average
W/bt-btif ( 4484): overflow 0, enter 0, exit 0
,W/bt-smp  ( 4484): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4484): Plain text(LSB ~ MSB) = 4d d0 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4484): Encrypted text(LSB ~ MSB) = ac ac 02 48 c9 d9 37 c9 a2 70 77 ef fd 04 28 23 
W/bt-btm  ( 4484): Stopping oneshot timer
,W/bt-smp  ( 4484): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4484): Plain text(LSB ~ MSB) = 58 62 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4484): Encrypted text(LSB ~ MSB) = 49 50 72 f1 1c f7 45 6e ff 38 a0 aa c3 34 e3 36 
,W/bt-smp  ( 4484): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4484): Plain text(LSB ~ MSB) = 18 fb 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4484): Encrypted text(LSB ~ MSB) = f2 9b b5 3d d4 6b 60 b1 9f 69 66 49 8f 2c 66 6e 
,W/bt-smp  ( 4484): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4484): Plain text(LSB ~ MSB) = c7 6b 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4484): Encrypted text(LSB ~ MSB) = f0 1e e3 f6 85 11 66 fc d8 ea 1e 7d d6 42 49 ad 
,W/bt-smp  ( 4484): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
,W/bt-smp  ( 4484): Plain text(LSB ~ MSB) = 68 c9 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4484): Encrypted text(LSB ~ MSB) = 1e 68 15 af a5 b1 d4 d9 5e 4c 39 f8 60 be 72 0d 
,I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 117us total 12.550ms
,I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 121us total 12.170ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 278a99db-4070-4289-8a8f-698f63a66bda
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 278a99db-4070-4289-8a8f-698f63a66bda / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterProperties( 4484): Name is: G4-1
D/BluetoothAdapterProperties( 4484): Scan Mode:20
D/BluetoothAdapterProperties( 4484): Discoverable Timeout:120
D/BluetoothManagerService( 1280): Bluetooth Adapter name changed to G4-1
D/BluetoothManagerService( 1280): store name and address
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothManagerService( 1280): Stored Bluetooth name: G4-1
D/BluetoothAdapterProperties( 4484): Adding bonded device:10:D3:8A:FB:85:D4
I/bt-btif ( 4484): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4484): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0c7ef734-9d1d-4d30-b555-5185e961d058
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0c7ef734-9d1d-4d30-b555-5185e961d058 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 40
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_INIT_PRIORITIES
,I/LGRemoteDevicePropertySetting( 4484): [BTUI] remoteDeviceSetProperties
I/LGRemoteDevicePropertySetting( 4484): [BTUI] Get AOSP HeadsetService
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 004e7126-d828-45f2-8db7-87cc51833ec6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 004e7126-d828-45f2-8db7-87cc51833ec6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 84bb5c65-45fe-43b8-a2d4-f796ea2c0556
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 84bb5c65-45fe-43b8-a2d4-f796ea2c0556 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,E/BluetoothRemoteDevices( 4484): devicePropertyChangedCallback: mDeviceTrust: false
E/bt-btif ( 4484): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 4484): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/bt_vendor( 4484): op for 2
D/bt_vendor( 4484): op for 6
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
E/bt-btif ( 4484): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 4484): BTA_JvEnable
E/bt-btif ( 4484): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 4484): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 4484): init_hci_slots(L136): in
D/IOP_DB_BT( 4484): db_open: file /etc/bluetooth/iop_bt.db
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - eeeca687-17ba-4496-8dfd-f9de2ddbfcbf
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - eeeca687-17ba-4496-8dfd-f9de2ddbfcbf / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/IOP_DB_BT( 4484): db_open: db_open : handle 3723003960l, read 11677 bytes onto local cache
D/IOP_DB_BT( 4484): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 4484): db_query: result 1
I/        ( 4484): iop_db_open: iop_db_open status 0
E/bt-btif ( 4484): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 4484): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 4484): bta_pan_co_init
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/bte_conf( 4484): Device ID record 1 : primary
D/bte_conf( 4484):   vendorId            = 00c4
D/bte_conf( 4484):   vendorIdSource      = 0001
D/bte_conf( 4484):   product             = 13a1
D/bte_conf( 4484):   version             = 1000
D/bte_conf( 4484):   clientExecutableURL = 
D/bte_conf( 4484):   serviceDescription  = 
D/bte_conf( 4484):   documentationURL    = 
D/bte_conf( 4484): bte_load_did_conf no section named DID2.
I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 4484): btif_hf_upstreams_evt: wrong handle = 2670 
I/bt-btif ( 4484): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 4484): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 4484): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4484): ScanMode =  20
D/BluetoothAdapterProperties( 4484): State =  11
D/BluetoothAdapterProperties( 4484): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 4484): Setting state to 12
I/BluetoothAdapterState( 4484): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(221810696)( 4484): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService( 1280): Message: 60
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1280): Broadcasting onBluetoothStateChange(true) to 8 receivers.
I/BluetoothAdapterState( 4484): Entering On State
D/BluetoothA2dp( 1280): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 4484): Entering On State from state = 11
D/OppService( 4484): onOpcStateChange()
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 611782dd-1b85-4ad4-a0a7-65ea50c18137
I/bt-btif ( 4484): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 4484): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 4484): Recieved MESSAGE_OPC_ENABLE
D/OppService( 4484): onOpsStateChange() :0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 611782dd-1b85-4ad4-a0a7-65ea50c18137 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LGBluetoothFeatureConfig( 4484): isPrivacyLogsEnabled : true
D/OppService( 4484): Recieved MESSAGE_OPS_ENABLE
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothAdapterService(221810696)( 4484): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(221810696)( 4484): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 4484): [BTUI] autoConnect() : not allowed
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothPanServiceJni( 4484): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_properties_cb
D/LGBluetoothServiceAdapter( 4484): [BTUI] OnState
D/LGBluetoothServiceAdapter( 4484): [BTUI]         global_name: G4-1
,D/BluetoothAdapterProperties( 4484): Scan Mode:21
,D/LGBluetoothServiceAdapter( 4484): [BTUI]         local_name: G4-1
I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothAdapterService(221810696)( 4484): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(221810696)( 4484): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 4484): [BTUI] autoConnect() : not allowed
D/BluetoothAdapterProperties( 4484): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 4484): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5186bb4b-0567-4d4e-a673-4e6d4c0999be
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5186bb4b-0567-4d4e-a673-4e6d4c0999be / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothHeadset( 4684): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1280): Creating new ProfileServiceConnections object for profile: 1
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 04f36d3f-c48d-45d5-8f07-10212d056e69
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 04f36d3f-c48d-45d5-8f07-10212d056e69 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothHeadset( 4118): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4484): onBluetoothStateChange: up=true
D/BluetoothHeadset( 4118): onBluetoothStateChange: up=true
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e22589bd-a788-4404-b626-cf8fc4aaee80
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e22589bd-a788-4404-b626-cf8fc4aaee80 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothHeadset( 4118): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1280): onBluetoothStateChange: up=true
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothA2dp( 4684): onBluetoothStateChange: up=true
D/bt_h4   ( 4484): vendor lib postload completed
E/BluetoothManagerService( 1280): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1280): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 4057): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BleQmManagerService( 4057): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 4057): Message: 1
D/LGBluetoothAPIService( 4057): MESSAGE_BOOT_COMPLETED
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4092a9bd-3a85-4262-aa6c-aa824a29c1c2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4092a9bd-3a85-4262-aa6c-aa824a29c1c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothManagerService( 1280): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1280): Message: 40
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/[SystemUI]QuickSettingsHandler( 3398): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 3398): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,I/LGBluetoothAPIService( 4057): [BTUI] LGBluetoothAPIService Binding Success
,I/BluetoothMapService( 4484): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 4484): STATE_ON
V/BluetoothPbapReceiver( 4484): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 4484): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4484): ***********state = 12
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bba919cd-b828-4cf9-a1fe-d11eeeb473a2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bba919cd-b828-4cf9-a1fe-d11eeeb473a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ContextImpl( 7390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a44054ce-270b-4e36-93cc-84c22e4a9bca
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a44054ce-270b-4e36-93cc-84c22e4a9bca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,I/jxcore-log( 7441): getBuffer is called!!!!
I/jxcore-log( 7441): 
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/LIA_SmartSetting(4.50.6)_LogCore( 7476): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7476): onReceive state= 12
D/LGBluetoothAPIServer( 4484): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 4484): [BTUI] onBind()
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): selection= recipe_slug = "arrive_home_bluetooth"
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 80e3e563-c2ae-468e-b3c5-304d3025b210
V/BluetoothMapService( 4484): Handler(): got msg=1
D/LGBluetoothAPIService( 4057): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 4057): Message: 100
D/LGBluetoothAPIService( 4057): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 4484): Map Service startRfcommSocketListener
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 80e3e563-c2ae-468e-b3c5-304d3025b210 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothMapMasInstance( 4484): MAS initSocket()
D/BluetoothMapMasInstance( 4484):   masId = 00
D/BluetoothMapMasInstance( 4484):   msgTypes = 0e
D/BluetoothMapMasInstance( 4484):   masName = SMS/MMS
D/BluetoothMapMasInstance( 4484):   SDP string = 000eSMS/MMS
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothManagerService( 1280): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ceca4459-dae0-48ce-b519-53c970b9ec00
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ceca4459-dae0-48ce-b519-53c970b9ec00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/BluetoothAdapter( 4484): getBluetoothService() called with no BluetoothManagerCallback
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/bt-btif ( 4484): BTA_JvCreateRecordByUser
I/bt-btif ( 4484): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 4484): [BTUI] createSocketChannel FD=86 mFd=0
V/BluetoothMapMasInstance( 4484): Succeed to create listening socket 
D/BluetoothMapMasInstance( 4484): Accepting socket connection...
,D/LocalBluetoothProfileManager( 7390): Adding local A2DP profile
,D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): status= 0
D/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onUpdate Bluetooth on
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d8e78793-325e-4aa5-ac8d-228a603d0367
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d8e78793-325e-4aa5-ac8d-228a603d0367 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
V/BluetoothPbapService( 4484): Pbap Service onCreate
V/BluetoothPbapService( 4484): Starting PBAP service
D/BluetoothManagerService( 1280): Message: 30
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/LGBluetoothPbapAdapter( 4484): [BTUI] getInstance : create
V/BluetoothPbapService( 4484): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 4484): state: 12
D/LGBluetoothDeviceModeControllManager( 4484): [BTUI] checkDeviceModeAndSet, sinkMode : false
V/BluetoothPbapService( 4484): Handler(): got msg=1
,V/BluetoothPbapService( 4484): Pbap Service startRfcommSocketListener
,D/LocalBluetoothProfileManager( 7390): Adding local HEADSET profile
V/BluetoothPbapService( 4484): Pbap Service initSocket
D/BluetoothManagerService( 1280): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService( 1280): Message: 30
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a0af8b25-cbbc-4a59-8051-507fc0e9b60d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a0af8b25-cbbc-4a59-8051-507fc0e9b60d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/BluetoothAdapter( 4484): getBluetoothService() called with no BluetoothManagerCallback
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_SmartSetting(4.50.6)_Recommender( 7476): onStatusChanged value= Bluetooth on
,D/BluetoothManagerService( 1280): Message: 30
,I/bt-btif ( 4484): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 4484): [BTUI] createSocketChannel FD=88 mFd=86
I/bt-btif ( 4484): BTA_JvRfcommStartServer
V/BluetoothPbapService( 4484): Succeed to create listening socket 
V/BluetoothPbapService( 4484): Accepting socket connection...
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 171a03a2-d0ff-44e9-8246-c5698b0f7138
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 171a03a2-d0ff-44e9-8246-c5698b0f7138 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/LGBluetoothContextForResources( 7390): [BTUI] create LGBluetoothContextForResources new Instance
D/LGBluetoothContextForResources( 7390): context.getPackageName : com.lge.bluetoothsetting
D/LGBluetoothContextForResources( 7390): mBluetoothContext.getPackageName : com.lge.bluetoothsetting
D/PanProfile( 7390): mainContext : com.lge.bluetoothsetting
,D/BluetoothManagerService( 1280): Message: 30
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 03e83af4-0e5e-4d33-bda4-5775ac44f0c9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 03e83af4-0e5e-4d33-bda4-5775ac44f0c9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/LIA_SmartSetting(4.50.6)_SenseLocation( 7476): getCurrentPlaceId 
D/LIA_SmartSetting(4.50.6)_Recommender( 7476): not entered home
V/LIA_SmartSetting(4.50.6)_DeviceLogger( 7476): DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1457358076755, , settingStatus=Bluetooth on, deviceTypeOrdinal=1]
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LocalBluetoothProfileManager( 7390): Adding local MAP profile
,D/BluetoothMap( 7390): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1280): Message: 30
,D/LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter( 7476): insert start
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b518486e-38d7-4c62-9ae6-103ebfc299c0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b518486e-38d7-4c62-9ae6-103ebfc299c0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_SmartSetting(4.50.6)_LocationDBManager( 7476): insertSettingInfo ID = 5420
,D/BluetoothManagerService( 1280): Message: 30
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 73215c5a-3c90-46b8-a8d4-073b59c16f4c
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 73215c5a-3c90-46b8-a8d4-073b59c16f4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LocalBluetoothProfileManager( 7390): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 4484): Pbap Service onBind
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 595f748f-dd66-47e3-9b72-878813e08b17
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 595f748f-dd66-47e3-9b72-878813e08b17 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LGBluetoothUserBindClient( 7390): [BTUI] initUserBindClient
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e64a047e-c72b-42c0-8d3b-49c998d3dcd7
W/ContextImpl( 7390): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1870 android.content.ContextWrapper.bindService:539 com.lge.bluetoothsetting.LGBluetoothUserBindClient.initUserBindClient:98 com.lge.bluetoothsetting.LGBluetoothUserBindClient.<init>:57 com.lge.bluetoothsetting.LGBluetoothUserBindClient.getInstance:47 
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e64a047e-c72b-42c0-8d3b-49c998d3dcd7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/DockEventReceiver( 7390): finishStartingService: stopping service
,D/BluetoothA2dp( 7390): Proxy object connected
,D/A2dpProfile( 7390): Bluetooth service connected
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 457cc45a-d90a-4a2f-a84e-17a5a040e54d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 457cc45a-d90a-4a2f-a84e-17a5a040e54d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothInputDevice( 7390): Proxy object connected
,D/HidProfile( 7390): Bluetooth service connected
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/BluetoothPan( 7390): BluetoothPAN Proxy object connected
,D/PanProfile( 7390): Bluetooth service connected
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b123c05d-baca-400e-a81f-1b9e03c3c0c0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b123c05d-baca-400e-a81f-1b9e03c3c0c0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothMap( 7390): Proxy object connected
,D/MapProfile( 7390): Bluetooth service connected
D/BluetoothMap( 7390): getConnectedDevices()
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
V/BluetoothMapService( 4484): getConnectedDevices()
,D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): onReceive(), ConnectedDeviceName : null , Num : 0
,D/BluetoothPbap( 7390): Proxy object connected
D/PbapServerProfile( 7390): Bluetooth service connected
D/LGBluetoothUserBindClient( 7390): [BTUI] onServiceConnected
D/BluetoothManagerService( 1280): Message: 400
,D/BluetoothHeadset( 4684): Proxy object connected
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0811f9de-123c-47d0-a96d-a5a378aa7346
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0811f9de-123c-47d0-a96d-a5a378aa7346 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/BluetoothOppReceiver( 4484): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothManagerService( 1280): Message: 400
,D/BluetoothHeadset( 4118): Proxy object connected
,D/BluetoothManagerService( 1280): Message: 400
,D/BluetoothHeadset( 4118): Proxy object connected
,D/BluetoothManagerService( 1280): Message: 400
V/BluetoothOppManager( 4484): restoreApplicationData! falsefalsenullnull
D/BluetoothHeadset( 4118): Proxy object connected
D/BluetoothManagerService( 1280): Message: 400
D/BluetoothHeadset( 1280): Proxy object connected
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - deb9f079-8f54-4a32-820d-cbe1e7b8a2ab
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - deb9f079-8f54-4a32-820d-cbe1e7b8a2ab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/BluetoothSapReceiver( 4484): [BTUI] checkServiceStart
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b222fdb0-13b6-4364-8b77-0fe3d9b131b7
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b222fdb0-13b6-4364-8b77-0fe3d9b131b7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothPermissionRequest( 7390): onReceive
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 869808e7-7467-4d4d-8ef3-38a11bdc7aa8
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 869808e7-7467-4d4d-8ef3-38a11bdc7aa8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LGBluetoothFeatureConfig( 7390): isPrivacyLogsEnabled : true
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LGBluetoothUtils( 7390): [BTUI] FileNotFound: readProperty
,D/LGBluetoothStateChangeReceiver( 7390): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 151e475f-becf-4d00-8f48-d7dad0c500a6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 151e475f-becf-4d00-8f48-d7dad0c500a6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/AuthorizationBluetoothService( 5205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7b05957e-dea2-43bc-9f10-e82b187b4825
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7b05957e-dea2-43bc-9f10-e82b187b4825 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/CloudHub( 7732): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 7732): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c38523a3-5c05-4551-8d5c-60002cbdd666
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c38523a3-5c05-4551-8d5c-60002cbdd666 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b2f2840c-0331-482b-8a8c-275c5c7f7241
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b2f2840c-0331-482b-8a8c-275c5c7f7241 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/a       ( 5205): Opening database auth.proximity.permit_store...
V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 37e24a4b-05bc-4cef-bccf-7048ddf00a8f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 37e24a4b-05bc-4cef-bccf-7048ddf00a8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@3dae0e02 on behalf of 7732
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothManagerService( 1280): Message: 400
,D/BluetoothHeadset( 7390): Proxy object connected
D/HeadsetProfile( 7390): Bluetooth service connected
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - debc2b4b-df02-4fc0-b223-3623910576d6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - debc2b4b-df02-4fc0-b223-3623910576d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7768:com.lge.drive.activator/u0a65 for broadcast com.lge.drive.activator/com.lge.drive.oem.BootReceiver
,I/ActivityManager( 1280): Killing 6973:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d29a559d-5c21-44ea-8e56-54907674eab8
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d29a559d-5c21-44ea-8e56-54907674eab8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/TasksProvider( 7615): Sending task notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ }
W/ContentResolver( 7615): Failed to get type for: content://com.lge.task/ (Unknown URI content://com.lge.task/)
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2f2d55ad-71cf-47e5-b47f-a4026eff375d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2f2d55ad-71cf-47e5-b47f-a4026eff375d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9bc52120-dc53-4abf-8e05-3d8c591935eb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9bc52120-dc53-4abf-8e05-3d8c591935eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Killing 6877:com.android.gallery3d/u0a55 (adj 15): empty #22
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 20361834-0923-49e2-bddf-83bd3f273a59
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 20361834-0923-49e2-bddf-83bd3f273a59 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - aafe78f8-e04e-42e6-ac74-a8d774918607
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - aafe78f8-e04e-42e6-ac74-a8d774918607 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cb58d621-d69c-48fc-a189-313570a50797
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cb58d621-d69c-48fc-a189-313570a50797 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4829edec-e062-41e7-bc40-f2cf942a1bc6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4829edec-e062-41e7-bc40-f2cf942a1bc6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3431e8fb-688d-42d8-b044-4a0b31e09c2d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3431e8fb-688d-42d8-b044-4a0b31e09c2d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7791:com.lge.drmservice/u0a68 for broadcast com.lge.drmservice/.DrmBroadcastReceiver
,I/ActivityManager( 1280): Killing 6526:com.lge.clock/u0a16 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 88305298-5d49-42bb-b379-f58bfb74237e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 88305298-5d49-42bb-b379-f58bfb74237e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/ActivityManager( 1280): Waited long enough for: ServiceRecord{10e26dfa u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8e1331e3-0612-4a99-981d-ae79a3a483e3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8e1331e3-0612-4a99-981d-ae79a3a483e3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bc6989b3-d9af-4f66-ad25-48f8feef1fac
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bc6989b3-d9af-4f66-ad25-48f8feef1fac / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b6035a83-4f7d-469d-ab0e-2c1b758f3cbb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b6035a83-4f7d-469d-ab0e-2c1b758f3cbb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/art     ( 4732): Explicit concurrent mark sweep GC freed 3126(127KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 579us total 25.843ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 834a078b-bbc3-433b-ad24-7374720abbca
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 834a078b-bbc3-433b-ad24-7374720abbca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/DrmBroadcastReceiver( 7791): Receive ACTION_BOOT_COMPLETED
,V/DrmService( 7791): Service onCreate
,D/DrmService( 7791): Received new request = 4
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4c6fc8e1-64b0-43bb-a8e6-31a5a8a3ccbd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4c6fc8e1-64b0-43bb-a8e6-31a5a8a3ccbd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/DrmServiceHandler( 7791): updateDrmPushNotification() : No notification
,D/DrmService( 7791): Completed !! request = 4
D/DrmService( 7791): Request count = 0
,I/ActivityManager( 1280): Start proc 7811:com.google.android.configupdater/u0a64 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/DrmService( 7791): Service onDestroy
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 57681a41-7b11-4000-bfc0-e4685d64f616
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 57681a41-7b11-4000-bfc0-e4685d64f616 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 518b673e-37b1-4fe5-a41e-bf6bd96bc45a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 518b673e-37b1-4fe5-a41e-bf6bd96bc45a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Killing 5050:com.google.android.gms/u0a6 (adj 15): empty #22
,D/ConnectivityService( 1280): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2247864d)
,D/ConnectivityService( 1280): dumpNetworkRequest
D/ConnectivityService( 1280):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::a239:f7ff:fe6f:c95d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60}  everValidated{true}  lastValidated{true}  created{true}  explicitlySelected{false} }
D/ConnectivityService( 1280):     Requests:
D/ConnectivityService( 1280):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1280):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1280):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1280):     Lingered:
D/ConnectivityService( 1280): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1280): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1280): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 493930b0-fba2-4e71-bbeb-980d846513c7
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 493930b0-fba2-4e71-bbeb-980d846513c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/KeyguardUpdateMonitor( 3398): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 3398): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 4057): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 3398): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3398): On Skip Timer : true
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bf9f7fb1-e1b0-4244-874f-e6e55488f0dd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bf9f7fb1-e1b0-4244-874f-e6e55488f0dd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1588a9c1-7816-486b-b709-ad4687ed104a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1588a9c1-7816-486b-b709-ad4687ed104a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7da46135-f30a-4cc7-a48e-7ed2469965fd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7da46135-f30a-4cc7-a48e-7ed2469965fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2c9d6b36-f196-4d27-9cf9-1a05eacae44f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2c9d6b36-f196-4d27-9cf9-1a05eacae44f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ebc6f3d2-8e9b-4d52-a73a-26666c21bedb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ebc6f3d2-8e9b-4d52-a73a-26666c21bedb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - de444991-6fae-41cf-88df-6ea89ae595f2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - de444991-6fae-41cf-88df-6ea89ae595f2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 01cecfcb-ca84-4a50-b919-65bc5b8b08d8
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 01cecfcb-ca84-4a50-b919-65bc5b8b08d8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e66c4f6a-c6b2-49c4-9e5b-aa919a6d402e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e66c4f6a-c6b2-49c4-9e5b-aa919a6d402e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 763e4172-cd32-4e68-8bda-9b12a569ae07
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 763e4172-cd32-4e68-8bda-9b12a569ae07 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2ae13f22-ce07-4e54-b9f2-e196e2e6aea1
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2ae13f22-ce07-4e54-b9f2-e196e2e6aea1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1bc38bb4-707f-43e8-95e4-8357b03eb6bc
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1bc38bb4-707f-43e8-95e4-8357b03eb6bc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/UpdateRequestReceiver( 7811): ignoring update request
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/UpdateRequestReceiver( 7811): ignoring update request
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 74a589a7-7ae1-443d-a71c-3012a7490cf2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 74a589a7-7ae1-443d-a71c-3012a7490cf2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
E/UpdateRequestReceiver( 7811): ignoring update request
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5dfcd78d-dca1-448b-a5e9-621d41a6911a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5dfcd78d-dca1-448b-a5e9-621d41a6911a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/UpdateRequestReceiver( 7811): ignoring update request
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 089b8ef7-36c5-48e2-a905-bc5678be5979
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 089b8ef7-36c5-48e2-a905-bc5678be5979 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
E/UpdateRequestReceiver( 7811): ignoring update request
,E/UpdateRequestReceiver( 7811): ignoring update request
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 82b9a205-4fa0-4794-918b-a593bd4f33a9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 82b9a205-4fa0-4794-918b-a593bd4f33a9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7844:com.lge.gcuv/1000 for broadcast com.lge.gcuv/.GcuvReceiver
,I/ActivityManager( 1280): Killing 7116:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,V/AudioFlinger(  466): thread 0xf2091000 type 0 TID 3233 going to sleep
,V/AudioFlinger(  466): thread 0xf2047000 type 0 TID 3231 going to sleep
,V/AudioFlinger(  466): thread 0xf5fab000 type 0 TID 3230 going to sleep
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5f863214-316c-42c3-8398-856ba55e0382
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5f863214-316c-42c3-8398-856ba55e0382 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6eadfa52-9425-4717-99e8-1d4e907b2fee
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6eadfa52-9425-4717-99e8-1d4e907b2fee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2f501d59-657b-4647-87a9-d40b8df84ab7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2f501d59-657b-4647-87a9-d40b8df84ab7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bdffc995-fc23-483a-8303-4600254e1a4e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bdffc995-fc23-483a-8303-4600254e1a4e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 91362f08-3471-4796-8261-4102ba5e06b6
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 91362f08-3471-4796-8261-4102ba5e06b6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/GCUV:GcuvReceiver( 7844): onReceive from Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.gcuv/.GcuvReceiver (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/GCUV:SDKReflector( 7844): +isLinkedUser : false
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3e01f7be-98e3-46aa-a43d-3ee68546da04
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3e01f7be-98e3-46aa-a43d-3ee68546da04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/GCUV:JsonUtils( 7844): getJsonFile {"sequence":"00000000000000000000000003000002952842","gcuv_completed":false}
I/GCUV:JsonUtils( 7844): readCompleted + false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d17bd42a-b0d6-4413-8657-613dedf877c1
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d17bd42a-b0d6-4413-8657-613dedf877c1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/GCUV:Utils( 7844): startService will start at 03/07 16:41:17
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2d313401-5b56-4def-81e9-af630f55c065
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2d313401-5b56-4def-81e9-af630f55c065 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7864:com.lge.gnss.airtest/u0a80 for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver
,I/ActivityManager( 1280): Killing 6652:com.android.providers.calendar/u0a19 (adj 15): empty #22
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 95726(5MB) AllocSpace objects, 3(268KB) LOS objects, 33% free, 61MB/91MB, paused 1.893ms total 152.837ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9802f6c9-7e76-46b1-91a5-b9bf890bea1a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9802f6c9-7e76-46b1-91a5-b9bf890bea1a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a84e3c6d-b477-476b-b68e-456f670ccbcb
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a84e3c6d-b477-476b-b68e-456f670ccbcb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/AirTest ( 7864): Set airtest_enable to false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 741faada-69bc-45ee-b9c2-2accb6aed8f2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 741faada-69bc-45ee-b9c2-2accb6aed8f2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e172e70b-487f-42d2-9fd5-fa2e8bbeb957
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e172e70b-487f-42d2-9fd5-fa2e8bbeb957 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/LGSC    ( 4118): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 07dd7864-f444-40fe-8fdc-bf699e71c648
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 07dd7864-f444-40fe-8fdc-bf699e71c648 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/GoogleHttpClient( 4732): GMS http client unavailable, use old client
,I/ActivityManager( 1280): Start proc 7887:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.ModemProtocol.L5000LoggingReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/AlarmManager( 1280): ELAPSED_WAKEUP set : Alarm{3dcfa850 type 2 when 44652 com.android.providers.calendar} when 44652
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9377b7e6-9a10-4a39-bf14-0e18c9b9b223
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9377b7e6-9a10-4a39-bf14-0e18c9b9b223 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 98424e47-20e8-4f6c-a819-b6a0bc4e9e0d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 98424e47-20e8-4f6c-a819-b6a0bc4e9e0d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 65e2d64b-6123-4b23-b870-87e398004426
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 65e2d64b-6123-4b23-b870-87e398004426 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c8921f61-d72f-40f8-90da-5485d520eb11
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c8921f61-d72f-40f8-90da-5485d520eb11 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0c9220f3-5315-4dcc-a872-515bdb9047ca
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0c9220f3-5315-4dcc-a872-515bdb9047ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a101f2ed-29b3-437e-a70b-486a40e9fd71
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a101f2ed-29b3-437e-a70b-486a40e9fd71 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
I/ActivityManager( 1280): Killing 7221:com.lge.appbox.client:AppBoxCommonService/u0a9 (adj 15): empty #22
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - acdf2dd6-72d3-415a-9aee-eb0f72bd0470
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - acdf2dd6-72d3-415a-9aee-eb0f72bd0470 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ResourcesManager( 7887): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7887): Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
W/ResourcesManager( 7887): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/SMSNvReceiver( 7887): onReceive
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 29f8335f-ebeb-4bc2-921f-8da2aecf36b2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 29f8335f-ebeb-4bc2-921f-8da2aecf36b2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/[SMS_AD]( 7887): Intent action: android.intent.action.BOOT_COMPLETED
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6e72c836-d97d-495e-8423-9a7bc240e01a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6e72c836-d97d-495e-8423-9a7bc240e01a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7908:com.lge.springcleaning/1000 for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver
,I/ActivityManager( 1280): Killing 7243:com.lge.smartconfig/1000 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 54652804-c445-4d93-af00-b504c7632281
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 54652804-c445-4d93-af00-b504c7632281 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f0c17726-3516-42b1-99a7-c068941871a2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f0c17726-3516-42b1-99a7-c068941871a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - afdf2484-a5b0-449a-9d83-469c0cadbb48
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - afdf2484-a5b0-449a-9d83-469c0cadbb48 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e55ed73c-2afa-4b73-bcc9-ac7cdd13350e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e55ed73c-2afa-4b73-bcc9-ac7cdd13350e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cb5a2383-3379-4bcc-b551-4536e4b5b2c2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cb5a2383-3379-4bcc-b551-4536e4b5b2c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 396123ce-dbf7-4cc0-ab2e-d8f533b3c9b3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 396123ce-dbf7-4cc0-ab2e-d8f533b3c9b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BootCompleteReceiver( 7908): hasclipTray = true
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ContextImpl( 7908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2701 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a8b46284-cbf4-44bd-ac5b-4e81473520bd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a8b46284-cbf4-44bd-ac5b-4e81473520bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7928:com.lge.springcleaning:AppCleanupService/1000 for service com.lge.springcleaning/.service.AppCleanupService
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f1333028-d927-43ed-9c9e-e2b702673fa9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f1333028-d927-43ed-9c9e-e2b702673fa9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7948:com.lge.lgfota.permission/1000 for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver
,I/ActivityManager( 1280): Killing 6998:com.lge.appbox.client/u0a9 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/AlarmManager( 1280): RTC_WAKEUP set : Alarm{3be83f4e type 0 when 1457358078922 com.lge.myplace} when 1457358078922
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1b71813e-78ba-44f6-81bb-ba108c400456
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1b71813e-78ba-44f6-81bb-ba108c400456 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d85031a6-3afb-4890-9152-9a157c738d35
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d85031a6-3afb-4890-9152-9a157c738d35 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/TARGETVALIDLATION_RECEIVER( 7948): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/AppCleanupService( 7928): registerAlarm
,D/TARGETVALIDLATION_RECEIVER( 7948): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 7948): Do Not display result dialog. it is not used Update Tool!!
,I/LockScreenSettings( 7533): Received Broadcast : android.intent.action.BOOT_COMPLETED
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8e52cffe-8cdb-449d-b707-9663d0796ec9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8e52cffe-8cdb-449d-b707-9663d0796ec9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/AppCleanupService( 7928): noticeInterval = 2674800000
D/AppCleanupService( 7928): notiDateStr = 2016-03-27 17:35:59
I/LockScreenSettings( 7533): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/AppCleanupService( 7928): noticeStart = 2016-03-27 17:35:59
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 269419bd-8393-4a13-bc0f-00657cd015d5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 269419bd-8393-4a13-bc0f-00657cd015d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/AppCleanupService( 7928): noticeStart = 1459092959000
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 78bbbf3c-373f-4771-ae86-0ba66933d381
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 78bbbf3c-373f-4771-ae86-0ba66933d381 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Killing 7270:com.lge.myplace/u0a30 (adj 15): empty #22
,D/AppUsageDbAdapter( 7928): initPreloadedAppToTheDB() : row count = 255
,V/LGSC    ( 5553): [104] 401
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9f130368-95f1-44ae-8366-1fa6fce0498b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9f130368-95f1-44ae-8366-1fa6fce0498b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 7970:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2aa4c3f6-93fb-4d41-868c-12322edfc4a6
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2aa4c3f6-93fb-4d41-868c-12322edfc4a6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ef259041-18f9-4c0f-9e07-1d395e4f60d7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ef259041-18f9-4c0f-9e07-1d395e4f60d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6da5e912-3d51-48dc-90ca-c86cc01cb687
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6da5e912-3d51-48dc-90ca-c86cc01cb687 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 03e01b19-0c10-45ed-b89d-f3c0c5f751aa
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 03e01b19-0c10-45ed-b89d-f3c0c5f751aa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b7800d3a-015f-4cde-8d6b-1f5ef3687991
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b7800d3a-015f-4cde-8d6b-1f5ef3687991 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/art     ( 7970): Almond Protected OAT
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3edc9206-7a1b-4640-9209-30108ef8c2e0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3edc9206-7a1b-4640-9209-30108ef8c2e0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ea97011e-ea1f-4943-b4e4-83e855f851e5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ea97011e-ea1f-4943-b4e4-83e855f851e5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 264fc4a9-7da2-4057-9f66-6e3edf523ad2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 264fc4a9-7da2-4057-9f66-6e3edf523ad2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 773b6064-318b-4264-bd4e-23a7f09331d0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 773b6064-318b-4264-bd4e-23a7f09331d0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c7ed03f4-d69e-4b71-ba70-3bccad2c2ea4
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c7ed03f4-d69e-4b71-ba70-3bccad2c2ea4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5118ed51-6564-45ef-bd2f-1696d323e2d5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5118ed51-6564-45ef-bd2f-1696d323e2d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/WeatherPlatformReceiver( 7970): start action : android.intent.action.BOOT_COMPLETED
D/WeatherPlatformReceiver( 7970): setNextUpdate
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3aa655f7-13e4-4005-a013-ef85ee744b8a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3aa655f7-13e4-4005-a013-ef85ee744b8a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/WeatherPlatform_Alarm( 7970): CurrentTime = 3/7 14:41:19
D/WeatherPlatform_Alarm( 7970): lastUpdatedTime = 1/1 1:0:0
D/WeatherPlatform_Alarm( 7970): RemainedTime = -404818:-41:-19
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6ba37268-3437-42b6-a7da-8c901e186926
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6ba37268-3437-42b6-a7da-8c901e186926 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/WeatherPlatform_Alarm( 7970): Update is Canceled by com.lge.sizechangable.weather.action.autoupdate
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3b02990c-c8c8-4007-a836-162cf43d3892
,D/WeatherPlatform_Alarm( 7970): Update is Canceled by com.lge.sizechangable.weather.action.update.currentonly
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3b02990c-c8c8-4007-a836-162cf43d3892 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/WeatherPlatform_Alarm( 7970): set auto-update time : 1/1 3:59:59
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f4faa060-5d7c-40e7-b14c-50029e3d8754
,I/ActivityManager( 1280): Killing 6050:com.android.defcontainer/u0a3 (adj 15): empty #22
D/WeatherPlatformReceiver( 7970): end action : android.intent.action.BOOT_COMPLETED : 16ms
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f4faa060-5d7c-40e7-b14c-50029e3d8754 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ContextImpl( 5441): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2701 
,E/AtFwd AutoBoot( 5441): AtFwd Auto Boot Started Successfully
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 28d50d8d-b6e1-4cc7-9f1c-bb92d23fb6b9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 28d50d8d-b6e1-4cc7-9f1c-bb92d23fb6b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/QcrilMsgTunnelAutoboot( 4707): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 32cce78b-0af3-4e75-b148-dad19d3f6399
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 32cce78b-0af3-4e75-b148-dad19d3f6399 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a352c52f-7ebf-4e52-97b7-58d23a32e3d3
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a352c52f-7ebf-4e52-97b7-58d23a32e3d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm,
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 91edf82a-547b-4dca-b08a-c56b752cbdfe
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 91edf82a-547b-4dca-b08a-c56b752cbdfe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5a7bbf3c-75b2-4c4e-87c6-70f4af4d2ce4
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5a7bbf3c-75b2-4c4e-87c6-70f4af4d2ce4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/PhoneInterfaceManager( 4118): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e6426277-aa80-4168-9b22-23feff97b8fb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e6426277-aa80-4168-9b22-23feff97b8fb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/PhoneInterfaceManager( 4118): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 96b00bf1-76ac-420b-9772-9614970555c7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 96b00bf1-76ac-420b-9772-9614970555c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6a79f1d5-9b76-4db7-a10e-433a023ea36c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6a79f1d5-9b76-4db7-a10e-433a023ea36c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/XDivert ( 4118): Action intent recieved:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qti.xdivert/.XDivert (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/MSM-irqbalance(  680): Discovered a new IRQ: 146
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 50b8b9d1-491c-4f73-8aff-5d3a8f795783
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 50b8b9d1-491c-4f73-8aff-5d3a8f795783 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/MSM-irqbalance(  680): Decided to move IRQ271 from CPU2 to CPU3
,I/ActivityManager( 1280): Start proc 7992:com.lge.ia.task.incalagent/u0a8 for broadcast com.lge.ia.task.incalagent/.BootReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 56670f89-0720-427c-a99e-d830f924a7c8
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 56670f89-0720-427c-a99e-d830f924a7c8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 00082803-a5c5-418a-92e8-131fc1e22894
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 00082803-a5c5-418a-92e8-131fc1e22894 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 12b975bc-2b41-44ed-8b43-4741895d7da8
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 12b975bc-2b41-44ed-8b43-4741895d7da8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5b7161b2-44b6-477e-a060-ad697b76921c
I/art     (  499): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 621us total 19.437ms
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5b7161b2-44b6-477e-a060-ad697b76921c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - af9f85c4-81dd-43b9-a262-fb2d49677423
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - af9f85c4-81dd-43b9-a262-fb2d49677423 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 562db7fb-5b34-426c-a7b7-fbcbdd84a4dc
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 562db7fb-5b34-426c-a7b7-fbcbdd84a4dc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7b46cc46-899a-47cb-bc10-ba0e32c44a7a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7b46cc46-899a-47cb-bc10-ba0e32c44a7a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/art     (  499): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 600us total 19.106ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1aa4e30b-74b0-4f43-8193-98f1d34a5482
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1aa4e30b-74b0-4f43-8193-98f1d34a5482 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2b9e11ee-4b0f-4afa-b6dc-0c5a455b1447
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2b9e11ee-4b0f-4afa-b6dc-0c5a455b1447 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3183faee-4fcc-47e1-b1db-c3e6ee9ba8e4
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3183faee-4fcc-47e1-b1db-c3e6ee9ba8e4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1b02046b-ebef-41fd-bb2e-743c213625b1
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1b02046b-ebef-41fd-bb2e-743c213625b1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/art     (  499): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 687us total 19.690ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6d8ca6f4-87c5-4188-9958-7ad7a5ee8632
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6d8ca6f4-87c5-4188-9958-7ad7a5ee8632 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2e04197a-166d-45c8-93f4-fe6b17dccf2c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2e04197a-166d-45c8-93f4-fe6b17dccf2c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 51d374e6-993f-4b00-9341-17734525412e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 51d374e6-993f-4b00-9341-17734525412e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b2b18ab5-9dfe-4143-a022-b790cb612382
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b2b18ab5-9dfe-4143-a022-b790cb612382 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f80b4dff-7116-463f-83dc-6216cb0f7774
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f80b4dff-7116-463f-83dc-6216cb0f7774 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f47bf020-8f59-48bb-b451-418965586113
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f47bf020-8f59-48bb-b451-418965586113 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 13097e5e-5a19-4b6e-8aa0-cc0c941da455
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 13097e5e-5a19-4b6e-8aa0-cc0c941da455 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 89b446a7-f264-4f2f-b33d-772690c8dff2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 89b446a7-f264-4f2f-b33d-772690c8dff2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4cd36e79-f3fd-4953-b9bf-e7afa7ae8b94
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4cd36e79-f3fd-4953-b9bf-e7afa7ae8b94 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/InCalContentProvider( 7992): [ContentProvider] onCreate called
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 791cef21-e04b-4002-b449-00d8a902c417
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 791cef21-e04b-4002-b449-00d8a902c417 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 51ca12f5-ab79-47ba-9abe-008c71e0a91e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 51ca12f5-ab79-47ba-9abe-008c71e0a91e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - db2893c4-2092-4a11-a687-eb437ac9b21b
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - db2893c4-2092-4a11-a687-eb437ac9b21b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
E/DBConnectionManagerAndroid( 7992): Same database already exists
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e38485cb-3da2-49c4-ace3-40fa306627ea
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e38485cb-3da2-49c4-ace3-40fa306627ea / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/InCalAgent( 7992): InCalAgent Alarm: android.intent.action.BOOT_COMPLETED
,E/DBConnectionManagerAndroid( 7992): Same database already exists
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8a89f1ff-8ff1-471b-86e4-833314171b9e
D/InCalAgentAndroidDBHelper( 7992): /data/data/com.lge.ia.task.incalagent/
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8a89f1ff-8ff1-471b-86e4-833314171b9e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/InCalAgentAndroidDBHelper( 7992): /data/data/com.lge.ia.task.incalagent/
D/InCalAgentAndroidDBHelper( 7992): /data/data/com.lge.ia.task.incalagent/
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1bd7c750-f371-47f1-bb4e-af35a88aa5b0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1bd7c750-f371-47f1-bb4e-af35a88aa5b0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 31189bf4-5545-429d-a50e-377de73fc965
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 31189bf4-5545-429d-a50e-377de73fc965 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b493e08a-0831-47ee-8f46-dd0fc9f82cb7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b493e08a-0831-47ee-8f46-dd0fc9f82cb7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/InCalAgent( 7992): Deleted old venue_detail info
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 289f8e57-548f-4619-b95d-c3d6b525dced
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 289f8e57-548f-4619-b95d-c3d6b525dced / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 8012:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f2898a16-488c-4c01-bdab-93ac801aca29
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f2898a16-488c-4c01-bdab-93ac801aca29 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3c2b9169-addf-4a0f-8263-56e010616005
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3c2b9169-addf-4a0f-8263-56e010616005 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ba8b3b9d-6a68-43c7-8a85-1a463041fccc
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ba8b3b9d-6a68-43c7-8a85-1a463041fccc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8b49a803-634a-48f5-baf2-d75366b43837
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8b49a803-634a-48f5-baf2-d75366b43837 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e4775662-575e-4d3a-b353-8e8669e1974b
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e4775662-575e-4d3a-b353-8e8669e1974b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2cd8d5cb-7395-4a48-96c7-2d9468597cb2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2cd8d5cb-7395-4a48-96c7-2d9468597cb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ResourcesManager( 8012): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d3de462b-25ec-485a-a5c5-b0176ff108ca
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d3de462b-25ec-485a-a5c5-b0176ff108ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - edc3b145-01e3-4651-b55c-529363ae9c9a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - edc3b145-01e3-4651-b55c-529363ae9c9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 890d5493-8caf-4e84-ac03-4a9425825369
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 890d5493-8caf-4e84-ac03-4a9425825369 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/CalendarProvider2( 8012): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f8152f0
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0173bc1a-d097-4d28-a0c9-5c281cd3e009
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0173bc1a-d097-4d28-a0c9-5c281cd3e009 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bc1d6f22-43e3-4ae1-82b7-a6b0c4d01587
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bc1d6f22-43e3-4ae1-82b7-a6b0c4d01587 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/CalendarProvider2( 8012): [getOrCreateCalendarAlarmManager]
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 83509d54-ae3a-48a6-987b-28ad775956c9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 83509d54-ae3a-48a6-987b-28ad775956c9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/CalendarProvider2( 8012): Created com.android.providers.calendar.CalendarAlarmManager@7beda25(com.android.providers.calendar.CalendarProvider2@3f8152f0)
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c6b9ce0e-0bf6-4395-8276-24d2a6431005
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c6b9ce0e-0bf6-4395-8276-24d2a6431005 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/InCalAgent( 7992): Data retrieved from content://com.android.calendar/event_pocket_preference
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0eaba406-8682-490f-9924-bb7c808954df
D/InCalAgent( 7992): Data retrieved  Visible Checked: 0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0eaba406-8682-490f-9924-bb7c808954df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/InCalAgent( 7992): Data retrieved from content://com.android.calendar/event_pocket_preference
D/InCalAgent( 7992): Data retrieved  Visible Checked: 0
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f1475e52-243d-4144-8435-202c684b1255
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f1475e52-243d-4144-8435-202c684b1255 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ee6b751b-3f3d-4e7e-87f1-8a6277bff917
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ee6b751b-3f3d-4e7e-87f1-8a6277bff917 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/InCalAgent( 7992): Visible Unchecked Not Start InCalService
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 93531771-b572-4406-9c77-af2d1e644c41
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 93531771-b572-4406-9c77-af2d1e644c41 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 8033:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
,I/ActivityManager( 1280): Killing 7019:com.google.android.apps.plus/u0a122 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 7339:com.lge.formmanager/u0a49 (adj 15): empty #23
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0b50dead-7338-42e1-a3be-5d69a95ae21d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0b50dead-7338-42e1-a3be-5d69a95ae21d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fbb8a6df-fe6d-43de-bd0d-ecf46325d80f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fbb8a6df-fe6d-43de-bd0d-ecf46325d80f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6043a4f0-2d5f-4486-bfb4-823dc35c3505
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6043a4f0-2d5f-4486-bfb4-823dc35c3505 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 862ed339-641f-4c84-b358-577d9fb98ad9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 862ed339-641f-4c84-b358-577d9fb98ad9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 27122fb5-fd7e-4c45-8dd0-770d0b506dd7
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 27122fb5-fd7e-4c45-8dd0-770d0b506dd7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 92181860-a943-42e2-a155-d4a0e735852f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 92181860-a943-42e2-a155-d4a0e735852f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/[BNRBootReceiver]( 8033): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 8033): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 8033): End of BootComplted IF
V/[BNRBootReceiver]( 8033): Boot Receiver Return
V/[BNRBootCompletedThread]( 8033): run
W/MainApplication( 8033): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ea6d03af-023d-4bbc-a40c-dc7d05890c8b
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ea6d03af-023d-4bbc-a40c-dc7d05890c8b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 08c1cae8-2fca-4848-b332-91dd33d52943
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 08c1cae8-2fca-4848-b332-91dd33d52943 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/linker  ( 8054): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 8054): BNRD > wait starting [8054-4136038528] <
,E/bnrd    ( 8054): /data/data/.bnr_fifo_req
,V/[BNRBootCompletedThread]( 8033): End of BNRProcess
,V/[BNRBootCompletedThread]( 8033): End of BNRViaWifiProcess
,I/ActivityManager( 1280): Start proc 8060:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
,V/[BNRBootCompletedThread]( 8033): End of SpriteProcess
I/ActivityManager( 1280): Killing 7615:com.lge.task/u0a20 (adj 15): empty #22
V/[BNRBootCompletedThread]( 8033): exit
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 706751e4-df06-4c0b-a9bd-cf05cc1b5933
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 706751e4-df06-4c0b-a9bd-cf05cc1b5933 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 65f680e3-9f2b-492d-9d65-777207824fb2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 65f680e3-9f2b-492d-9d65-777207824fb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 29e1e57b-84d4-4c9d-ac79-db148cb0d4e9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 29e1e57b-84d4-4c9d-ac79-db148cb0d4e9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1f0183e5-83e3-46b5-a44e-d0cfee8f7bc2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1f0183e5-83e3-46b5-a44e-d0cfee8f7bc2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1389325a-4c9c-406f-b8fb-5047b265794b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1389325a-4c9c-406f-b8fb-5047b265794b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bb9de6fe-8f41-4419-b8a8-ad29c5cc37e3
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bb9de6fe-8f41-4419-b8a8-ad29c5cc37e3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3681ea27-72d0-4150-aa2f-ceb5f95299fd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3681ea27-72d0-4150-aa2f-ceb5f95299fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6ee5456f-9456-46b8-8981-4c04ecff2cf2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6ee5456f-9456-46b8-8981-4c04ecff2cf2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cfbe8b72-8e3a-4998-b463-3edb97a83a82
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cfbe8b72-8e3a-4998-b463-3edb97a83a82 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 98f0874d-b6fe-48e5-aad9-6bf37eaa2c59
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 98f0874d-b6fe-48e5-aad9-6bf37eaa2c59 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 25e1b2ab-b32f-426e-91ec-ac2ebec08d66
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 25e1b2ab-b32f-426e-91ec-ac2ebec08d66 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ef230305-4cf3-469d-9c08-aa3fd1eafe85
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ef230305-4cf3-469d-9c08-aa3fd1eafe85 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ea0e2806-7922-4f2f-b42c-f03f4d0bb32f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ea0e2806-7922-4f2f-b42c-f03f4d0bb32f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b10104d1-e4e9-4fba-b05a-38316754e591
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b10104d1-e4e9-4fba-b05a-38316754e591 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6d52451c-3ff9-414b-8cec-677d8da8f540
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6d52451c-3ff9-414b-8cec-677d8da8f540 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 16772382-6d07-43e6-bb1c-6aa089f375cd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 16772382-6d07-43e6-bb1c-6aa089f375cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d1bf7a09-33bd-4731-805b-b4e9eeaec6ee
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d1bf7a09-33bd-4731-805b-b4e9eeaec6ee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating ,
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2db1372b-686b-43eb-ab9f-6e7d0a3ae7ff
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2db1372b-686b-43eb-ab9f-6e7d0a3ae7ff / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d80f77b0-13b6-4c62-bcdf-d481014590d3
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d80f77b0-13b6-4c62-bcdf-d481014590d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6ce07274-cdcd-4ce2-814c-4b259fe619a9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6ce07274-cdcd-4ce2-814c-4b259fe619a9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 38e33f3f-4773-48d0-806f-13174903b491
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 38e33f3f-4773-48d0-806f-13174903b491 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5fabf0b0-fb7f-479c-910f-0309b2dd0bf7
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5fabf0b0-fb7f-479c-910f-0309b2dd0bf7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_CTP_StepCounterDetected( 7293): currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ab141f47-5e67-4525-b200-f3be7d04013a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ab141f47-5e67-4525-b200-f3be7d04013a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a9520a93-0796-4360-ac68-0b1cc385201e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a9520a93-0796-4360-ac68-0b1cc385201e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4bb10986-e8ec-4dcc-8ae2-ca0a448864cb
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4bb10986-e8ec-4dcc-8ae2-ca0a448864cb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ef60bd9b-4b37-46db-a1ba-404941422741
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ef60bd9b-4b37-46db-a1ba-404941422741 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a249ba1a-4ed1-45c6-b299-e7ca14ff60f0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a249ba1a-4ed1-45c6-b299-e7ca14ff60f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fa3ec0e5-a36a-4116-b749-3574d36a6c69
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fa3ec0e5-a36a-4116-b749-3574d36a6c69 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a693e746-222f-40a6-b6a6-2dbac9a7cc05
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a693e746-222f-40a6-b6a6-2dbac9a7cc05 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f90cd638-7f1f-44e7-8b5c-f715a5018587
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f90cd638-7f1f-44e7-8b5c-f715a5018587 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f4d27d96-14f4-4ac7-a025-4b2d52255a43
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f4d27d96-14f4-4ac7-a025-4b2d52255a43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9c66dce2-ec8d-4b2a-b078-32fd35a28ae0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9c66dce2-ec8d-4b2a-b078-32fd35a28ae0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 886be952-2de9-4927-b34e-39ed969a5588
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 886be952-2de9-4927-b34e-39ed969a5588 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2d76dd0f-0098-4b73-abaf-f028667221b9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2d76dd0f-0098-4b73-abaf-f028667221b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8fcc5e8c-c8fe-4888-85ab-12aa489431cd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8fcc5e8c-c8fe-4888-85ab-12aa489431cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 24e437fc-3494-40c3-972f-b9c2f82ef89e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 24e437fc-3494-40c3-972f-b9c2f82ef89e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 803125a0-c64c-44b7-b6fd-d35b7ca1b725
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 803125a0-c64c-44b7-b6fd-d35b7ca1b725 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 94a5beeb-2fb2-4ad8-88d6-ccd78991edba
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 94a5beeb-2fb2-4ad8-88d6-ccd78991edba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 894925e2-e51a-4291-9bc1-792ae15c4b12
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 894925e2-e51a-4291-9bc1-792ae15c4b12 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 65185bd2-75cd-4dcc-89b5-69883bd5a900
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 65185bd2-75cd-4dcc-89b5-69883bd5a900 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/ActivityThread( 8060): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 63cb7ad3-9b21-4bc9-99a0-8f14f42e0959
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 63cb7ad3-9b21-4bc9-99a0-8f14f42e0959 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Gmail   ( 8060): getAccountsCursor
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d9be372b-8066-436d-81b5-d990aeeda02c
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d9be372b-8066-436d-81b5-d990aeeda02c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 30435cfc-d93b-471d-b56e-fd2526705744
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 30435cfc-d93b-471d-b56e-fd2526705744 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 829b4156-1341-4270-8ab3-13b5eaf56794
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 829b4156-1341-4270-8ab3-13b5eaf56794 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a8f25c9a-f492-487e-9f29-ef20a347f630
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a8f25c9a-f492-487e-9f29-ef20a347f630 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9a931799-16f8-406a-82f1-2f98d6e6ea04
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9a931799-16f8-406a-82f1-2f98d6e6ea04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 84352142-8431-4722-ac6d-c375fe7041b3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 84352142-8431-4722-ac6d-c375fe7041b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 865b4daf-072f-4f31-8b58-cec9534baa97
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 865b4daf-072f-4f31-8b58-cec9534baa97 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4b794654-155f-421b-b272-24c223b7b48a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4b794654-155f-421b-b272-24c223b7b48a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 44ca9b81-fa77-4713-9972-dc5361e9dbd5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 44ca9b81-fa77-4713-9972-dc5361e9dbd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c08e9922-0204-4981-bb90-6d9d9cdfe5ac
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c08e9922-0204-4981-bb90-6d9d9cdfe5ac / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fc128c02-c630-4662-9981-70da16e8cf99
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fc128c02-c630-4662-9981-70da16e8cf99 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6dfef9fc-b361-45a9-9998-edc5899487b0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6dfef9fc-b361-45a9-9998-edc5899487b0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 27f38297-b70b-40e3-94a8-3227e45002d5
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 27f38297-b70b-40e3-94a8-3227e45002d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ebcfd271-c361-4f20-94aa-4c0c5cd24811
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ebcfd271-c361-4f20-94aa-4c0c5cd24811 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm,
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6ef657a4-a755-44ec-89a5-dc6178314e49
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6ef657a4-a755-44ec-89a5-dc6178314e49 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 81c8c749-54c7-4053-9ad1-0a4e1b9e1141
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 81c8c749-54c7-4053-9ad1-0a4e1b9e1141 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 26d7ccb8-6238-425e-a914-52f7941108bd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 26d7ccb8-6238-425e-a914-52f7941108bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7050ff3f-2cd7-4006-ac9d-3ef4e6a07b98
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7050ff3f-2cd7-4006-ac9d-3ef4e6a07b98 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a70bd083-4c69-4a1e-8b19-3187f5168b43
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a70bd083-4c69-4a1e-8b19-3187f5168b43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fa5c3172-db16-47a5-933a-b9a0d67b1eb3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fa5c3172-db16-47a5-933a-b9a0d67b1eb3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ActivityManager( 1280): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b835f487-a783-486f-a42e-a9f3c802b38a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b835f487-a783-486f-a42e-a9f3c802b38a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 40fd4fba-cefb-46af-b577-6e61ac94842c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 40fd4fba-cefb-46af-b577-6e61ac94842c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bd1e7c72-5562-4ff0-9c1b-835dd21f0567
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bd1e7c72-5562-4ff0-9c1b-835dd21f0567 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Gmail   ( 8060): Observing account changes for notifications
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4ca2f31f-88b4-4df6-9f47-83970a61b60f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4ca2f31f-88b4-4df6-9f47-83970a61b60f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/GAV2    ( 8060): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b66e5d5d-b14d-4acc-bda2-0f819c17bad0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b66e5d5d-b14d-4acc-bda2-0f819c17bad0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 40946a72-4ec0-4c8d-8d2f-a0d9905e6106
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 40946a72-4ec0-4c8d-8d2f-a0d9905e6106 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4e829150-125e-4886-86ea-9ccde1c985d5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4e829150-125e-4886-86ea-9ccde1c985d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 19033ee3-e37d-4335-9815-c4160abd8747
W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 19033ee3-e37d-4335-9815-c4160abd8747 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 55abf039-0499-433f-9f0d-3aa3bdfb1cd5
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 55abf039-0499-433f-9f0d-3aa3bdfb1cd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e1639432-8c5f-48a0-8649-e45b9abe721e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e1639432-8c5f-48a0-8649-e45b9abe721e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 537c5b87-9f67-415d-81f4-84d83f25deb8
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 537c5b87-9f67-415d-81f4-84d83f25deb8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/Gmail   ( 8060): Error finding the version of the Email provider.....
E/Gmail   ( 8060): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 8060): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 8060): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 8060): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 8060): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 8060): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 8060): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 8060): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 8060): We do not support migrating this version of the Email provider.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 970b9fe0-824b-4e9d-b0ba-d8346aabb205
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 970b9fe0-824b-4e9d-b0ba-d8346aabb205 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Gmail   ( 8060): getAccountsCursor
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5e249c61-e345-42a3-a78b-e2bb95936113
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5e249c61-e345-42a3-a78b-e2bb95936113 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 74aff581-351d-4be1-89c6-2c4529d06455
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 74aff581-351d-4be1-89c6-2c4529d06455 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1280): Start proc 8101:com.android.vending/u0a62 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bba95c60-e778-4b10-af5c-f615bfac03d6
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bba95c60-e778-4b10-af5c-f615bfac03d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
E/ActivityThread( 8060): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@97e8d14 that was originally bound here
E/ActivityThread( 8060): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@97e8d14 that was originally bound here
E/ActivityThread( 8060): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1259)
E/ActivityThread( 8060): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1153)
E/ActivityThread( 8060): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1888)
E/ActivityThread( 8060): 	at android.app.ContextImpl.bindService(ContextImpl.java:1871)
E/ActivityThread( 8060): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 8060): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 8060): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 8060): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 8060): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 8060): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 8060): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 8060): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 8060): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 8060): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 8060): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 8060): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1280): Unbind failed: could not find connection for android.os.BinderProxy@33297cae
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0218dba6-3b8f-4dd6-aa68-65b0bddedbb1
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0218dba6-3b8f-4dd6-aa68-65b0bddedbb1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0244ab51-5b33-450e-a0ae-f7003ad4bc64
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0244ab51-5b33-450e-a0ae-f7003ad4bc64 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 23c52ef1-4bea-4648-abc7-e20327a28f4f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 23c52ef1-4bea-4648-abc7-e20327a28f4f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4922fff3-1d9f-4647-a8de-2b186920a32e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4922fff3-1d9f-4647-a8de-2b186920a32e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5870cbdc-47ad-4b06-b8fd-214d3666860e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5870cbdc-47ad-4b06-b8fd-214d3666860e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 116fae68-b15d-4ad5-b2ce-d36d616351ea
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 116fae68-b15d-4ad5-b2ce-d36d616351ea / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 34ed90bb-ea48-4655-9406-ca237996b5ab
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 34ed90bb-ea48-4655-9406-ca237996b5ab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 98e370a8-dc72-438d-acc4-14756bab1cee
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 98e370a8-dc72-438d-acc4-14756bab1cee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 409f36ac-2a0a-40e5-b1b3-1d5d8b74fd9a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 409f36ac-2a0a-40e5-b1b3-1d5d8b74fd9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 78f338c7-4684-4764-bcaa-064186026361
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 78f338c7-4684-4764-bcaa-064186026361 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c8df21d1-5658-42f3-80ba-8170ab81ec73
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c8df21d1-5658-42f3-80ba-8170ab81ec73 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 81535909-e940-40b0-b588-a88c8f90b4ca
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 81535909-e940-40b0-b588-a88c8f90b4ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 814bf556-8011-42d7-a000-99d240d75e00
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 814bf556-8011-42d7-a000-99d240d75e00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - dc651e19-46e8-4831-abb0-0d8cb228d035
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - dc651e19-46e8-4831-abb0-0d8cb228d035 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6202a83b-e18c-49f7-83b9-37dda8d37934
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6202a83b-e18c-49f7-83b9-37dda8d37934 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 682f2ce4-b1ad-4e2d-8a0d-d2028980af56
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 682f2ce4-b1ad-4e2d-8a0d-d2028980af56 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 680cb9ec-7b04-42ac-9056-73993ecc808c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 680cb9ec-7b04-42ac-9056-73993ecc808c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1d5c7421-6381-4abc-b782-7c3adc677e7d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1d5c7421-6381-4abc-b782-7c3adc677e7d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fbd8ec31-807f-4a7c-9ea6-2016bb7c1cf6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fbd8ec31-807f-4a7c-9ea6-2016bb7c1cf6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ce57ba62-cb76-4220-a487-2114dcb6092c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ce57ba62-cb76-4220-a487-2114dcb6092c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 70590970-02bd-4905-a7c0-e2d2bb42eb62
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 70590970-02bd-4905-a7c0-e2d2bb42eb62 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7236aae1-e996-463a-8031-4cc362fde6b3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7236aae1-e996-463a-8031-4cc362fde6b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 926ebf23-406f-4438-8f59-9a37c2271c8f
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 926ebf23-406f-4438-8f59-9a37c2271c8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/Gmail   ( 8060): notifyAccountChanged
,I/Gmail   ( 8060): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5520c849-42d8-45c3-9a64-d3b94b7251d3
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5520c849-42d8-45c3-9a64-d3b94b7251d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - dc0f9d35-d277-4d02-b51e-52a6cd9e0b76
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - dc0f9d35-d277-4d02-b51e-52a6cd9e0b76 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/Gmail   ( 8060): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 63ded62a-9750-4e49-9ece-0961f83f42ed
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 63ded62a-9750-4e49-9ece-0961f83f42ed / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/Gmail   ( 8060): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 8060): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8a86d4bd-d371-4086-818c-88debab7e023
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8a86d4bd-d371-4086-818c-88debab7e023 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cb77b773-c909-4cde-ac38-a34efc68150c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cb77b773-c909-4cde-ac38-a34efc68150c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - eee7b05c-fa50-49d6-88ed-a2a759a27f15
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - eee7b05c-fa50-49d6-88ed-a2a759a27f15 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8e5af302-3dba-48f5-87ac-53e03d539d04
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8e5af302-3dba-48f5-87ac-53e03d539d04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6a69f98d-6575-45d5-9e91-d68e7dee4da2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6a69f98d-6575-45d5-9e91-d68e7dee4da2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ea14854e-3f9f-4ee7-a201-11a1631fdeca
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ea14854e-3f9f-4ee7-a201-11a1631fdeca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 464ddc3e-1680-4c53-b3f2-e72dc8758016
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 464ddc3e-1680-4c53-b3f2-e72dc8758016 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1f907072-f094-4959-9ab0-0f79ee5a6480
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1f907072-f094-4959-9ab0-0f79ee5a6480 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d7baeb28-d03c-454b-acd6-ffcd88610a03
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d7baeb28-d03c-454b-acd6-ffcd88610a03 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9e0154e7-1b18-47e7-a1a9-3a12cedf27c8
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9e0154e7-1b18-47e7-a1a9-3a12cedf27c8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f6037b05-fc58-4492-a50b-18c18fe64951
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f6037b05-fc58-4492-a50b-18c18fe64951 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b7ff929f-b6a7-4c54-9365-aaa04bf418dd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b7ff929f-b6a7-4c54-9365-aaa04bf418dd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 68c06519-cd8d-46be-a2e6-636edda9d7d6
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 68c06519-cd8d-46be-a2e6-636edda9d7d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 976de724-cfbb-47c8-8567-ef68177fc50d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 976de724-cfbb-47c8-8567-ef68177fc50d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 62075146-fc0f-4a97-97a2-3ecf30b1334a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 62075146-fc0f-4a97-97a2-3ecf30b1334a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bff89f91-99d5-4412-a336-672911ba88a8
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bff89f91-99d5-4412-a336-672911ba88a8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/Finsky  ( 8101): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bcfbc285-dc7e-439a-9ea8-cc1b145ac79f
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bcfbc285-dc7e-439a-9ea8-cc1b145ac79f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d380f950-c87c-4f1b-a483-2a63f49bf1fd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d380f950-c87c-4f1b-a483-2a63f49bf1fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6553dabf-f63d-4062-b8c3-d84fb2c4f8b9
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6553dabf-f63d-4062-b8c3-d84fb2c4f8b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 8060): getAccountsCursor
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 865ed0fa-2f5b-465c-9ced-4ac0880cd16e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 865ed0fa-2f5b-465c-9ced-4ac0880cd16e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4fe0fa81-7eca-4486-82ba-e2da3e7b55be
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4fe0fa81-7eca-4486-82ba-e2da3e7b55be / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 937d70d6-6e5b-4091-a795-2ded79d5d42d
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 937d70d6-6e5b-4091-a795-2ded79d5d42d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2e6bb707-df3a-46c8-8b91-5c4b0ae4a55d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2e6bb707-df3a-46c8-8b91-5c4b0ae4a55d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/Gmail   ( 8060): getAccountsCursor
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e3587bbb-8cc3-4db6-86f1-de8c12a29067
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e3587bbb-8cc3-4db6-86f1-de8c12a29067 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
V/GLSActivity( 5205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fb13061c-fcd4-4752-bd33-9c1d341e1e61
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fb13061c-fcd4-4752-bd33-9c1d341e1e61 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2d9a8638-ed23-4470-9d49-8dca99785057
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2d9a8638-ed23-4470-9d49-8dca99785057 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a0015d8e-db79-4411-94bb-e51aa8329482
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a0015d8e-db79-4411-94bb-e51aa8329482 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d1a03ad5-d246-4d36-a9ee-f61055fb6c9a
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d1a03ad5-d246-4d36-a9ee-f61055fb6c9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6dbeaf37-3466-42cc-ba47-af0d1d41888a
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6dbeaf37-3466-42cc-ba47-af0d1d41888a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ffae94f7-8d51-41a7-b23e-841c1d3d03d9
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ffae94f7-8d51-41a7-b23e-841c1d3d03d9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0c2f9104-796b-4205-ae33-4b0d070111fd
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0c2f9104-796b-4205-ae33-4b0d070111fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3496b1b5-8354-47d3-a32d-b65fbd5ca47b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3496b1b5-8354-47d3-a32d-b65fbd5ca47b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothManagerService( 1280): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService( 1280): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@de6016a mBinding = false
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ecb6ccf5-4c8e-45fc-9d8f-93084aec3df2
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ecb6ccf5-4c8e-45fc-9d8f-93084aec3df2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - db8034f2-ccf8-4976-adf8-93bd0e42a1ad
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - db8034f2-ccf8-4976-adf8-93bd0e42a1ad / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LocationManagerService( 1280): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1280): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1280): JNI:system_update. Event-4
D/BluetoothManagerService( 1280): Message: 2
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothManagerService( 1280): Sending off request.
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothAdapterService(221810696)( 4484): disable() called...
D/LGBluetoothServiceAdapter( 4484): [BTUI] Precleanup
D/LGBluetoothDeviceModeControllManager( 4484): getDeviceMode  deviceMode 0
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothAdapterState( 4484): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 4484): Setting state to 13
I/BluetoothAdapterState( 4484): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(221810696)( 4484): updateAdapterState() - Broadcasting state to 1 receivers.
,D/BluetoothAdapterProperties( 4484): onBluetoothDisable()
I/BluetoothAdapterState( 4484): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/BluetoothManagerService( 1280): Message: 60
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1280): Bluetooth State Change Intent: 12 -> 13
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0f181be5-e6ba-4a18-aedb-e1356e782077
D/LGBluetoothAPIService( 4057): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0f181be5-e6ba-4a18-aedb-e1356e782077 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_properties_cb
D/BleQmManagerService( 4057): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothMapService( 4484): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 4484): STATE_TURNING_OFF
V/BluetoothMapService( 4484): Handler(): got msg=4
D/BluetoothMapService( 4484): MAP Service closeService in
D/BluetoothMapMasInstance( 4484): MAP Service shutdown
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/bt-btif ( 4484): BTA_JvDeleteRecord
I/bt-btif ( 4484): BTA_JvRfcommStopServer
D/BluetoothAdapterProperties( 4484): Scan Mode:20
D/BluetoothAdapterState( 4484): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 4484): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 4484): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 4484): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 4484): BTA_JvDeleteRecord
I/bt-btif ( 4484): BTA_JvRfcommStopServer
V/BluetoothPbapService( 4484): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 4484): invalid rfc slot id: 2
D/IOP_DB_BT( 4484): db_close: nbr users 0
D/IOP_DB_BT( 4484): db_close: free database
D/btif_config_util( 4484): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 4484): enum_config(L344): out, value:f8:95:c7:87:3c:51
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 4484): enum_config(L344): out, value:����:r4W�J�c��^�BindBitmaps
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 4484): enum_config(L344): out, value:��m��
D/btif_config_util( 4484): �]�j8oV|\!icudt53l-zone
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 4484): enum_config(L344): out, value:�2�d��	t�y����icudt53l-zone
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 4484): enum_config(L344): out, value:�<#��%9T�u�-x�``+��0+���
D/btif_config_util( 4484): ��ong
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, valu,e type:int
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 4484): enum_config(L344): out, value:x
D/btif_config_util( 4484): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:G4-1
D/btif_config_util( 4484): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist,
,D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
,V/BluetoothMapMasInstance( 4484): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 4484): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 4484): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 4484): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 4484): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 4484): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 4484): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 4484): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 4484): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 4484): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 4484): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 4484): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 4484): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 4484): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 4484): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 4484): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:	a
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/LGBluetoothMapAdapter( 4484): [BTUI] LGBluetoothMapAdapter cleanup
D/btif_config_util( 4484): enum_config(L302): section name:Remot,e, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Note3-1
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
V/BluetoothMapService( 4484): MAP Service closeService out
W/ActivityManager( 1280): getRunningAppProcesses: caller 10361 does not hold REAL_GET_TASKS; limiting output
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
,D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
W/ContextImpl( 7390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
D/btif_config_util( 4484): enum_config(L344): out, value:
,D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
V/BluetoothPbapReceiver( 4484): PbapReceiver onReceive 
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:A
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/WifiServiceImplEx( 1280): setWifiEnabled: false pid=7441, uid=10361, package= com.example.hello, App Lable : HelloWorld
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
,D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/WifiService( 1280): setWifiEnabled: false pid=7441, uid=10361
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
V/BluetoothPbapReceiver( 4484): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
V/BluetoothPbapReceiver( 4484): ***********state = 13
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name,
D/btif_config_util( 4484): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
,D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
,D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:A
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
,D/btif_config_util( 4484): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
,D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:#
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/FastDownloadService( 1280): [FastDN][FDS] handleMessage: EVENT_WIFI_SETTING_CHANGED
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/FastDownloadService( 1280): [FastDN][FDS] wifi setting is changed to false
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
,D/btif_config_util( 4484): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
,D/btif_config_util( 4484): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
,D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
,D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LinkKeyType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LinkKeyType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LinkKeyType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:PinLength
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:PinLength, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:PinLength
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LinkKey
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LinkKey, value type:binary
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LinkKey
D/btif_config_util( 4484): enum_config(L344): out, value:�tR��w���𦜻'Manufacturer
D/btif_config_util( 4484): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
,D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:H
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
V/BluetoothPbapReceiver( 4484): ***********Calling start service!!!! with action = null
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:?C
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Tab4
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
,D/btif_config_util( 4484): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:a
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/,btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3,:68, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:A3-1
I/[SystemUI]BluetoothHandler( 3398): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:a
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:S5-1
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
E/LGBluetoothEventManager( 7390): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 304f965d-5d0b-4c64-92fd-e8bec5275e84
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:XT1072
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DMTSupported
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 304f965d-5d0b-4c64-92fd-e8bec5275e84 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DMTSupported, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DMTSupported
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:A5-1
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:A
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:G3s-1
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:82, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:82, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:82, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:82, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:82, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:82, value:DevType
D/ConnectivityService( 1280): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/btif_config_util( 4484): enum_config(L344): out, value:
D/ConnectivityService( 1280): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:XT1039
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:"
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Note4-1
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section ,name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:	a
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/WifiHS20( 1280): hidePasspointNotification off =false
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/WifiHS20( 1280): hidePasspointNotification off =false
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:G3-1
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:6e, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:6e, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:6e, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:6e, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:6e, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:6e, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:	a
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4484): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:����
D/btif_config_util( 4484): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:03:00:00:00:a9:81, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:03:00:00:00:a9:81, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:03:00:00:00:a9:81, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:03:00:00:00:a9:81, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:L�
D/btif_config_util( 4484): enum_config(L300): in, key:03:00:00:00:a9:81, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:03:00:00:00:a9:81, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:#
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:onem9-1
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4484): enum_config(L300): in, key:24:59:5c:de:a9:59, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:24:59:5c:de:a9:59, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:�Lި���,a\ޛ
D/btif_config_util( 4484): enum_config(L300): in, key:24:59:5c:de:a9:59, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:59:5c:de:a9:59, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��B
D/btif_config_util( 4484): enum_config(L300): in, key:24:59:5c:de:a9:59, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:59:5c:de:a9:59, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): @�
D/btif_config_util( 4484): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:D��
D/btif_config_util( 4484): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:16:19:de:a9:19, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f4:16:19:de:a9:19, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:�	ޠ���B��B�
D/btif_config_util( 4484): enum_config(L300): in, key:f4:16:19:de:a9:19, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:16:19:de:a9:19, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:f4:16:19:de:a9:19, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:16:19:de:a9:19, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:ae, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:ae, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:i������p��p��
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:ae, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:ae, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:ae, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:ae, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:	�ݨ�4���ݛ
D/btif_config_util( 4484): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:	�ݠ�����P���P�
D/btif_config_util( 4484): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:f2, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:f2, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:f2, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:f2, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:f2, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:f2, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:4e, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:4e, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:	'ް�B��E��E�
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:4e, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:4e, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��I
D/btif_config_util( 4484): enum_config(L300): in, key:08:00:00:00:9b:4e, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:08:00:00:00:9b:4e, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Service
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Service, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Service
D/btif_config_util( 4484): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:A3-1
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:Z
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:0f:40:e6:f,f:ff, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:@�
D/btif_config_util( 4484): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:0f:40:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:0f:40:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:24:d9:2f:de:a9:d9, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:d9:2f:de:a9:d9, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:d9:2f:de:a9:d9, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:24:d9:2f:de:a9:d9, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:24:d9:2f:de:a9:d9, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:24:d9:2f:de:a9:d9, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:12, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:12, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:12, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:12, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:00:00:00:00:6d:12, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:00:00:00:00:6d:12, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:��
D/btif_config_util( 4484): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:H��
D/btif_config_util( 4484): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:�������hr�hr�
D/btif_config_util( 4484): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:20:00:00:00:00:00, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:20:00:00:00:00:00, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:t��8��� 
D/btif_config_util( 4484): enum_config(L300): in, key:20:00:00:00:00:00, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:20:00:00:00:00:00, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:�
D/btif_config_util( 4484): enum_config(L300): in, key:20:00:00:00:00:00, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:20:00:00:00:00:00, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:88:c6:26:19:97:dc, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:88:c6:26:19:97:dc, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:88:c6:26:19:97:dc, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:88:c6:26:19:97:dc, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:88:c6:26:19:97:dc, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:88:c6:26:19:97:dc, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:fc:f3:1c:6e:2d:57, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:fc:f3:1c:6e:2d:57, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:fc:f3:1c:6e:2d:57, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:fc:f3:1c:68:15:41, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:fc:f3:1c:68:15:41, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:fc:f3:1c:68:15:41, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:c8:d9:53:a0:ea:82, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:c8:d9:53:a0:ea:82, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:c8:d9:53:a0:ea:82, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:c8:d9:53:a0:ec:4e, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:c8:d9:53:a0:ec:4e, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:c8:d9:53:a0:ec:4e, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:e0:b7:20:28:c5:81, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:e0:b7:20:28:c5:81, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:e0:b7:20:28:c5:81, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:54:be:8a:2a:e1:73, value:DevType
,D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:54:be:8a:2a:e1:73, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:54:be:8a:2a:e1:73, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:f0:8b:b2:7e:ea:d2, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:f0:8b:b2:7e:ea:d2, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:f0:8b:b2:7e:ea:d2, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4484): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:66:72:3c:79:d2:ed, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:66:72:3c:79:d2:ed, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:66:72:3c:79:d2:ed, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:79:5c:ac:41:e2:ce, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:79:5c:ac:41:e2:ce, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:79:5c:ac:41:e2:ce, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:	��p���C��C�
D/btif_config_util( 4484): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:���
D/btif_config_util( 4484): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:fc:f3:1c:a2:30:44, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:fc:f3:1c:a2:30:44, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:fc:f3:1c:a2:30:44, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:55:ce:01:ef:8c:a5, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:55:ce:01:ef:8c:a5, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:55:ce:01:ef:8c:a5, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:6e:88:dc:7c:fd:26, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6e:88:dc:7c:fd:26, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:6e:88:dc:7c:fd:26, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4484): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4484): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:Name
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:Name, value type:string
D/btif_config_util( 4484): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:Name
D/btif_config_util( 4484): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4484): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:DevClass
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:DevClass, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:DevClass
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:AddrType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:AddrType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:AddrType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:54:36:60:05:36:7a, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:54:36:60:05:36:7a, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:54:36:60:05:36:7a, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:58:f5:d4:66:00:e7, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:58:f5:d4:66:00:e7, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:58:f5:d4:66:00:e7, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:7c:ca:90:58:e4:df, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:7c:ca:90:58:e4:df, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:7c:ca:90:58:e4:df, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:51:9c:b5:21:65:57, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:51:9c:b5:21:65:57, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:51:9c:b5:21:65:57, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:53:8f:03:8e:00:3c, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:53:8f:03:8e:00:3c, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:53:8f:03:8e:00:3c, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:53:f4:70:85:14:64, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:53:f4:70:85:14:64, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:53:f4:70:85:14:64, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:6d:1c:64:a9:88:80, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:6d:1c:64:a9:88:80, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:6d:1c:64:a9:88:80, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:49:c5:64:5c:74:8c, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:49:c5:64:5c:74:8c, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:49:c5:64:5c:74:8c, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
D/btif_config_util( 4484): enum_config(L300): in, key:4b:a1:34:a9:32:1d, value:DevType
D/btif_config_util( 4484): enum_config(L302): section name:Remote, key name:4b:a1:34:a9:32:1d, value name:DevType, value type:int
D/btif_config_util( 4484): enum_config(L343): out, key:4b:a1:34:a9:32:1d, value:DevType
D/btif_config_util( 4484): enum_config(L344): out, value:
V/BluetoothPbapService( 4484): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 4484): state: 13
V/BluetoothPbapService( 4484): Pbap Service closeService in
W/bt-btif ( 4484): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-obex ( 4484): Ignore event 10 in state 1
E/        ( 4484): ### ASSERT : vendor/lge/external/bluetooth/bluedroid_brcm/main/../iop_hooks/iop_db_hooks.c line 96 no handle (0) ###
E/bt-btif ( 4484): btif_hf_upstreams_evt: wrong handle = 0 
I/bt-btif ( 4484): HAL bt_op_callbacks->ops_state_cb
E/bt-btif ( 4484): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothOPPServiceJni( 4484): ops_state_cb(L223):  ops_state_cb state:3
D/OppService( 4484): onOpsStateChange() :3
V/BluetoothPbapService( 4484): successfully stopped pbap service
V/BluetoothPbapService( 4484): Pbap Service closeService out
D/OppService( 4484): Recieved MESSAGE_OPS_DISABLE
V/BluetoothPbapService( 4484): Pbap Service onDestroy
V/BluetoothPbapService( 4484): Pbap Service closeService in
V/BluetoothPbapService( 4484): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 4484): [BTUI] cleanup
D/BluetoothPbap( 7390): Proxy object disconnected
D/PbapServerProfile( 7390): Bluetooth service disconnected
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/LIA_SmartSetting(4.50.6)_LogCore( 7476): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7476): onReceive state= 13
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): selection= recipe_slug = "arrive_home_bluetooth"
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 57c30edb-3a2a-4ed0-98ec-7ed94f879838
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 57c30edb-3a2a-4ed0-98ec-7ed94f879838 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): status= 0
D/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onUpdate Bluetooth off
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_SmartSetting(4.50.6)_Recommender( 7476): onStatusChanged value= Bluetooth off
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - bafe996d-e0aa-41fe-b4b1-381133107c2e
V/LIA_SmartSetting(4.50.6)_SenseLocation( 7476): getCurrentPlaceId 
D/LIA_SmartSetting(4.50.6)_Recommender( 7476): not entered home
V/LIA_SmartSetting(4.50.6)_DeviceLogger( 7476): DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1457358081272, , settingStatus=Bluetooth off, deviceTypeOrdinal=1]
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - bafe996d-e0aa-41fe-b4b1-381133107c2e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LocationManagerService( 1280): getAllProviders()=[passive, gps, network]
D/DockEventReceiver( 7390): finishStartingService: stopping service
D/Ulp_jni ( 1280): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1280): JNI:system_update. Event-4
I/jxcore-log( 7441): ****TEST TOOK:  5082  ms ****
I/jxcore-log( 7441): 
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/jxcore-log( 7441): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7441): 
E/WifiStateMachine( 1280): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1280): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9b9fc9bc-089e-4a7b-a2f4-a039d608bcb2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9b9fc9bc-089e-4a7b-a2f4-a039d608bcb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter( 7476): insert start
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 012f0558-9752-4ee3-a667-bbb57ada0109
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 012f0558-9752-4ee3-a667-bbb57ada0109 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/DhcpStateMachine( 1280): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  461): Clearing all IP addresses on wlan0
I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 7
D/LIA_SmartSetting(4.50.6)_LocationDBManager( 7476): insertSettingInfo ID = 5421
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 99cac81d-2123-46ce-a4d3-fe28654d55cb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 99cac81d-2123-46ce-a4d3-fe28654d55cb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): onReceive(), ConnectedDeviceName : null , Num : 0
V/BluetoothOppReceiver( 4484): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 4484): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 4484): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 4484): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 4484): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1ce831ee-f8dc-4bb2-b9fd-5b1f1f1866e8
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1ce831ee-f8dc-4bb2-b9fd-5b1f1f1866e8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6dd19686-49ad-470b-89ad-4dfa598a7d40
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6dd19686-49ad-470b-89ad-4dfa598a7d40 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd( 1280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 7
V/BluetoothSapReceiver( 4484): [BTUI] checkServiceStart
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
V/WfdStateTracker( 4057): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1280): scanCount==0 - aborting
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 473e3a23-945a-42ae-8215-1f818169a959
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 473e3a23-945a-42ae-8215-1f818169a959 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3398): Remote
D/WifiOffDelayIfNotUsed( 1280): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LgWifiTrafficPoller( 1280): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
D/LGBluetoothAuthorization( 7390): [BTUI] cancel All Notification
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(17301632) by com.lge.bluetoothsetting
D/LgWifiTrafficPoller( 1280): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000001) by com.lge.bluetoothsetting
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000011) by com.lge.bluetoothsetting
D/WifiOffDelayIfNotUsed( 1280): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3398): Remote
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000021) by com.lge.bluetoothsetting
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000031) by com.lge.bluetoothsetting
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000041) by com.lge.bluetoothsetting
D/WifiScanningService( 1280): SCAN_AVAILABLE : 1
D/RttService( 1280): SCAN_AVAILABLE : 1
D/WifiNetworkAgent( 1280): NetworkAgent: NetworkAgent channel lost
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7eca0968-92ed-4e46-b7ed-2fe7c22bf1fe
D/WifiScanningService( 1280): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1280): DefaultState
D/RttService( 1280): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7eca0968-92ed-4e46-b7ed-2fe7c22bf1fe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothPermissionRequest( 7390): onReceive
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LGBluetoothAuthorization( 7390): [BTUI] cancel All Notification
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(17301632) by com.lge.bluetoothsetting
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000001) by com.lge.bluetoothsetting
V/WfdStateTracker( 4057): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 4057): WifiP2pState is changed : false
D/WfdsService( 4057): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 4057): Set the WFDS Monitor: false
D/libc-netbsd( 1280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WfdsMonitor( 4057): WFDS Monitor is stopped
D/WfdsService( 4057): STATE : WfdsDisabledState - enter
D/WfdsService( 4057): WFDS: Scanner is paused
D/CtrlSupplicant( 4057): Received on exit socket, terminate
D/WfdsDiscoveryStore( 4057): Clear Discovery Method Map: ScanAlwaysMode false
E/CtrlSupplicant( 4057): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 4057): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 4057): WfdsMonitorThread is received the interrupt - closing
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000011) by com.lge.bluetoothsetting
W/WfdsSession:Controller( 4057): DefaultState - msg [9441355] is not handled
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000021) by com.lge.bluetoothsetting
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000031) by com.lge.bluetoothsetting
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3b9905d6-e5ed-486c-8f80-f2fcb8ca514d
I/NotificationManager( 7390): com.lge.bluetoothsetting: cancel(-1000041) by com.lge.bluetoothsetting
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3b9905d6-e5ed-486c-8f80-f2fcb8ca514d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LGBluetoothStateChangeReceiver( 7390): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 06ab7a24-8eeb-4874-aec4-d19f138546ef
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 06ab7a24-8eeb-4874-aec4-d19f138546ef / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2390de7e-2f9d-489d-bbff-8d75cbbd4ed9
D/AuthorizationBluetoothService( 5205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2390de7e-2f9d-489d-bbff-8d75cbbd4ed9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/ConnectivityService( 1280): Default network via Wi-Fi disconnect. stop DSQN
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/DSQN    ( 1280): disableDataServiceNotify
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6885fdd2-6a7c-4898-9d55-21a337014781
D/DSQN    ( 1280): stop dsqn bin
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6885fdd2-6a7c-4898-9d55-21a337014781 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d64deca9-23d2-477d-b6dd-915f31af1672
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d64deca9-23d2-477d-b6dd-915f31af1672 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - adb18da9-114c-44cf-a58f-2150dca28a1e
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - adb18da9-114c-44cf-a58f-2150dca28a1e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/Finsky  ( 8101): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fd34b0e0-6de5-4fa7-bd7a-9d8d78ba0aeb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fd34b0e0-6de5-4fa7-bd7a-9d8d78ba0aeb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 46f38f3b-4098-43e6-a630-44be5a7eda4c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 46f38f3b-4098-43e6-a630-44be5a7eda4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f012d2aa-2add-422e-ac27-ab5f560931d7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f012d2aa-2add-422e-ac27-ab5f560931d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/CommandListener(  461): Clearing all IP addresses on wlan0
E/WifiStateMachine( 1280): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
D/WifiHS20( 1280): hidePasspointNotification off =false
D/WifiOffDelayIfNotUsed( 1280): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LgWifiTrafficPoller( 1280): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3398): Remote
V/WfdStateTracker( 4057): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1280): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1280): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1280): setSupplicantStateDISCONNECTED
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 7796bb58-49b3-49d2-8eb8-7999f2a8ba70
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 7796bb58-49b3-49d2-8eb8-7999f2a8ba70 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 8fee0203-fdde-4b7d-8163-3b46c63af0df
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 8fee0203-fdde-4b7d-8163-3b46c63af0df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/NetworkManagementService( 1280): hardware tether stats:NetworkStats: elapsedRealtime=47954
D/NetworkManagementService( 1280): getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=47955
D/NetworkManagementService( 1280):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=50355 rxPackets=88 txBytes=10531 txPackets=95 operations=0
D/NetworkManagementService( 1280):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/NetworkManagementService( 1280): hardware tether stats:NetworkStats: elapsedRealtime=47956
D/NetworkManagementService( 1280): getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=47957
D/NetworkManagementService( 1280):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=50683 rxPackets=92 txBytes=11847 txPackets=89 operations=0
D/NetworkManagementService( 1280):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 61c1ea30-78eb-4cf3-860b-e7f1662ba055
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 61c1ea30-78eb-4cf3-860b-e7f1662ba055 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/ConnectivityService( 1280): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1280):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1280):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/ConnectivityService( 1280): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - faea5ea3-bd8d-4da9-9206-770ff342d5c4
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - faea5ea3-bd8d-4da9-9206-770ff342d5c4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1280): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1280): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1280): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 3398): CM callback handler got msg 524292
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/Nat464Xlat( 1280): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/CSLegacyTypeTracker( 1280): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::a239:f7ff:fe6f:c95d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60}  everValidated{true}  lastValidated{true}  created{true}  explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1280): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1280): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1280): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1280): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1280): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering( 1280): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/FastDownloadService( 1280): [FastDN][FDS] received CONNECTIVITY_ACTION_IMMEDIATE for WIFI detailedState: DISCONNECTED
D/LocSvc_java( 1280): onReceive
D/FastDownloadService( 1280): [FastDN][FDS] WIFI is disconnected
D/LocSvc_java( 1280): got connectivity action
D/LocSvc_java( 1280): broadcast - no network connections
D/LocSvc_java( 1280): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java( 1280): Sending msg: 4 arg1:0 arg2:1
D/[LGE_DATA][PayPopUp_ko] ( 4118): intent received :android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1280): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1280): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1280): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering( 1280): MasterInitialState.processMessage what=3
W/QCNEJ   ( 4077): |CORE| No family connected
D/ConnectivityService( 1280): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/GpsLocationProvider( 1280): updateNetworkState unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/FastDownloadService( 1280): [FastDN][FDS] received CONNECTIVITY_ACTION for WIFI detailedState: DISCONNECTED
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9bc0f51e-5189-480b-b9d1-6d1e3d1a7615
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9bc0f51e-5189-480b-b9d1-6d1e3d1a7615 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/ConnectivityService( 1280): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1280): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1280): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering( 1280): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/FastDownloadService( 1280): [FastDN][FDS] received CONNECTIVITY_ACTION_IMMEDIATE for WIFI detailedState: DISCONNECTED
D/FastDownloadService( 1280): [FastDN][FDS] WIFI is disconnected
V/NetworkPolicy( 1280): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 4077): |CORE| No family connected
D/FastDownloadService( 1280): [FastDN][FDS] received CONNECTIVITY_ACTION for WIFI detailedState: DISCONNECTED
D/WIFI    ( 1280): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1280):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    ( 1280): evalRequest
D/WIFI    ( 1280):   done
D/WIFI_UT ( 1280): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_UT ( 1280):   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI_UT ( 1280): evalRequest
D/WIFI_UT ( 1280):   done
D/[LGE_DATA][PayPopUp_ko] ( 4118): intent received :android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1280): onReceive
D/LocSvc_java( 1280): got connectivity action
D/LocSvc_java( 1280): broadcast - no network connections
D/LocSvc_java( 1280): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java( 1280): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1280): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1280): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1280): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering( 1280): MasterInitialState.processMessage what=3
D/NetworkManagementService( 1280): Removing idletimer
E/ConnectivityService( 1280): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/Settings( 8101): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c639a728-339e-4545-8390-c9536453654c
W/Settings( 8101): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c639a728-339e-4545-8390-c9536453654c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/GpsLocationProvider( 1280): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/NotificationManager( 8101): com.android.vending: cancel(-1050172287) by com.android.vending
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b6805ff3-2c52-4320-8c53-596c952f6e8f
D/GpsLocationProvider( 1280): updateNetworkState unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b6805ff3-2c52-4320-8c53-596c952f6e8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - fc9a8edd-207d-427e-a5e4-75f090ba05f0
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - fc9a8edd-207d-427e-a5e4-75f090ba05f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - b20adf61-a0b1-4a82-bc8e-cb885de2fec5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - b20adf61-a0b1-4a82-bc8e-cb885de2fec5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4f08a1e3-0da4-4551-b49b-77bf8f81b275
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4f08a1e3-0da4-4551-b49b-77bf8f81b275 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ea50bff7-8fc8-4420-b3b5-f675cf05da43
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ea50bff7-8fc8-4420-b3b5-f675cf05da43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 39db361c-7fd9-4b33-b2eb-867d986a4563
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 39db361c-7fd9-4b33-b2eb-867d986a4563 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/wpa_supplicant( 5687): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 5687): monitor socket send errors count : 1
I/wpa_supplicant( 5687): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_4057-2\x00 that cannot receive messages
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/wpa_supplicant( 5687): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 2ad01bce-48f3-4847-ba33-00a73832084d
W/wpa_supplicant( 5687): USIM:  scard_deinit function
I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 4
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 2ad01bce-48f3-4847-ba33-00a73832084d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/Tethering( 1280): interfaceLinkStateChanged wlan0, true
D/Tethering( 1280): interfaceStatusChanged wlan0, true
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 755c7cc2-1bee-458b-a6ce-3e5783a8494d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 755c7cc2-1bee-458b-a6ce-3e5783a8494d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/Volley  ( 8101): [334] DiskBasedCache.clear: Cache cleared.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e6706500-5974-40a4-9412-3c889951aad5
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e6706500-5974-40a4-9412-3c889951aad5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/Volley  ( 8101): [327] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 8101): Skipping gmscore version check
,D/DhcpStateMachine( 1280): StoppedState
D/DhcpStateMachine( 1280): StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1280): Start proc 8160:com.google.android.youtube/u0a124 for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,I/ActivityManager( 1280): Killing 7711:com.android.managedprovisioning/u0a43 (adj 15): empty #22
,D/AndroidRuntime( 8158): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 8158): CheckJNI is OFF
,I/ActivityManager( 1280): Killing 7684:com.lge.voicerecorder/u0a41 (adj 15): empty #23
,W/CursorWrapperInner( 7732): Cursor finalized without prior close()
,I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 4
,D/Tethering( 1280): interfaceLinkStateChanged wlan0, true
D/Tethering( 1280): interfaceStatusChanged wlan0, true
,I/Netd    (  461): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 5687): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1280): interfaceLinkStateChanged wlan0, false
D/Tethering( 1280): interfaceStatusChanged wlan0, false
,D/Tethering( 1280): InitialState.processMessage what=4
D/Tethering( 1280): upstreamIface add type 0
D/Tethering( 1280): upstreamIface add type 1
D/Tethering( 1280): upstreamIface add type 4
D/Tethering( 1280): upstreamIface add type 5
D/Tethering( 1280): upstreamIface add type 7
D/Tethering( 1280): upstreamIface add type 9
D/Tethering( 1280): upstreamIface add type 18
D/Tethering( 1280): checkDunRequired: secureSetting is 2
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d073ef55-ec51-4487-a7ad-57fc9a9bac98
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d073ef55-ec51-4487-a7ad-57fc9a9bac98 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/AndroidRuntime( 8158): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1280): Start proc 8194:com.google.android.gms/u0a6 for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService
,I/art     (  498): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 365us total 25.922ms
,W/PackageSettings( 1280): Skipping PackageSetting{331f7bc5 com.test.thalitest/10353} due to missing metadata
,I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 319us total 20.910ms
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,W/ActivityManager( 1280): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 195us total 19.611ms
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@22ecc313 on behalf of 8101
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 121498(6MB) AllocSpace objects, 5(4MB) LOS objects, 33% free, 56MB/85MB, paused 1.919ms total 164.515ms
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/ActivityManager( 1280): Force stopping com.example.hello appid=10361 user=-1: uninstall pkg
I/ActivityManager( 1280): Killing 7441:com.example.hello/u0a361 (adj 0): stop com.example.hello
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e24e4e4c-1531-4561-80c9-e1e46dd8734c
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e24e4e4c-1531-4561-80c9-e1e46dd8734c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ResourcesManager( 8160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WindowState( 1280): WIN DEATH: Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher( 1280): Focus left window: Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher( 1280): Window went away: Window{1435a48 u0 com.example.hello/com.example.hello.MainActivity}
,D/bt_vendor( 4484): op for 6
W/bt-l2cap( 4484): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4484): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4484): ag scb idx 1 not allocated
W/bt-btif ( 4484): ag scb idx 2 not allocated
E/bt-btif ( 4484): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 4484): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4484): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4484): ag scb idx 1 not allocated
W/bt-btif ( 4484): ag scb idx 2 not allocated
E/bt-btif ( 4484): BTA AG is already disabled, ignoring ...
E/bt-btif ( 4484): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 4484): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 4484): select_read return size <=0:0, exiting userial_read_thread
D/bt_vendor( 4484): op for 9
D/bt_hwcfg( 4484): hw_epilog_process
,D/bt_vendor( 4484): op for 4
I/bt_userial_vendor( 4484): device fd = 73 close
,W/ActivityManager( 1280): Force removing ActivityRecord{18ed6004 u0 com.example.hello/.MainActivity t53}: app died, no saved state
,D/bt_vendor( 4484): op for 0
,D/bt_vendor( 4484): cleanup
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/GKI_LINUX( 4484): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/GKI_LINUX( 4484): gki_task task_id=0 [BTU] terminating
E/NetlinkEvent(  461): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/GKI_LINUX( 4484): GKI_destroy_task(): task [BTU] terminated
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,I/bt-btif ( 4484): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4484): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/WifiOffDelayIfNotUsed( 1280): stopMonitoring
,D/SplitWindowPolicy( 4057): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
W/ActivityManager( 1280): Spurious death for ProcessRecord{f92c80d 7441:com.example.hello/u0a361}, curProc for 7441: null
D/SplitWindowPolicy( 4057): topRunningActivity=ActivityInfo{322d3988 co.....MainActivity}, taskId=53, activityType=0, bIsSplit=false
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/HeadsetService( 4484): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/Tethering( 1280): sendTetherStateChangedBroadcast 0, 0, 0
W/ActivityManager( 1280): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hid.HidService
I/ActivityManager( 1280): Force stopping com.example.hello appid=10361 user=0: pkg removed
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/SplitWindowPolicy( 4057): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 4057): topRunningActivity=ActivityInfo{2bf91f21 co.....Launcher}, taskId=51, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 4311): onStart
I/[LGHome]EVENT( 4311): onResume
,D/Finsky  ( 8101): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8101): [1] Libraries$2.run: Finished loading 1 libraries.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 282d3e17-345f-453d-9a06-0acf4fc6a925
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 282d3e17-345f-453d-9a06-0acf4fc6a925 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/AppInfoDao( 7561): topacitivyt exist app = com.lge.launcher2
,W/ResourcesManager( 8194): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AppInfoDao( 7561): topacitivyt update app = com.lge.launcher2 time = 2016-03-07 14:41 date = 20160307
,I/LGBluetoothHfpAdapter( 4484): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 4484): Cleaning up Bluetooth Handsfree callback object
D/HeadsetStateMachine( 4484): Exit Disconnected: -1
,D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/WfdsService( 4057): Supplicant Connection state is changed : false
,D/WfdsService( 4057): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 4057): Set the WFDS Monitor: false
D/WfdsMonitor( 4057): WFDS Monitor is stopped
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,V/WfdStateTracker( 4057): WfdStateTracker handleDirectStateChangedEvent: 0
I/LGCover ( 5225): PackageIntentReceiver: PackageIntentReceiver Received Broadcast : android.intent.action.PACKAGE_REMOVED
I/InputReader( 1280): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister( 1280): removeObsoleteFile: deleting file=53_task.xml
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/GeofencerStateMachine( 5205): Ignoring removeGeofence because network location is disabled.
,D/LIA_Service_RemotePackageHandler( 4268): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/NetworkManagementService( 1280): hardware tether stats:NetworkStats: elapsedRealtime=48870
I/WifiServerServiceExt( 1280): WIFI_STATE_CHANGED_ACTION [1]
D/NetworkManagementService( 1280): getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=48877
D/NetworkManagementService( 1280):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=50355 rxPackets=88 txBytes=10531 txPackets=95 operations=0
D/NetworkManagementService( 1280):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/A2dpService( 4484): Received stop request...Stopping profile...
D/A2dpStateMachine( 4484): Exit Disconnected: -1
I/WifiServerServiceExt( 1280): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1280): batteryPsActivateMsgHandler : this is not treated
,D/NetworkManagementService( 1280): hardware tether stats:NetworkStats: elapsedRealtime=48878
D/NetworkManagementService( 1280): getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=48880
D/NetworkManagementService( 1280):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=50683 rxPackets=93 txBytes=11847 txPackets=89 operations=0
D/NetworkManagementService( 1280):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/System.err( 4290): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.pan.PanService
W/System.err( 4290): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4290): 	at com.lge.mlt.watcher.LDBOnAppWatcher$2.onReceive(LDBOnAppWatcher.java:69)
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
W/System.err( 4290): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1038)
W/System.err( 4290): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4290): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4290): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4290): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
W/System.err( 4290): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4290): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4290): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
W/System.err( 4290): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass()
V/JNIHelp ( 8160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.camera.app.QuickWindowCameraActivity
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.mms.quickcover.QuickCoverActivity
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.contacts.activities.QuickCircleActivity
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.music.MusicQuickCircle
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.lifetracker.QuickCover
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity
D/LGCover ( 5225): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity
,D/GmsApplication( 8194): Forcing legacy multidex for PROD_LMP build.
,D/LGCover ( 5225): QuickCoverSettingsUtil.java:215 isSupportsQuickCircle(): cover_type : 3
D/LGCover ( 5225): QuickCoverSettingsUtil.java:226 isSupportsYGCover(): cover_type : 3
I/MultiDex( 8194): VM with version 2.1.0 has multidex support
I/MultiDex( 8194): install
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6313603d-3b9f-44fa-9602-eefcf2aeae06
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6313603d-3b9f-44fa-9602-eefcf2aeae06 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/Settings( 5205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 4118): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/MultiDex( 8194): MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
,D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.lge.music.MusicQuickCircle  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.lge.lifetracker.QuickCover  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity  true
D/LGCover ( 5225): PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity  true
I/LGCover ( 5225): PackageIntentReceiver: PackageIntentReceiver Received Broadcast : android.intent.action.PACKAGE_FULLY_REMOVED
I/art     ( 4368): Explicit concurrent mark sweep GC freed 120463(6MB) AllocSpace objects, 16(2MB) LOS objects, 35% free, 29MB/45MB, paused 728us total 37.585ms
I/MirrorLink_UPnP( 4368): pkgReceiver : ACTION_PACKAGE_REMOVED:com.example.hello [TmAppListManager.java:380:onReceive()]
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f461309b-5114-40b1-811c-a1d958c2cdd5
D/MirrorLink_UPnP( 4368): removeApp : com.example.hello [TmAppListManager.java:1503:removeApp()]
I/[LGHome]LGActivityUtil( 4311): [LGActivityUtil.java:204:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f461309b-5114-40b1-811c-a1d958c2cdd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4484): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
,D/LGBluetoothA2dpAdapter( 4484): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 4484): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 4484): [BTUI] terminate
,I/MultiDex( 8194): loading existing secondary dex files
,I/MultiDex( 8194): load found 3 secondary dex files
,D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/[LGHome]EVENT( 4311): onResume end
I/Activity( 4311): Activity.onPostResume() called 
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 9e9d2d55-39f8-4b01-a1c1-c18e9a35e893
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 9e9d2d55-39f8-4b01-a1c1-c18e9a35e893 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/BluetoothAdapterService( 4484): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
,D/BluetoothManagerService( 1280): Message: 31
,D/ActionManagerService( 4204): notifyUserLog: 1000004
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
,I/MultiDex( 8194): install done
,D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4484): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,W/BluetoothAdapterService( 4484): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
,D/BluetoothA2dp( 7390): Proxy object disconnected
,D/A2dpProfile( 7390): Bluetooth service disconnected
,D/Finsky  ( 8101): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f31e07a7-2cb2-4be9-b0ea-94e2cdef2998
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f31e07a7-2cb2-4be9-b0ea-94e2cdef2998 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BluetoothA2dp( 4684): Proxy object disconnected
,D/WallpaperManager( 4311): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/HidService( 4484): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
,D/BluetoothAdapterState( 4484): Stopping profile services that were post enabled
I/ProviderInstaller( 8160): Installed default security provider GmsCore_OpenSSL
,D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothInputDevice( 7390): Proxy object disconnected
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/HidProfile( 7390): Bluetooth service disconnected
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 4484): Unbinding service...
I/SystemUI[Framework]( 1280): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
I/Choreographer( 3398): Skipped 57 frames!  The application may be doing too much work on its main thread.
I/[SystemUI]NetworkController( 3398): onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/SystemUI[Framework]( 1280): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ba56745,  pkg=Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx( 1280): Call!!!getLGSystemUiVisibility. =0x0
I/SystemUI[Framework]( 1280): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/StatusBarManagerServiceEx( 1280): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1280): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 3398): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/administrator( 1280): Handling package changes for user 0
,D/HeadsetPhoneState( 4484): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 4484): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 4484): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 4484): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 4484): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4484): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 4484): [BTUI] LGBluetoothHfpAdapter cleanup
,D/InputDispatcher( 1280): Focus entered window: Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1280): ResTable_typeSpec entry count inconsistent: given 1, previously 483
,D/HealthService( 4484): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - c98f3939-3834-4d49-9d43-d5750a416c37
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - c98f3939-3834-4d49-9d43-d5750a416c37 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/PanService( 4484): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BtGatt.DebugUtils( 4484): handleDebugAction() action=null
,D/BtGatt.GattService( 4484): Received stop request...Stopping profile...
D/BtGatt.GattService( 4484): stop()
D/BtGatt.AdvertiseManager( 4484): advertise clients cleared
,I/[SystemUI]QSlideListController( 3398): onReceive = android.intent.action.PACKAGE_REMOVED
,D/LGBluetoothGattAdapter( 4484): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4a3f534f-67b0-42d7-90d4-82287072acc9
D/Finsky  ( 8101): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4a3f534f-67b0-42d7-90d4-82287072acc9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothPan( 7390): BluetoothPAN Proxy object disconnected
D/PanProfile( 7390): Bluetooth service disconnected
,D/BluetoothMapService( 4484): Received stop request...Stopping profile...
D/BluetoothMapService( 4484): stop()
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothMapEmailAppObserver( 4484): deinitObservers()
D/BluetoothMapEmailAppObserver( 4484): removeReceiver()
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 5ad1145f-ef5f-4219-b387-543ca4782e0b
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 5ad1145f-ef5f-4219-b387-543ca4782e0b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/[LGHome]EVENT( 4311): [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/[LGHome]EVENT( 4311): [Launcher.java:5476:setEnableShakeHandlers()]enableShakeHandlers
D/[Concierge][ConciergeWidgetLayout]( 4311): notifyExtViewAvailable
,I/ActivityManager( 1280): Waited long enough for: ServiceRecord{4d1588f u0 com.android.mms/.service.SwitchedService}
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
,V/SplitUIManager( 6774): split_name #14 / not available #0
,D/SplitUIService( 6774): removed split : 
,D/BluetoothMap( 7390): Proxy object disconnected
D/MapProfile( 7390): Bluetooth service disconnected
,D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/SapService( 4484): Received stop request...Stopping profile...
D/SapService( 4484): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 4484): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 4484): [BTUI] terminateSapManager
,W/InputMethodManagerService( 1280): Got RemoteException sending setActive(false) notification to pid 7441 uid 10361
,D/LgeBluetoothSimManager( 4118): [BTUI] SAP_DISABLE_EVT
,D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
I/BluetoothA2dpServiceJni( 4484): cleanupNative
I/GKI_LINUX( 4484): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4484): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4484): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/**OppService( 4484): Received stop request...Stopping profile...
D/OppService( 4484): Stopping Bluetooth OppService
D/OppService( 4484): cleanup OPP Service
W/BluetoothOPPServiceJni( 4484): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 4484): Cleaning up Bluetooth OPP callback object
,D/OppService( 4484): remove callbacks and handler
D/LGBluetoothOppAdapter( 4484): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 4484): cleanup done
D/BluetoothAdapterService( 4484): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d389008
W/BluetoothHidServiceJni( 4484): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 4484): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 4484): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 4484): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 4484): Cleaning up Bluetooth Health object
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 3398): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 3398): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 4484): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 4484): Cleaning up Bluetooth PAN callback object
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 4484): Handler(): got msg=4
D/BluetoothMapService( 4484): MAP Service closeService in
D/LGBluetoothMapAdapter( 4484): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 4484): MAP Service closeService out
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 4484): cleanup()
D/BluetoothMapService( 4484): MAP Service closeService in
D/LGBluetoothMapAdapter( 4484): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 4484): MAP Service closeService out
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4484): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4484): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 4484): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 4484): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(221810696)( 4484): handleMessage(), - Message: 1
D/BluetoothAdapterService(221810696)( 4484): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 4484): isTurningOnRadio()=false
D/BluetoothAdapterState( 4484): isTurningOffRadio()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4484): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4484): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(221810696)( 4484): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 4484): cleanup OPP Service
D/OppService( 4484): remove callbacks and handler
D/LGBluetoothOppAdapter( 4484): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 4484): cleanup done
D/BluetoothAdapterState( 4484): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 4484): Setting state to 10
I/BluetoothAdapterState( 4484): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(221810696)( 4484): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService( 1280): Message: 60
D/LGBluetoothDeviceModeControllManager( 4484): LGAdapterState - setDeviceMode : 0
D/LGBluetoothDeviceModeControllManager( 4484): LGAdapterState - setDeviceMode : 0
I/BluetoothAdapterState( 4484): Entering OffState
D/BluetoothManagerService( 1280): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1280): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothA2dp( 1280): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 73bfab76-3ff3-4db4-a38d-106418180f7c
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 73bfab76-3ff3-4db4-a38d-106418180f7c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/Timeline( 4311): Timeline: Activity_idle id: android.os.BinderProxy@2c54b562 time:49078
,I/art     ( 3398): Explicit concurrent mark sweep GC freed 7731(343KB) AllocSpace objects, 109(15MB) LOS objects, 26% free, 87MB/119MB, paused 1.053ms total 47.733ms
,E/xt9input_alpha( 3645): alpha_data::getExactType() failed. status(0x4)
,I/SystemUI[Framework]( 1280): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1280): Call!!!getLGSystemUiVisibility. =0x0
I/SystemUI[Framework]( 1280): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ba56745,  pkg=Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/StatusBarManagerServiceEx( 1280): setLGSystemUiVisibility(0x0)
I/SystemUI[Framework]( 1280): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/StatusBarManagerServiceEx( 1280): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{b48f860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothHeadset( 4684): onBluetoothStateChange: up=false
I/ActivityManager( 1280): Start proc 8234:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
D/BluetoothHeadset( 4684): Proxy object disconnected
D/JobSchedulerService( 1280): Receieved: android.intent.action.PACKAGE_REMOVED
D/BluetoothHeadset( 4118): onBluetoothStateChange: up=false
D/BackupManagerService( 1280): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothHeadset( 4118): Proxy object disconnected
D/BluetoothInputDevice( 7390): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothHeadset( 4118): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1280): Proxy object disconnected
D/BluetoothHeadset( 4118): Proxy object disconnected
V/SplitUIManager( 6774): split_name #14 / not available #0
I/SplitUIService( 6774): split app #14
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 20327(988KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 57MB/85MB, paused 7.632ms total 218.611ms
D/BluetoothHeadset( 7390): Proxy object disconnected
D/HeadsetProfile( 7390): Bluetooth service disconnected
,D/BluetoothMap( 7390): onBluetoothStateChange: up=false
D/BluetoothHeadset( 4118): Proxy object disconnected
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 60259dd3-530d-4b02-a588-32a83785d4e7
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 60259dd3-530d-4b02-a588-32a83785d4e7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/AudioService( 1280): onServiceDisconnected: Bluetooth profile: 1
I/ActivityManager( 1280): Displayed com.lge.launcher2/.Launcher: +296ms (total +8s115ms)
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothHeadset( 4118): onBluetoothStateChange: up=false
D/PhoneStatusBar( 3398): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 3398): NavigationKey Color is changed(WHITE -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 3398):  BarMode=4, Theme=BLACK, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 3398): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
D/BluetoothA2dp( 4684): onBluetoothStateChange: up=false
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6796770b-5fb6-4726-a0e8-78553dc068c2
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6796770b-5fb6-4726-a0e8-78553dc068c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BluetoothHeadset( 7390): onBluetoothStateChange: up=false
D/BluetoothPbap( 7390): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothPan( 7390): onBluetoothStateChange on: false
,D/BluetoothA2dp( 7390): onBluetoothStateChange: up=false
,D/BluetoothAdapterService(221810696)( 4484): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@394cf67f
,D/BluetoothManagerService( 1280): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1280): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - a53bfb02-0d5b-4b75-bd74-930b138e9929
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - a53bfb02-0d5b-4b75-bd74-930b138e9929 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BarTransitions( 3398): draw background and invalidate : color = f2000000
,D/BarTransitions( 3398): draw background and invalidate : color = ee000000
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ResourcesManager( 1280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1280): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1280): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1280): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@de6016a mBinding = false
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0e104402-cca0-4d90-a975-45cced602f6d
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0e104402-cca0-4d90-a975-45cced602f6d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothManagerService( 1280): Sending unbind request.
D/BluetoothAdapterService(221810696)( 4484): onUnbind() - calling cleanup
D/BluetoothManagerService( 1280): Bluetooth State Change Intent: 13 -> 10
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/BluetoothAdapterService(221810696)( 4484): cleanup()
D/LGBluetoothAPIService( 4057): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BleQmManagerService( 4057): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 4057): Message: 2
D/LGBluetoothAPIService( 4057): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@15147f46 mBinding = false
D/LGBluetoothAPIService( 4057): Sending unbind request.
,E/LGBluetoothEventManager( 7390): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,I/art     ( 8158): System.exit called, status: 0
W/ResourcesManager( 8234): Asset path '/system/framework/com.lge.locksettings.jar' does not exist or contains no resources.
I/AndroidRuntime( 8158): VM exiting with result code 0.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 766bfdf6-64a9-4048-9134-1b8b1aabd6d0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 766bfdf6-64a9-4048-9134-1b8b1aabd6d0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/BluetoothAdapter( 3398): 28887129: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3398): 28887129: getState() :  mService = null. Returning STATE_OFF
I/[SystemUI]QuickSettingsHandler( 3398): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 3398): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,D/LGBluetoothEventManager( 7390): [BTUI] clear device connection state
D/BluetoothAdapter( 5205): 420360478: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5205): 420360478: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService(221810696)( 4484): cleanup() - Cleaning up adapter native
I/bt-btif ( 4484): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 4484): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 4484): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 4484): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 4484): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 4484): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4484): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4484): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4484): GKI_exit_task 2 done
I/GKI_LINUX( 4484): GKI_exit_task 1 done
I/GKI_LINUX( 4484): GKI_exit_task 0 done
I/BluetoothServiceJni( 4484): cleanupNative: return from cleanup
,W/LGBluetoothServiceJni( 4484): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 4484): [BTUI] unregister observer for LG device name DB
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0048bf62-4366-4a74-907b-ce3b06c110bd
D/BluetoothAdapterService(221810696)( 4484): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(221810696)( 4484): cleanup() done
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0048bf62-4366-4a74-907b-ce3b06c110bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/art     ( 4484): System.exit called, status: 0
I/AndroidRuntime( 4484): VM exiting with result code 0, cleanup skipped.
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - f8d7d334-b7f8-4cf1-abd3-dc9816b57553
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - f8d7d334-b7f8-4cf1-abd3-dc9816b57553 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 3315adda-1603-4fed-94f4-cc4f279135a8
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 3315adda-1603-4fed-94f4-cc4f279135a8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - d4993ef2-3ed9-4c07-980c-97875d8b93da
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - d4993ef2-3ed9-4c07-980c-97875d8b93da / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - ba25acd0-62b0-47e8-a927-eee5b33e7ca7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - ba25acd0-62b0-47e8-a927-eee5b33e7ca7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
D/KeyguardModel( 3398): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 3398): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 25be324e-8988-406d-848c-db6b87187ea0
D/KeyguardModel( 3398): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 3398): createShortcutInfo...
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 25be324e-8988-406d-848c-db6b87187ea0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 1da2a246-22d1-4f91-a862-4e7a90cd52eb
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 1da2a246-22d1-4f91-a862-4e7a90cd52eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ResourcesManager( 3398): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/asset   ( 3398): Asset path /system/framework/com.lge.telephony.sms.jar is neither a directory nor file (type=1).
W/ResourcesManager( 3398): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 3398): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3398): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 3398): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 3398): createShortcutInfo...
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 41c53c33-50d8-49ac-98b2-eabba89498e6
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 41c53c33-50d8-49ac-98b2-eabba89498e6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,W/ResourcesManager( 3398): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3398): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4019f137-59a3-4201-9f09-3519bb9ac520
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4019f137-59a3-4201-9f09-3519bb9ac520 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/KeyguardModel( 3398): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 3398): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4c5d7f71-8d54-49a4-9e27-dd68168afda6
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4c5d7f71-8d54-49a4-9e27-dd68168afda6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
W/ResourcesManager( 3398): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3398): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
W/ResourcesManager( 3398): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/PackageManager( 3398): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 3398): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 6c991d0f-6693-471e-bb41-d5d13b1472eb
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 6c991d0f-6693-471e-bb41-d5d13b1472eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/KeyguardModel( 3398): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 3398): createShortcutInfo...
I/[LGHome]EVENT( 4311): [LauncherModel.java:199:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ActivityManager( 1280): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1280): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
D/FMFRW_FmProxy( 4057): Fm Proxy object disconnected
,V/AudioFlinger(  466): 4484 died, releasing its sessions
V/AudioFlinger(  466):  pid 4118 @ 0
V/AudioFlinger(  466):  pid 4588 @ 1
D/LGBluetoothUserBindClient( 7390): [BTUI] onServiceDisconnected
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 4f948d0f-e5bd-4a2f-bc7b-b9736bb93386
,V/JNIHelp ( 8194): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 4f948d0f-e5bd-4a2f-bc7b-b9736bb93386 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/[LGHome]Launcher.Model( 4311): onPackageRemoved=com.example.hello for UserHandle{0}
,D/KeyguardModel( 3398): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 3398): createShortcutInfo...
,D/KeyguardModel( 3398): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 3398): createShortcutInfo...
W/ContextImpl( 7390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
,W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3398): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e77c7fbe-1bbd-422b-9d53-596833e396cd
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e77c7fbe-1bbd-422b-9d53-596833e396cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/LIA_SmartSetting(4.50.6)_LogCore( 7476): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7476): onReceive state= 10
D/DockEventReceiver( 7390): finishStartingService: stopping service
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): selection= recipe_slug = "arrive_home_bluetooth"
D/KeyguardModel( 3398): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 3398): createShortcutInfo...
D/KeyguardModel( 3398): handleShortcutListChanged...
W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 3398): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7476): status= 0
D/LIA_SmartSetting(4.50.6)_ContextDetector( 7476): onUpdate Bluetooth off
,D/KeyguardModel( 3398): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 3398): createShortcutInfo...
,W/ResourceType( 3398): No package identifier when getting value for resource number 0x00000000
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - cb10dc0e-4956-4101-9dcd-07d616009e00
W/PackageManager( 3398): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - cb10dc0e-4956-4101-9dcd-07d616009e00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_SmartSetting(4.50.6)_Recommender( 7476): onStatusChanged value= Bluetooth off
,V/LIA_SmartSetting(4.50.6)_SenseLocation( 7476): getCurrentPlaceId 
D/LIA_SmartSetting(4.50.6)_Recommender( 7476): not entered home
V/LIA_SmartSetting(4.50.6)_DeviceLogger( 7476): DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1457358082684, , settingStatus=Bluetooth off, deviceTypeOrdinal=1]
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/KeyguardModel( 3398): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 3398): createShortcutInfo...
I/ProviderInstaller( 8194): Installed default security provider GmsCore_OpenSSL
D/LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter( 7476): insert start
D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 99d66707-1bc4-42a7-a719-ea82a245eaba
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 99d66707-1bc4-42a7-a719-ea82a245eaba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/NotificationManager( 8194): com.google.android.gms: cancel(10436) by com.google.android.gms
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,I/NotificationManager( 8194): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - afa80763-76f5-49dd-bcd6-f8618d033b2e
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - afa80763-76f5-49dd-bcd6-f8618d033b2e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/KeyguardModel( 3398): handleShortcutListChanged...
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 70ec249a-13ac-4ded-85e9-c71f134273c7
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 70ec249a-13ac-4ded-85e9-c71f134273c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_SmartSetting(4.50.6)_LocationDBManager( 7476): insertSettingInfo ID = 5422
,D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): onReceive(), ConnectedDeviceName : null , Num : 0
,D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7390): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information - BluetoothSettings
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - 0a200fd7-7bf9-441f-95a6-862fda1b7095
,I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - 0a200fd7-7bf9-441f-95a6-862fda1b7095 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,E/SQLiteDatabase( 8194): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 8194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteDatabase( 8194): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 8194): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteDatabase( 8194): 	at android.content.ContentProvider.query(ContentProvider.java:1000)
E/SQLiteDatabase( 8194): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:214)
E/SQLiteDatabase( 8194): 	at android.content.ContentResolver.query(ContentResolver.java:490)
E/SQLiteDatabase( 8194): 	at android.content.ContentResolver.query(ContentResolver.java:434)
E/SQLiteDatabase( 8194): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteDatabase( 8194): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 8194): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8194): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8194): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 8194): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 8194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteOpenHelper( 8194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteOpenHelper( 8194): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 8194): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteOpenHelper( 8194): 	at android.content.ContentProvider.query(ContentProvider.java:1000)
E/SQLiteOpenHelper( 8194): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:214)
E/SQLiteOpenHelper( 8194): 	at android.content.ContentResolver.query(ContentResolver.java:490)
E/SQLiteOpenHelper( 8194): 	at android.content.ContentResolver.query(ContentResolver.java:434)
E/SQLiteOpenHelper( 8194): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteOpenHelper( 8194): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 8194): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 8194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 8194): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 8194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 8194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 8194): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 8194): Opened reminders.db in read-only mode
,I/ActivityManager( 1280): Start proc 8268:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,E/SQLiteDatabase( 8194): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 8194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteDatabase( 8194): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8194): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 8194): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 8194): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8194): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8194): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager( 1280): Killing 7732:com.lge.cloudhub/u0a73 (adj 15): empty #22
,E/AndroidRuntime( 8194): FATAL EXCEPTION: AsyncTask #2
E/AndroidRuntime( 8194): Process: com.google.android.gms, PID: 8194
E/AndroidRuntime( 8194): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 8194): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 8194): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 8194): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 8194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 8194): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 8194): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 8194): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 8194): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 8194): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/AndroidRuntime( 8194): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8194): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8194): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 8194): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 8194): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 8194): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 8194): 	... 4 more
,D/NativeLibraryUtils( 8194): Install completed successfully. count=19 extracted=0
,I/qdhwcomposer(  416): handle_blank_event: dpy:1 panel power state: 0
,E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=32
E/qdoverlay(  416): src msmfb_img w=2944 h=2560 format=5 MDP_RGB_888
E/qdoverlay(  416): src_rect mdp_rect x=720 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
,E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=32
E/qdoverlay(  416): src msmfb_img w=2944 h=2560 format=5 MDP_RGB_888
E/qdoverlay(  416): src_rect mdp_rect x=720 y=100 w=1440 h=2292
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=100 w=1440 h=2292
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
,D/LCardEmulationManager( 4183): setRequireHCEConfirmvalue : true
,D/LIA_Informant_RecoverableAlarmManager( 7293): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7293): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7293): restoreAllAlarm() : sharedPreferences key - e91d5fa6-391f-43de-bc3f-33cf15f8dcd5
I/LIA_Informant_RecoverableAlarmManager( 7293): getPendingIntent() : key - e91d5fa6-391f-43de-bc3f-33cf15f8dcd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LCardEmulationManager( 4183): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 4183): getDefaultRoute
,I/qdhwcomposer(  416): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
,E/qdhwcomposer(  416): hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
E/SurfaceFlinger(  416): eventControl(0, 0) failed Cannot send after transport endpoint shutdown

```
